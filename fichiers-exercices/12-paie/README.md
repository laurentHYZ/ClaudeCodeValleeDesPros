# Dossier d'exercices — Externalisation paie (fictif)

Cabinet de paie fictif. Contenu : variables d'avril et mai (avec anomalies à détecter AVANT
saisie), un dossier d'embauche incomplet, le portefeuille clients pour le tableau de bord.

Exercices du tutoriel (leçon 8 — Paie) :
1. Contrôle des variables → variables-avril.xlsx + variables-mai.xlsx
2. Check-list d'embauche → dossier-embauche-pinto/
3. Tableau de bord des échéances → portefeuille.xlsx

ATTENTION : toutes les personnes et données sont fictives. En réel, jamais de données
de paie nominatives hors cadre validé (RGPD).

## D'abord, l'essai naïf

Avant le premier exercice, lancez tel quel : « Vérifie les variables. »
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
- À la fin d'un exercice, demandez la critique du personnage « Inspecteur du recouvrement (type URSSAF) »
  (sous-agent `controleur-urssaf`) : il relit votre production comme dans la vraie vie.
- Le décor est posé dans `CONTEXTE-ENTREPRISE.md`.

## Mission finale (si vous avez fini en avance)

Il est vendredi 17 h 30. Veille de saisie des paies : tout doit être prêt. En **une seule demande** à Claude,
faites produire dans un dossier `avant-saisie/` : le tableau d'anomalies des variables avec une question client par ligne, l'e-mail des pièces manquantes du dossier Pinto, et le tableau de bord des échéances trié par urgence.
Critère de réussite : les trois livrables sont cohérents entre eux, chaque affirmation cite sa
source, et vous avez vérifié au moins un chiffre de chaque livrable avant de « l'envoyer ».

## Bonus RGPD — anonymiser avant de travailler

Réflexe à prendre avant tout fichier nominatif réel. Essayez ici sur `variables-mai.xlsx` :
« Crée une copie anonymisée de ce fichier : remplace chaque nom par des initiales et un
identifiant stable, puis vérifie qu'aucun nom complet ne subsiste et liste ce que tu as
remplacé. » En formation les données sont fictives ; en réel, ce réflexe est la condition
d'usage (et gardez la table de correspondance hors de Claude).
