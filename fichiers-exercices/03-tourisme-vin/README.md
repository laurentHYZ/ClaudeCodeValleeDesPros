# Dossier d'exercices — Tourisme / camping / viticulture (fictif)

Domaine fictif : camping Les Restanques & chambres d'hôtes La Lézardière, avec cave.
Contenu : export réservations de mai, registre de cave, factures vin, demandes clients types.

Exercices du tutoriel (leçon 8 — Tourisme & Vin) :
1. Taxe de séjour → reservations-mai.csv
2. Contrôle avant DRM → registre-cave.xlsx + factures-vin.csv
3. Réponses types → demandes-clients.txt

Toutes les données sont fictives.

## Fichiers ajoutés

- `contrat-location.pdf` (conditions générales), `fiches-arrivee/` (Morel complète, Costa incomplète), `facture-sejour-leroy.pdf` — utiles aux exercices 1 et 3.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Prépare la taxe de séjour. »
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
- À la fin d'un exercice, demandez la critique du personnage « Contrôleur de la régie / douanes »
  (sous-agent `controleur-regie`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.
