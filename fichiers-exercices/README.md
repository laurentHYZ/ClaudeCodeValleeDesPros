# Fichiers d'exercices — Formation Claude Code (12 métiers)

Un dossier par métier, aligné sur les exercices de la leçon 8 du tutoriel
(`claude-code-tutorial.html`). Chaque dossier contient un README listant ses fichiers
et les exercices associés.

## Utilisation

1. Déposez ce dossier dans un drive partagé (Google Drive, OneDrive, Dropbox).
2. Chaque participant télécharge **uniquement le dossier de son métier** sur son ordinateur
   (par exemple sur le Bureau).
3. Dans l'application Claude, onglet Code → Sélectionner un dossier → le dossier téléchargé.
4. Suivre les exercices du tutoriel — ou taper `/demarrer` pour le **mode guidé** :
   Claude devient le formateur et déroule les exercices pas à pas, en français.

## Mode guidé et personnages relecteurs

Chaque dossier métier contient :

- `CONTEXTE-ENTREPRISE.md` — la société fictive du dossier (certaines se croisent d'un
  dossier à l'autre : NetPro Services, Pain d'Or, Cabinet Vernet, Hôtel Le Mistral…).
- `.claude/commands/demarrer.md` — la commande `/demarrer` : formation guidée autonome
  (essai naïf → exercices avec prompt écrit par le participant d'abord → questions de
  réflexion → critique finale).
- `.claude/agents/<personnage>.md` — un relecteur métier (gestionnaire de SCI, associé
  senior, inspecteur fluides, contrôleur URSSAF…) qui critique les productions du
  participant en s'appuyant sur les anomalies plantées.

En présentiel, le mode guidé sert aux participants qui avancent plus vite ; à distance,
il remplace le formateur pour les devoirs entre deux sessions.

## Important

- Toutes les données sont **fictives** : sociétés, personnes, numéros, IBAN, références.
- Les dossiers contiennent des **anomalies plantées volontairement** (écarts, pièces
  manquantes, totaux faux, doublons) pour que les exercices produisent de vraies trouvailles.
  Le détail est dans `CORRIGES-ANIMATEUR.md` — **à ne pas distribuer aux participants**.
- Conseillez aux participants de refaire ensuite les exercices sur des copies de leurs
  propres fichiers : c'est là que la valeur apparaît.

## Dossiers

| Dossier | Métier |
|---|---|
| 01-nettoyage | Nettoyage professionnel |
| 02-communication | Communication BtoB |
| 03-tourisme-vin | Tourisme / camping / viticulture |
| 04-renovation | Rénovation habitat |
| 05-e-reputation | E-réputation / avis clients |
| 06-patrimoine | Gestion de patrimoine |
| 07-avocat | Avocat d'affaires |
| 08-assurance | Courtage assurance entreprises |
| 09-froid-clim | Froid / climatisation / PAC |
| 10-solaire | Solaire / EnR |
| 11-admin-externalise | Services administratifs externalisés |
| 12-paie | Externalisation paie |


## Session 3 — Les agents autonomes (optionnelle)

La session 3 est indépendante des sessions 1 et 2. Elle introduit les **agents Claude** :
des instructions permanentes enregistrées dans .claude/agents/ qui permettent à Claude
d'exécuter une tâche récurrente de façon autonome, sans demande manuelle à chaque fois.

Chaque dossier métier contient un agent pré-rempli (dans .claude/agents/) qui sert de
modèle de départ pour les exercices A, B et C de la session 3 :

| Dossier | Agent modèle | Mission |
|---|---|---|
| 01-nettoyage | controle-pointages | Écarts planning/pointages, relances impayés |
| 02-communication | suivi-livrables | Livrables en retard, état avancement hebdo |
| 03-tourisme-vin | prep-arrivees | Arrivées lendemain, points de vigilance |
| 04-renovation | suivi-chantiers | Devis vs factures, tableau de bord chantier |
| 05-e-reputation | veille-avis | Classe avis, propose réponses, signale crises |
| 06-patrimoine | prep-rendez-vous | Fiche synthèse avant RDV client |
| 07-avocat | veille-echeances | Délais légaux 30/60 jours, alerte hebdo |
| 08-assurance | relances-echeances | Contrats expirant 60 j, brouillons renouvellement |
| 09-froid-clim | planning-maintenance | Dates maintenance préventive, fiches intervention |
| 10-solaire | suivi-production | Réel vs prévisionnel, écarts >10%, rapport mensuel |
| 11-admin-externalise | tri-entrants | Tri docs par client/priorité, dates clés, to-do |
| 12-paie | validation-variables | Variables reçues, anomalies, rapport contrôle |

Les participants testent l'agent avec /agent:nom-de-l-agent puis le personnalisent
pour correspondre à leur propre activité (exercices A, B, C du tutoriel — session 3).