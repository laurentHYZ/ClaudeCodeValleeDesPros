# Dossier d'exercices — Avocat d'affaires (fictif, anonymisé)

Contenu : pièces d'un dossier de rupture de contrat de distribution (chronologie à reconstituer),
un projet de contrat de prestation à analyser clause par clause, le relevé de temps du mois.

Exercices du tutoriel (leçon 8 — Avocat d'affaires) :
1. Chronologie d'un dossier → pieces/
2. Analyse de contrat → contrat.pdf
3. Facturation au temps → temps-mai.xlsx

Toutes les parties, faits et montants sont fictifs.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Résume ce dossier. »
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
- À la fin d'un exercice, demandez la critique du personnage « Associé senior du cabinet »
  (sous-agent `associe-senior`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. L'associé veut le point complet du dossier demain matin : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `point-associe/` : la chronologie sourcée avec les trous documentaires signalés, l'analyse clause par clause du contrat, et les projets de notes d'honoraires du mois vérifiés.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».
