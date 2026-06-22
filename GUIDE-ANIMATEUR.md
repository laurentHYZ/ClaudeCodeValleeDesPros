# Guide animateur — formation Claude Code pour dirigeants de PME

**Ce document est votre seul point d'entrée.** Tout le reste du pack est du matériel que vous
piochez ou ignorez. Il remplace `teaching-plan.md` (conservé pour archive).

## La règle d'or

**Prérequis non négociable : faites le tutoriel vous-même une fois, en entier, sur un
dossier d'exercices — avant votre première session.** Deux heures qui vous éviteront
toutes les surprises en salle.

Une session réussie = **leçons 1 à 5 du tutoriel + UN exercice métier par participant**.
Tout le reste est du bonus. Si vous ne deviez retenir qu'une phrase de ce guide : vous
n'avez pas à présenter les couches du pack — elles travaillent pour vous en silence.

## Le pack en une carte

| Élément | Fichier(s) | Statut | Votre effort |
|---|---|---|---|
| Tutoriel interactif (9 leçons) | `claude-code-tutorial.html` | **CŒUR** | C'est votre fil conducteur, projetez-le |
| Dossiers de fichiers fictifs (12 métiers) | `fichiers-exercices/` + zip | **CŒUR** | Les déposer dans un drive avant la session |
| Corrigés (anomalies plantées) | `CORRIGES-ANIMATEUR.md` | **CŒUR** | Le relire pour LES métiers présents, pas les 12 |
| Essai naïf → prompt complet | intégré (tutoriel + README de chaque dossier) | **CŒUR** | Rien — c'est dans le déroulé |
| Questions de réflexion (×3) | intégré (fin de leçon 8) | **CŒUR** | Les poser à l'oral après l'exercice |
| Moment ROI « calculez votre gain » | leçon 1 du tutoriel | **CŒUR** | 5 min d'animation en ouverture |
| Compétences : créer, lire, modifier la sienne (6a-6b) | leçon 6 du tutoriel | **CŒUR** | 15 min, idéalement juste après l'exercice métier |
| Compétences en ligne / marketplaces (6c) | leçon 6 du tutoriel | **OPTIONNEL** | Démo seulement, TOUJOURS avec la liste de vérification sécurité |
| Critique par le personnage métier | `.claude/agents/` de chaque dossier | **RECOMMANDÉ** | Une seule phrase à connaître : « demandez la critique du personnage » |
| Projet final (outil HTML) | leçon 9 | **RECOMMANDÉ** | Une démo de 10 min par vous suffit |
| Mode guidé `/demarrer` | `.claude/commands/` de chaque dossier | **OPTIONNEL** | À annoncer comme devoir, pas à dérouler en salle |
| Tournoi de prompts | fin de leçon 8 | **OPTIONNEL** | Seulement si ≥ 3 participants du même métier — sinon en plénière sur un seul dossier, ou pas du tout |
| Contexte d'entreprise fictive | `CONTEXTE-ENTREPRISE.md` ×12 | **AMBIANT** | Zéro — ça nourrit Claude et les personnages, pas votre discours |
| Docs Claude Code de référence | racine + `claude-code-docs/` | **ARCHIVE** | Pour vous, jamais pour les participants |
| Session 2 — sur la route (mobile) | section `#s2` du tutoriel | **OPTIONNEL · SESSION SÉPARÉE** | Mini-session (~1h), à proposer après la Session 1, jamais à la place. Prérequis : appairage mobile testé en amont — voir plus bas |

## Verdict honnête sur la complexité

Le pack a effectivement beaucoup de couches — mais elles sont **empilées, pas enchevêtrées** :
chaque couche fonctionne sans les autres, et trois d'entre elles (contextes, personnages,
mode guidé) s'exécutent toutes seules dans Claude sans que vous ayez à les expliquer.
Votre charge réelle d'animation se résume à : le tutoriel, les dossiers, les corrigés.

Trois points de vigilance assumés :

1. **Le tournoi de prompts est l'élément le plus fragile.** Il suppose 3 participants sur
   les mêmes fichiers — improbable dans un groupe mélangeant 12 métiers. Faites-le en
   plénière sur un seul dossier projeté (le nettoyage marche bien), ou supprimez-le sans
   remords : l'essai naïf enseigne déjà 80 % de la même leçon.
2. **Les questions de réflexion existent en trois exemplaires** (tutoriel, README, script
   `/demarrer`). C'est voulu — chaque support se consomme seul — mais vous, n'en présentez
   qu'une : celle du tutoriel. Ignorez les doublons.
3. **Les grilles des personnages contiennent les réponses** (lisibles dans `.claude/agents/`
   par un curieux). Assumé, comme un manuel avec corrigés — ne le signalez pas en début de
   session.

Rien à supprimer d'urgence. Si vous voulez alléger quand même, coupez dans cet ordre :
tournoi → leçon 6c (marketplaces) → mode guidé (gardez-le pour les sessions à distance)
→ tâches planifiées (démo de 5 min suffit). Ne coupez pas la 6a : transformer son prompt
métier en /compétence est le déclic qui fait durer la formation.

## Déroulé type — demi-journée (3 h 50)

| Quand | Quoi | Support |
|---|---|---|
| 0:00 (15 min) | Accueil + « calculez votre gain » (chacun chiffre SA tâche) | Leçon 1 |
| 0:15 (30 min) | Démo : l'agent qui travaille sur un dossier + installation vérifiée (pré-travail !) | Leçons 1-2 |
| 0:45 (30 min) | Première session : les 3 exercices universels, faits par les participants | Leçon 3 |
| 1:15 (25 min) | Les cinq règles + quiz | Leçon 4 |
| 1:40 (10 min) | Pause | |
| 1:50 (20 min) | CLAUDE.md : chacun en crée un (avec la mention IA) | Leçon 5 |
| 2:10 (50 min) | **Exercice métier** : essai naïf → prompt complet → 3 questions de réflexion → transformer son prompt en /compétence et lire le SKILL.md créé (leçon 6a) | Leçon 8 + leçon 6a |
| 3:00 (10 min) | Débrief par le personnage : « demandez sa critique au [personnage de votre dossier] » | `.claude/agents/` |
| 3:10 (20 min) | **Atelier connecteurs (hands-on)** : exercice A — un seul outil (interroger sa messagerie) → exercice B — deux outils dans une demande (messagerie → Drive → fichier de suivi). Chacun sur SA connexion ; ceux qui n'ont pas connecté font la version « par export ». | Leçon 7 |
| 3:30 (10 min) | Garde-fous (modes de permission, vérification, RGPD) — puis, si le groupe est mûr, 2 min sur la 6c avec la liste sécurité, OU démo outil HTML | Leçons 7 / 9 / 6c |
| 3:40 (10 min) | Clôture : devoirs = `/demarrer` chez soi + refaire sur ses propres fichiers | README des dossiers |

**L'atelier connecteurs en bref.** C'est le créneau pratique que les versions précédentes
n'avaient pas — avant, les connecteurs n'étaient qu'une démo. Objectif : que chacun lance
au moins l'exercice A sur sa propre messagerie, et idéalement l'exercice B (deux outils).
La réussite tient à UNE chose : les connexions faites **avant** la session (point 4 de
l'e-mail de pré-travail). Faites un tour de salle en début de créneau — « qui voit bien
Gmail/Drive dans le bouton + ? » — et basculez les non-connectés sur la version export
plutôt que de déboguer des autorisations en direct (règle des 3 minutes).

**Pour rester en 3 h 30 si besoin.** L'atelier ajoute 20 min. Compensez en raccourcissant
l'exercice métier de 10 min (un seul passage essai naïf → prompt complet, sans second
exercice du dossier) et le débrief personnage de 5 min, ou en coupant la démo 6c/HTML du
créneau garde-fous. Ne sacrifiez pas l'atelier lui-même : c'est désormais le seul moment
où les participants *utilisent* un connecteur de leurs mains.

**Variante express (90 min)** : 0:00 gain (10') → démo dossier + 1 exercice universel (25')
→ cinq règles (15') → exercice métier essai naïf vs prompt complet (30') → garde-fous et
devoirs (10'). On saute : CLAUDE.md en pratique (montrez-le seulement), personnage, leçons 6-7.

## Check-list avant session

1. E-mail de pré-travail envoyé (abonnement actif, app installée, Git si Windows) — leçon 2.
   Y inclure : **connecter une messagerie ET un espace de fichiers avant la session**
   (Gmail ou Outlook + Google Drive ou OneDrive ; bouton + → connecteurs). L'atelier
   connecteurs (créneau 3:10) a besoin des **deux** : l'exercice A interroge la messagerie,
   l'exercice B enchaîne messagerie → Drive. Connexions faites à la maison = temps en salle
   consacré à utiliser, pas à s'authentifier. Faites-le vous-même une fois pour pouvoir
   guider (l'écran d'autorisation diffère un peu entre Google et Microsoft).
2. `fichiers-exercices/` déposé dans le drive ; chaque participant sait quel dossier prendre.
3. Vous avez relu dans `CORRIGES-ANIMATEUR.md` les sections des métiers présents.
4. Vous avez testé `/demarrer` et la critique du personnage sur UN dossier (10 min).
5. Tutoriel ouvert dans un navigateur, prêt à projeter.
6. **Cahier d'invites** créé (doc partagé Google/Word vierge, lien affiché en début de session) :
   chaque participant y colle ses meilleurs prompts au fil de la journée — il repart avec
   le butin collectif du groupe.

## E-mail de pré-travail (copier-coller)

> Objet : Avant notre formation Claude Code — 15 minutes de préparation
>
> Bonjour,
>
> Pour que la session soit 100 % pratique, merci de faire ces 4 choses avant le jour J :
>
> 1. Vérifiez que votre abonnement Claude est actif (Pro minimum) : claude.ai/settings
> 2. Installez l'application Claude pour ordinateur : claude.ai/download — connectez-vous.
> 3. Windows uniquement : installez Git pour Windows (git-scm.com, options par défaut).
> 4. Connectez DEUX outils dans l'application — c'est ce qui rend l'atelier de l'après-midi
>    possible. Dans l'app, cliquez le bouton **+** à côté de la zone de saisie, puis
>    « Connecteurs / Ajouter une connexion », et autorisez :
>    a) **votre messagerie** — Gmail OU Outlook ;
>    b) **votre espace de fichiers** — Google Drive OU OneDrive.
>    Pour chacun : choisissez le connecteur, ouvrez votre compte, acceptez l'accès demandé.
>    Comptez 2 minutes par outil, une seule fois. Si une connexion vous gêne (boîte
>    professionnelle sensible), utilisez un compte personnel ou de test — on verra en salle
>    comment travailler par export quand un outil n'a pas de connecteur.
>
> Apportez votre ordinateur portable et son chargeur. Rien d'autre à préparer : les
> fichiers d'exercices vous seront fournis.
>
> À très vite, [signature]

## Session 2 — Claude Code sur la route (mobile)

Session courte et **séparée** (~1h), à proposer après la Session 1 — jamais en remplacement
ni en rallonge le même jour. Modèle mental à donner d'emblée : « Session 1 = vous discutez
avec Claude assis à votre poste ; Session 2 = vous lui confiez une tâche depuis votre
téléphone et vous vérifiez le résultat en revenant. » Contenu : section `#s2` du tutoriel.

**Rappel à faire passer** : la fonction mobile (« Dispatch ») est un aperçu de recherche —
elle peut changer ou être indisponible. Dites-le aux participants avant de commencer, ça
désamorce la frustration si ça coince.

### Pré-travail spécifique (en plus de celui de la Session 1)
- Installer l'application Claude sur le téléphone, se connecter avec le **même compte**
  que sur l'ordinateur.
- Appairer le téléphone avec l'ordinateur qui fera tourner Claude Code (app mobile,
  onglet Code → suivre l'invite d'appairage).
- **Tester l'appairage avant le jour J** : envoyer une tâche simple depuis le téléphone
  et vérifier qu'elle arrive sur l'ordinateur. C'est le point de friction principal —
  à faire la veille chez soi, pas en salle.

Ajout à l'e-mail de pré-travail (à coller après le point 4, uniquement si la Session 2
est prévue) :

> 5. Installez l'application Claude sur votre téléphone (mêmes identifiants), puis
>    appairez-la avec votre ordinateur (onglet Code → bouton d'appairage). Envoyez-vous
>    une tâche test (« dis-moi bonjour et donne l'heure ») pour vérifier que ça fonctionne
>    avant le jour J — c'est un aperçu de recherche, mieux vaut le découvrir chez soi.

### Si l'appairage échoue le jour J (mode de repli)
Si une personne n'arrive pas à appairer en séance, ne perdez pas de temps à déboguer
(même règle des 3 minutes) : mettez-la en binôme avec un voisin dont l'appairage
fonctionne — elle dicte, le voisin lance depuis son téléphone, ou elle observe sur son
écran. Si **plus d'un tiers du groupe** est bloqué, basculez toute la session en binômes
dès le départ et annoncez-le sans gêne (« aperçu de recherche, ça arrive ») : un téléphone
qui fonctionne par binôme suffit pour faire vivre les deux exercices.

## Attention au partage

Ne déposez dans le drive participants QUE le dossier `fichiers-exercices/` (ou son zip).
`CORRIGES-ANIMATEUR.md`, ce guide et le reste du dossier de travail restent chez vous.

## Dépannage en direct

- **Abonnement inactif** (l'onglet Code propose de payer) : ne bloquez pas le groupe.
  Mettez la personne en binôme avec son voisin pour la session, elle régularise à la pause
  (claude.ai/settings). C'est LE cas que l'e-mail de pré-travail existe pour éviter.
- **Popup de permission qui déroute** (« Claude veut exécuter… ») : phrase toute faite :
  « C'est la ceinture de sécurité — Claude demande avant d'agir. Lisez, puis Autoriser. »
  Si quelqu'un a tout refusé et que Claude semble coincé : il suffit de relancer la demande.
- **Wifi qui tombe** : les fichiers sont locaux, rien n'est perdu ; Claude a juste besoin
  du réseau pour réfléchir. Faites passer le débrief / les questions de réflexion en
  attendant, ou basculez sur partage de connexion téléphone. Reprenez la session telle
  quelle : l'historique est conservé.
- **Limite d'utilisation atteinte en plein exercice** (message « usage limit ») : ça arrive
  sur Pro en usage intensif. Le message indique l'heure de réinitialisation. Solutions en
  salle : passer sur un modèle plus léger (menu modèle), travailler en binôme, ou avancer
  les parties sans Claude (réflexion, tournoi, mémo). Prévention : évitez de faire lancer
  les gros exercices deux fois pour le plaisir.
- **« Je ne vois pas /demarrer »** = mauvais niveau de dossier ouvert, presque à coup sûr.
  La commande vit dans chaque dossier métier : il faut ouvrir `12-paie/` (par exemple),
  pas le dossier parent `fichiers-exercices/`. Refaire « Sélectionner un dossier » au bon
  niveau. (Si le parent est ouvert, un /demarrer « panneau indicateur » le dit aussi.)
- **Règle générale** : ne déboguez jamais plus de 3 minutes devant le groupe — binôme,
  pause, ou « on le règle ensemble à la pause », et la session continue.
- **(Session 2) Appairage mobile qui échoue**
- **(Session 3) Agent qui ne lit pas le bon dossier** : vérifiez que le dossier métier est ouvert au bon niveau dans Claude Code (même règle que pour /demarrer). Faites relancer après correction.
- **(Session 3) Claude demande confirmation à chaque étape** : normal sur les premières exécutions en mode non-autonome — dites « Continue sans me demander » ou ajoutez « sans confirmation » dans le prompt de lancement.
 : aperçu de recherche, ça arrive — pas une
  erreur du participant. Binôme avec un voisin appairé (voir section Session 2 pour le
  mode de repli si une partie significative du groupe est touchée).

## Ce que vous dites (et ne dites pas)

- Dites : « chaque dossier contient une entreprise fictive avec des erreurs cachées —
  votre travail est de les faire trouver par Claude. »
- Dites : « à la maison, tapez /demarrer : Claude rejouera la formation avec vous. »
- Ne dites pas : « sous-agent », « MCP », « système de fichiers .claude » — montrez les
  effets, jamais la tuyauterie.

## Session 3 — Notes animateur

**Prérequis** : Session 1 obligatoire. Session 2 facultative mais conseillée si le groupe a déjà l'habitude de déléguer.

**Durée type** : 2 h (1 h 30 express).

| Quand | Quoi | Support |
|---|---|---|
| 0:00 (15 min) | Intro : qu'est-ce qu'un agent, en quoi ça diffère de ce qu'ils font déjà ? | Tableau comparatif leçon s3 |
| 0:15 (30 min) | Exercice A : créer un agent dans .claude/agents/ + le lire ligne à ligne | Leçon s3 |
| 0:45 (25 min) | Exercice B : lancer l'agent, vérifier un résultat dans le fichier source | Leçon s3 |
| 1:10 (20 min) | Exercice C : relier /compétence et agent | Leçon s3 |
| 1:30 (15 min) | Table des agents métiers : chacun identifie son premier agent réel | Leçon s3 |
| 1:45 (15 min) | Multi-agent (démo) + garde-fous + devoirs | Leçon s3 |

**Variante express (90 min)** : intro (10') → exercice A (25') → exercice B (20') → table métiers (20') → devoirs (15'). On saute exercice C et la démo multi-agent.

**Ce que vous dites**
- « Un agent, c'est un collaborateur textuel à qui vous donnez un mode d'emploi une fois — il s'en souvient à chaque exécution. »
- « La règle ne change pas : l'agent prépare, vous validez. Ne lui donnez jamais les droits d'envoyer des e-mails ou de modifier des données irréversibles sans vous demander. »
- « Vous avez déjà utilisé un agent sans le savoir — le personnage métier de la Session 1 était un agent. »

**Ce que vous ne dites pas** : « sous-agent », « orchestrateur », « MCP », « architecture multi-agent » — montrez les effets, jamais la tuyauterie.
