# Dossier d'exercices — Froid / climatisation / PAC (fictif)

Contenu : bons d'intervention du mois, fiches fluides (incomplètes volontairement),
contrats de maintenance, historique de dépannages sans contrat.

Exercices du tutoriel (leçon 8 — Froid / Clim / PAC) :
1. Traçabilité fluides → bons-intervention/ + cerfa-15497/
2. Relance des contrats → contrats.xlsx + bons + depannages-sans-contrat.csv
3. Devis dépannage type → bons-intervention/ comme matière

Clients et numéros fictifs.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Vérifie les fluides. »
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
- À la fin d'un exercice, demandez la critique du personnage « Inspecteur environnement (fluides frigorigènes) »
  (sous-agent `inspecteur-fluides`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. Un contrôle fluides est annoncé mardi : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `controle-mardi/` : le tableau de traçabilité complet (CERFA manquants en évidence), les re-contrôles à planifier, et les courriers de proposition de contrat aux clients en dépannage répété.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».
