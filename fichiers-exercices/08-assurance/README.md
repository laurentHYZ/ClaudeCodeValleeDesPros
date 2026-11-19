# Dossier d'exercices — Courtage assurance entreprises (fictif)

Contenu : 3 projets de police à mettre en concurrence (menuiserie), 5 polices en portefeuille
pour l'échéancier de renouvellement, un sinistre dégât des eaux « en vrac » à structurer.

Exercices du tutoriel (leçon 8 — Courtage assurance) :
1. Comparatif de garanties → mise-en-concurrence/
2. Échéancier des renouvellements → portefeuille-polices/
3. Dossier sinistre → sinistre-vrac/

Compagnies et clients fictifs.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Compare les polices. »
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
- À la fin d'un exercice, demandez la critique du personnage « Gérant de la menuiserie Bois & Formes »
  (sous-agent `client-menuisier`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. Le gérant de la menuiserie vient signer lundi : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `dossier-signature/` : le comparatif final avec recommandation motivée et sourcée, l'échéancier des renouvellements à 90 jours, et le dossier sinistre prêt à déclarer avec les pièces manquantes listées.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».
