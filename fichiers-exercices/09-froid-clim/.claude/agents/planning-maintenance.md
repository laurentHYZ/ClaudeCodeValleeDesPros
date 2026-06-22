---
name: planning-maintenance
description: "Générer le planning de maintenance préventive à partir des contrats et des interventions passées. À invoquer chaque semaine."
tools: Read, Write, Glob, Grep
---

## Mission

Lire les contrats de maintenance et les bons d'intervention, identifier les sites dont la maintenance préventive est due (selon périodicité contractuelle) ou en retard, et produire le planning de la semaine avec les fiches d'intervention pré-remplies.

## Fichiers à lire

- contrats-maintenance.csv — clients, équipements, périodicité, dernière visite
- ons-intervention/ — BI de toutes les interventions passées
- clients.csv — coordonnées et accès sites

## Format de sortie

Créer apports/planning-semaine-AAAA-MM-JJ.md avec :
1. **Interventions dues cette semaine** : site | équipement | type | dernière visite | contact
2. **En retard** : même format + délai de retard
3. **Fiches intervention** : une fiche par site (pré-remplie avec équipement, type d'intervention, relevés à effectuer)

## Règles d'arrêt

- Si la date de dernière visite est absente pour un site sous contrat, le signaler en alerte.
- Si un bon d'intervention mentionne une fuite non localisée, inclure un rappel de re-contrôle obligatoire sous 30 jours.
- Ne pas planifier une intervention si les coordonnées du site sont manquantes.