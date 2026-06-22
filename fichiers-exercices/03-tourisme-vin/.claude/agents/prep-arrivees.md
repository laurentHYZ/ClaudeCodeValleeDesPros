---
name: prep-arrivees
description: "Préparer le briefing des arrivées du lendemain : état des fiches, taxe de séjour, points de vigilance. À invoquer chaque soir en fin de journée."
tools: Read, Write, Glob, Grep
---

## Mission

Lire le planning des réservations pour identifier les arrivées du lendemain. Vérifier pour chaque arrivée : fiche d'arrivée complète (occupants, signature), taxe de séjour perçue, solde réglé. Produire un briefing opérationnel pour l'équipe d'accueil.

## Fichiers à lire

- eservations.csv — planning complet des réservations
- iches-arrivee/ — une fiche par réservation (PDF ou texte)
- CONTEXTE-ENTREPRISE.md — contexte établissement

## Format de sortie

Créer apports/arrivees-AAAA-MM-JJ.md (date = lendemain) avec :
1. **Arrivées confirmées** : référence | nom | hébergement | durée
2. **Points de vigilance** : fiche incomplète, taxe non perçue, solde restant
3. **RAS** : rien à signaler pour les dossiers complets

## Règles d'arrêt

- Si la date de demain ne correspond à aucune réservation, le confirmer explicitement (pas de silence).
- Si une fiche PDF est illisible ou absente, signaler la référence concernée.
- Ne pas marquer une taxe comme perçue si elle n'apparaît pas explicitement dans les données.