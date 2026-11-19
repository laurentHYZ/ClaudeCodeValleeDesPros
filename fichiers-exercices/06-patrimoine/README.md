# Dossier d'exercices — Gestion de patrimoine (fictif, anonymisé)

Dossier du « Client A » : bilan 2023, KYC, lettre de mission, reporting T1 2026, bulletin SCPI,
échanges récents. Le dossier comporte volontairement des pièces périmées ou manquantes.

Exercices du tutoriel (leçon 8 — Patrimoine) :
1. Préparer un RDV → tout le dossier
2. Contrôle de complétude réglementaire → tout le dossier
3. Synthèse trimestrielle → reporting-T1-2026.pdf

Données 100 % fictives. Ne jamais utiliser de vraies données clients en formation.

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Prépare mon RDV client. »
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
- À la fin d'un exercice, demandez la critique du personnage « Responsable contrôle interne / conformité »
  (sous-agent `controle-interne`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. RDV avec le Client A jeudi : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `dossier-rdv/` : la fiche de RDV, le tableau conforme/manquant/périmé des pièces réglementaires, la synthèse T1 et la liste des questions à poser au client.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».

## Bonus RGPD — anonymiser avant de travailler

Réflexe à prendre avant tout fichier nominatif réel. Essayez ici sur `emails-recents.txt (dossier-client-A/)` :
« Crée une copie anonymisée de ce fichier : remplace chaque nom par des initiales et un
identifiant stable, puis vérifie qu'aucun nom complet ne subsiste et liste ce que tu as
remplacé. » En formation les données sont fictives ; en réel, ce réflexe est la condition
d'usage (et gardez la table de correspondance hors de Claude).
