# Dossier d'exercices — Solaire / EnR (fictif)

Contenu : 3 dossiers chantiers à des stades différents (suivi administratif), un export de
production annuelle à comparer à l'étude, un devis à contrôler avant envoi.

Exercices du tutoriel (leçon 8 — Solaire / EnR) :
1. Suivi administratif → chantiers/
2. Rapport de production → production.csv + etude.pdf
3. Contrôle de devis → devis-client.pdf (+ etude.pdf pour les règles)

Clients, visas et références fictifs.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Fais le point sur les chantiers. »
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
- À la fin d'un exercice, demandez la critique du personnage « Auditeur RGE / qualité »
  (sous-agent `auditeur-rge`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. Revue de chantiers lundi matin : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `revue-lundi/` : le tableau de suivi administratif trié par blocage, le rapport de production pour le client, et la liste des corrections du devis Petit avant envoi.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».
