# Dossier d'exercices — E-réputation / avis clients (fictif)

Vous gérez les avis du client fictif « Habitat Rénov 83 ». Contenu : exports d'avis avril et mai,
fiche établissement avec charte de réponse.

Exercices du tutoriel (leçon 8 — E-réputation) :
1. Répondre à un mois d'avis → avis-mai.csv + fiche-etablissement.txt
2. Détection d'avis suspects → avis-mai.csv
3. Rapport client mensuel → avis-avril.csv + avis-mai.csv

Tous les avis et auteurs sont fictifs.

## Fichiers ajoutés

- `avis-mars.csv` (tendance sur 3 mois), `contrat-abonnement.pdf` (engagements 72 h et objectif 4,2), `export-fiche-google.csv` (statistiques de la fiche) — utiles aux exercices 1 et 3.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Réponds aux avis. »
Observez le résultat et notez ce qui manque. Puis lancez le prompt complet du tutoriel
(leçon 8) et comparez. La différence entre les deux résultats, c'est ce que la formation
vous apprend (leçon 4 : les cinq règles).

## Questions de réflexion (après chaque exercice)

1. Qu'avez-vous oublié de préciser — et qu'est-ce que Claude a supposé à votre place ?
2. Comment avez-vous vérifié le résultat ? (un total recalculé, une pièce ouverte au hasard)
3. Que changeriez-vous dans votre prompt la prochaine fois — mérite-t-il de devenir une /compétence ?

## Mode guidé et relecteur

- Tapez `/demarrer` dans Claude Code (dossier ouvert) : Claude devient votre formateur et
  vous fait faire les exercices pas à pas, en français.
- À la fin d'un exercice, demandez la critique du personnage « Juriste conformité (avis en ligne) »
  (sous-agent `juriste-conformite`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.
