# Dossier d'exercices — Nettoyage professionnel (fictif)

Société fictive : NetPro Services. Contenu : planning et pointages de mai, factures impayées,
FDS produits, cahier de liaison d'un site.

Exercices du tutoriel (leçon 8 — Nettoyage) :
1. Écarts pointage / planning → planning-mai.xlsx + pointage-mai.xlsx (+ cahier de liaison pour le contexte)
2. Relances clients → impayes.csv
3. Registre des FDS → dossier fds/

Tous les noms, sociétés et données sont fictifs.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Compare le planning et les pointages. »
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
- À la fin d'un exercice, demandez la critique du personnage « Gestionnaire de la SCI Les Arcades »
  (sous-agent `client-sci-arcades`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. Lundi matin, vous faites le point avec votre responsable d'exploitation : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `point-lundi/` : le tableau des écarts planning/pointages par site et par agent, les courriers de relance prêts à signer (gradués selon le retard), et le registre FDS avec les fiches à redemander en évidence.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».
