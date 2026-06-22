---
name: controle-pointages
description: "Comparer le planning et les pointages de la semaine, lister les écarts, générer les relances impayés. À invoquer chaque lundi matin."
tools: Read, Write, Glob, Grep
---

## Mission

Chaque lundi, comparer planning-mai.xlsx et pointage-mai.xlsx, produire un tableau des écarts (site, salarié, heures prévues vs réalisées, motif si connu), puis lister les clients avec impayés à relancer selon impayes.csv (niveau de relance selon l'ancienneté : 1 = 30-59 j, 2 = 60-89 j, mise en demeure = 90 j+).

## Fichiers à lire

- planning-mai.xlsx — heures prévues par salarié et par site
- pointage-mai.xlsx — heures réellement pointées
- impayes.csv — créances en attente avec dates de facture
- cahier-liaison-arcades.txt — contexte client (optionnel, pour compléter les écarts)

## Format de sortie

Créer apports/controle-AAAA-MM-JJ.md avec :
1. **Tableau des écarts** : salarié | site | prévu | réalisé | écart | observation
2. **Relances à envoyer** : client | montant | ancienneté | niveau de relance

## Règles d'arrêt

- Si un fichier source est absent ou illisible, s'arrêter et le signaler avant de continuer.
- Si un écart dépasse 20 h sans observation connue, le signaler séparément en tête de rapport.
- Ne pas inventer de motifs pour les absences non documentées.