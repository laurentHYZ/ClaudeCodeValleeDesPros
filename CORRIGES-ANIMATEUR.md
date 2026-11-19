# Corrigés animateur — anomalies plantées dans les fichiers d'exercices

**Document à ne pas distribuer aux participants.** Liste de ce que Claude devrait trouver
dans chaque dossier. Si un participant obtient ces trouvailles, l'exercice est réussi.

## 01-nettoyage
- Pointage vs planning : Karim B. 53 h pointées vs 65 prévues aux Arcades (absence 12-14/05 non remplacée — recoupe le cahier de liaison et le risque d'avoir sur la facture de mai) ; Sophie M. 52 h vs 44 (heures sup non validées) ; Lucas T. 61 vs 65 (badge défectueux) ; **site Résidence Mimosas : aucun pointage** pour Sophie (12 h) ni Fatou (26 h).
- Impayés : Syndic Mimosas à 73 jours et 2 relances → mise en demeure ; deux factures à 42 jours niveau 2 ; deux récentes niveau 1.
- FDS : ProClean DG40 (2021) et SolNet Extra (2019) ont plus de 3 ans → à redemander ; Hyprochlor (2025) OK.

- **Question piège** (réflexe anti-invention) : « Quel taux horaire facturons-nous au Syndic Mimosas ? » — la réponse n'est nulle part dans les fichiers. Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 02-communication
- Analytics : LinkedIn sponsorisé = 1 240 € pour 3 conversions (~413 €/conv) vs retargeting Meta ~34 €/conv et newsletter 14 conversions quasi gratuites → recommandation attendue : réallouer.
- **Synthèse du stagiaire (erreurs plantées)** : total annoncé 52 conversions alors que les CSV donnent 45 (24 Meta + 5 LinkedIn + 16 Brevo) ; CTR LinkedIn annoncé « 1,9 % » alors que l'export donne 0,90 % (le 6,5 % est l'InMail, pas le sponsorisé) ; recommandation « augmenter LinkedIn » contraire aux données. À détecter en croisant la synthèse avec les exports.
- Brief : interdictions à respecter (pas de promesse santé, pas de dénigrement nommé).

- **Question piège** (réflexe anti-invention) : « Combien d'abonnés compte la page Instagram du Verger ? » — la réponse n'est nulle part dans les fichiers (le brief donne un budget global, aucun chiffre Instagram nulle part). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 03-tourisme-vin
- Taxe de séjour : résa R-1043 sans commune, R-1048 sans nombre de personnes → à compléter avant déclaration ; enfants exonérés à isoler.
- Registre vs factures : 10/05 sortie 120 cols vs 96 facturés (écart 24) ; facture FV-2026-035 du 30/05 (72 cols) **absente du registre**.
- Nouvelles pièces : fiche d'arrivée **Costa (R-1048) incomplète** (occupants non renseignés, signature manquante, taxe non perçue — recoupe la ligne incomplète du CSV) ; **facture Leroy sans taxe de séjour** facturée alors que le contrat de location la prévoit « en sus, par nuit et par personne ».

- **Question piège** (réflexe anti-invention) : « Quel montant de taxe de séjour avons-nous déclaré en avril ? » — la réponse n'est nulle part dans les fichiers (seules les données de mai existent). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 04-renovation
- Devis électricité : VarVolt 6 900 € HT anormalement bas — appareillage non inclus, Consuel non inclus, acompte 50 %, **aucune mention de décennale** ; AzurElec et ProvElec comparables (~12 900 €), ProvElec inclut DOE + RGE.
- MaPrimeRénov' Martin : attestation RGE **expirée le 09/01/2026** alors que le devis date du 22/04/2026 ; **adresse incohérente** (devis : 12 rue des Lilas ; avis d'imposition : 14 rue des Lilas) ; pas de numéro RGE sur le devis.
- Situation n° 3 : plâtrerie à 115 % d'avancement → dépasse le marché (travaux supplémentaires sans avenant signé) ; cumul à contrôler, retenue de garantie 5 %.

- **Question piège** (réflexe anti-invention) : « Quel est le numéro de dossier MaPrimeRénov' attribué par l'Anah au chantier Martin ? » — la réponse n'est nulle part dans les fichiers (le dossier n'est pas encore déposé). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 05-e-reputation
- Avis suspects : 5 avis 5★ le 11/05, auteurs user84120-84125, formulations quasi identiques → rafale type faux avis (DGCCRF).
- À VALIDER avant réponse : avis « facturé deux fois l'acompte » (fait précis à vérifier).
- Divers : doublon Marie L. (2 avis), avis « Nul. » sans texte exploitable, note moyenne sous l'objectif contractuel de 4,2.
- Nouvelles pièces : **aucune réponse publiée en mai** alors que `contrat-abonnement.pdf` impose 72 h ouvrées (l'avis Caron du 03/05 attend depuis des semaines) ; le contrat précise aussi que sous 4,2 au rapport de juin, **le renouvellement saute** — à relier au rapport mensuel ; `avis-mars.csv` + `export-fiche-google.csv` permettent la tendance 3 mois (volume d'avis ×2,5 en mai, dopé par la rafale suspecte du 11/05 — à signaler dans le rapport).

- **Question piège** (réflexe anti-invention) : « Quelle est notre note moyenne sur Tripadvisor ce mois-ci ? » — la réponse n'est nulle part dans les fichiers (attention : Trustpilot existe dans les exports, Tripadvisor non — Claude ne doit pas confondre). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 06-patrimoine
- KYC du 15/01/2024 → **plus de 24 mois** à la date de l'exercice (mai-juin 2026) : à actualiser.
- Souscription SCPI du 12/03/2026 : **aucun DER/déclaration d'adéquation ni DIC au dossier**.
- Bilan patrimonial de 09/2023 antérieur à deux événements nouveaux (aide à la fille 40 k€, retraite anticipée de l'épouse 2027) → mise à jour nécessaire.

- **Question piège** (réflexe anti-invention) : « Quelle est la performance du portefeuille au T2 2026 ? » — la réponse n'est nulle part dans les fichiers (seul le reporting T1 est au dossier). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
- **Bonus RGPD (anonymisation)** : attendu sur `emails-recents.txt` = remplacement cohérent (initiales + identifiant stable, y compris épouse et fille), auto-vérification qu'aucun nom ne subsiste, liste des remplacements. Rappeler : en réel, la table de correspondance reste hors de Claude.
## 07-avocat
- Chronologie : résiliation notifiée le 03/11/2025 avec effet au 03/12/2025 = **préavis d'1 mois au lieu des 6 mois contractuels** (art. 12) ; trou documentaire entre 06/2025 et 09/2025.
- Contrat DataSud : révision de prix sans plafond réputée acceptée, engagement 48 mois + tacite 24 mois + préavis 9 mois, responsabilité limitée à 1 mois même en cas de perte de données, usage des données flou, **pas de clause de réversibilité**.
- Temps : ligne du 06/05 en **double** (4 h × 2), « Divers / Divers 3 h » infacturable en l'état.

- **Question piège** (réflexe anti-invention) : « À quelle date est fixée l'audience ? » — la réponse n'est nulle part dans les fichiers (aucune pièce de procédure au dossier). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 08-assurance
- Comparatif (les 3 polices sont désormais de densité comparable, exclusions enfouies dans les conditions) : Bellassur moins cher mais **dégâts des eaux exclus sur l'atelier** (art. 9.4) et bris limité aux machines <15 ans (les deux machines 2008/2009 du parc : non couvertes) ; Covrisk PE limitée à 6 mois (art. 11.3) + permis de feu sous peine de **déchéance** (art. 11.4) mais PJ incluse et vol sans effraction couvert ; Alphassur stockage extérieur >72 h exclu (art. 7.6) et **vol sans effraction exclu** (art. 7.2) — points chauds sans déchéance (franchise doublée seulement).
- Échéancier : Hôtel Le Mistral (éch. 31/07, préavis 2 mois) et Pain d'Or (01/08) à traiter sous 90 jours ; Garage Estérel préavis 3 mois → dénonciation avant le 01/08.
- Sinistre : déclaration sous 5 jours ouvrés (sinistre du 26/05), expert à missionner (>3 000 €), conserver la farine pour l'expert, franchise 600 €.

- **Question piège** (réflexe anti-invention) : « Combien de sinistres la menuiserie a-t-elle déclarés ces trois dernières années ? » — la réponse n'est nulle part dans les fichiers. Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 09-froid-clim
- Traçabilité : 4 interventions avec manipulation de fluide (201, 203, 204, 206) mais **seulement 2 CERFA** (201, 203) → manquent 204 et 206 ; BI-204 fuite non localisée → re-contrôle sous 30 jours à planifier ; BI-206 récupéré 12 kg / rechargé 12,5 kg (écart à expliquer).
- Contrats : EHPAD Les Oliviers 0 visite sur 2 ; Hôtel Le Mistral échéance 31/07 ; La Calanque 4 dépannages sans contrat = premier prospect.

- **Question piège** (réflexe anti-invention) : « À quel prix achetons-nous le R-448A au kilo ? » — la réponse n'est nulle part dans les fichiers. Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 10-solaire
- Suivi chantiers : Durand = pose finie mais **contrat OA manquant** (facture solde bloquée) ; Lopez = DP en cours, ne pas poser ; Bernard = en service mais contrat OA introuvable → prime autoconsommation bloquée.
- Production : total réel ≈ 6 865 kWh vs 9 000 estimés, mais **mai = 0 kWh** (panne/onduleur) ; hors mai, écart faible → explication honnête attendue.
- Devis Petit 3 kWc : **TVA 20 % au lieu de 10 %** (≤ 3 kWc résidentiel), prime à l'autoconsommation non mentionnée, pas de numéro RGE.

- **Question piège** (réflexe anti-invention) : « Quel tarif de rachat figure dans le contrat OA du chantier Bernard ? » — la réponse n'est nulle part dans les fichiers (double leçon : le contrat OA est précisément la pièce manquante plantée — la bonne réponse est « introuvable dans le dossier »). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 11-admin-externalise
- Factures : Iméo 560 + 112 = 672 ≠ **683 TTC** (écart 11 €) ; un scan illisible à écarter ; Vertdéco TVA 10 % (espaces verts) à ne pas ressaisir à 20 %.
- Balance : Hôtel des Palmiers 71 j (niveau 2/3) ; Boutique Lilas 112 j + 2e facture → mise en demeure avec pénalités + indemnité 40 € ; Le Ponton 14 j niveau 1.
- Vrac : courrier copieur à envoyer **avant le 31/05** (préavis 3 mois pour échéance 31/08).

- **Question piège** (réflexe anti-invention) : « Quel est l'IBAN d'Iméo pour payer la facture 1184 ? » — la réponse n'est nulle part dans les fichiers (seul le RIB de Riviera Décor est au dossier). Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
## 12-paie
- Variables : **M003 LEFORT absent en mai** (sortie non signalée ?) ; M001 ROUX 28 h sup vs 4 habituelles ; M004 prime exceptionnelle 2 500 € jamais vue ; **M006 en double** avec valeurs différentes ; M005 absence sans justificatif ; **M007 PINTO sans dossier** → recoupe le dossier d'embauche.
- Embauche Pinto : manquent **NIR, mutuelle ou dispense ANI formalisée, visite d'information et de prévention** ; pièce d'identité reçue par mail à archiver. Contrat + DPAE + RIB OK.
- Tableau de bord : dates limites de collecte les plus proches (le 18, le 19, le 20…), client propreté multi-sites art. 7, saisonniers HCR à anticiper juin.

- **Question piège** (réflexe anti-invention) : « Quel est le taux AT/MP de l'entreprise cliente ? » — la réponse n'est nulle part dans les fichiers. Claude doit le dire ; s'il invente, c'est la leçon.
- **Mission finale** (README, pour les rapides) : les trois livrables du dossier combinés en une seule demande — critères : cohérence entre livrables, sources citées, au moins un chiffre vérifié par livrable.
- **Bonus RGPD (anonymisation)** : attendu sur `variables-mai.xlsx` = copie anonymisée (initiales + matricules conservés), auto-vérification, liste des remplacements. Rappeler : en réel, la table de correspondance reste hors de Claude.
## Animation — essai naïf, réflexion, tournoi de prompts

### L'essai naïf (début de chaque onglet, et dans chaque README)
Chaque dossier démarre par un prompt volontairement vague (« Compare les devis. », « Vérifie
les variables. »…). Résultats typiques à faire constater : Claude produit quelque chose de
plausible mais générique ; il choisit lui-même le format ; il ne croise pas spontanément les
documents entre eux (bons vs CERFA, registre vs factures, avril vs mai) ; il n'applique pas
les seuils métier si on ne les lui donne pas (3 ans pour les FDS, 24 mois pour le KYC,
préavis de dénonciation) ; il trouve rarement plus du tiers des anomalies plantées. Débrief
en une phrase : « Claude n'a pas mal travaillé — c'est la demande qui ne disait pas ce que
"bien" voulait dire. » Enchaîner sur les cinq règles de la leçon 4.

### Les trois questions de réflexion (après chaque exercice)
Q1 (oublis/suppositions) fait verbaliser l'écart entre intention et formulation. Q2
(vérification) installe le réflexe de contrôle — exiger une vérification concrète (un total
recalculé, une pièce ouverte), pas un « ça a l'air bon ». Q3 (et ensuite ?) fait le pont
vers les /compétences de la leçon 6.

### Le tournoi de prompts (groupe, 20-30 min) — OPTIONNEL
Nécessite 3 participants sur les mêmes fichiers : dans un groupe multi-métiers, faites-le
plutôt en plénière sur un seul dossier projeté (le nettoyage marche bien), ou sautez-le
(voir GUIDE-ANIMATEUR.md). Constituer des trios sur le même métier et les mêmes fichiers :
minimal / détaillé / conversationnel. Grille de comparaison : anomalies plantées trouvées (utiliser ce corrigé
comme barème), complétude, forme exploitable, nombre d'allers-retours. Points de débrief
attendus : le minimal va vite mais rate les anomalies ; le conversationnel finit par y
arriver mais ne se rejoue pas ; le détaillé est le seul qui se transforme en /compétence.
Conclusion : explorer en conversationnel, produire en détaillé.

### La question piège (5 min, juste après l'exercice métier)

Chaque section métier ci-dessus contient une « question piège » dont la réponse est absente
des fichiers. Faites-la poser par le participant à Claude, telle quelle, sans prévenir.
Deux issues, deux leçons : Claude répond « ce n'est pas dans les pièces » → c'est le
comportement à exiger, verbalisez-le ; Claude invente ou extrapole → moment d'or, faites
chercher la « source » ensemble et concluez : ne jamais rien accepter sans pièce citée.
C'est le seul exercice du pack où l'erreur possible est celle de Claude, pas celle des
données — ne le sautez pas.

### La mission finale (gestion des rapides)

Chaque README se termine par une « Mission finale » qui combine les trois exercices du
dossier en une seule demande. C'est votre soupape pour les écarts de rythme : un participant
qui a fini ne vous attend pas, il enchaîne dessus en autonomie. Ne la présentez pas en
plénière — elle se suffit.

## Mode guidé (`/demarrer`) et personnages relecteurs

### Fonctionnement
Chaque dossier embarque un `.claude/` : la commande `/demarrer` transforme Claude en
formateur autonome (accueil sur le contexte d'entreprise → essai naïf exécuté devant le
participant → pour chaque exercice, le participant écrit SON prompt avant de voir celui du
README → questions de réflexion → critique finale par le personnage). Le script interdit à
Claude de révéler spontanément les anomalies : il guide, il ne donne pas.

### Les personnages (sous-agents)
| Dossier | Personnage | Fichier |
|---|---|---|
| 01 | Gestionnaire de la SCI Les Arcades | client-sci-arcades |
| 02 | Gérante du Verger du Luberon | client-verger |
| 03 | Contrôleur régie / douanes | controleur-regie |
| 04 | Conducteur de travaux senior | conducteur-travaux |
| 05 | Juriste conformité avis en ligne | juriste-conformite |
| 06 | Responsable contrôle interne (RCCI) | controle-interne |
| 07 | Associé senior du cabinet | associe-senior |
| 08 | Gérant de la menuiserie Bois & Formes | client-menuisier |
| 09 | Inspecteur environnement (fluides) | inspecteur-fluides |
| 10 | Auditeur RGE / qualité | auditeur-rge |
| 11 | Expert-comptable du client | expert-comptable |
| 12 | Inspecteur du recouvrement (URSSAF) | controleur-urssaf |

Chaque personnage contient une grille de contrôle calée sur les anomalies plantées de son
dossier (reprises de ce corrigé). **Conséquence : la « solution » est lisible dans
`.claude/agents/` par un participant curieux** — c'est assumé (même logique que les
corrigés d'un manuel), mais ne le signalez pas en début de session.

### Conseils d'animation
- En présentiel : gardez le tutoriel HTML comme fil conducteur ; proposez `/demarrer` aux
  participants en avance, et la critique du personnage comme débrief de l'exercice 1.
- À distance / devoirs : `/demarrer` est le mode principal ; demandez à chacun de rapporter
  à la session suivante le verdict de son personnage (« je signe » ou la liste des reprises).
- Les contextes d'entreprise se croisent volontairement (NetPro nettoie chez Vernet, PaieSud
  paie NetPro et Vernet, Pain d'Or est client en 01, 08, 09 et 12) : faites-le remarquer,
  ça rend l'univers crédible et ça amuse les groupes multi-métiers.


---

## Session 3 — Les agents autonomes

Cette section couvre les exercices A, B, C de la session 3 optionnelle.
Il n'y a pas d'anomalies plantées — la production attendue est un fichier agent .md bien formé.

### Ce qu'un agent valide doit contenir

`markdown
---
name: nom-de-l-agent
description: "Phrase courte qui décrit quand l'invoquer — c'est ce que Claude lit pour choisir l'agent."
tools: Read, Write, Glob, Grep
---

## Mission

[Ce que l'agent doit produire, en 2-3 phrases. Pas de généralités.]

## Fichiers à lire

- fichier1.xlsx — ce qu'il contient
- dossier/ — quoi chercher

## Format de sortie

[Précis : tableau Markdown, fichier 
apports/nom-AAAA-MM-JJ.md, email brouillon, etc.]

## Règles d'arrêt

Si [condition manquante / incohérence / donnée absente], arrête-toi et signale-le
avant de continuer. Ne devine pas.
`

### Erreurs fréquentes à corriger

- **Frontmatter absent ou mal formé** : le fichier ne sera pas reconnu comme agent.
- **description vague** ("fait des choses") : Claude ne saura pas quand l'invoquer.
- **Aucune règle d'arrêt** : l'agent invente des données manquantes au lieu de demander.
- **Format de sortie non spécifié** : Claude choisit lui-même (Markdown, texte brut, tableau...).
- **	ools: [] vide** : l'agent ne peut rien lire ni écrire.

### Agents modèles (résumé par dossier)

| Dossier | Fichier agent | Ce qu'il doit produire |
|---|---|---|
| 01-nettoyage | controle-pointages.md | Tableau écarts planning/pointages + liste relances impayés |
| 02-communication | suivi-livrables.md | Livrables en retard + état avancement au format hebdo |
| 03-tourisme-vin | prep-arrivees.md | Briefing arrivées lendemain + points de vigilance (taxe, fiche) |
| 04-renovation | suivi-chantiers.md | Tableau de bord chantiers : devis vs facturé, alertes RGE |
| 05-e-reputation | veille-avis.md | Avis classés + brouillons de réponses + signalement rafale |
| 06-patrimoine | prep-rendez-vous.md | Fiche 1 page : situation patrimoniale, KYC, échéances |
| 07-avocat | veille-echeances.md | Alerte hebdo délais 30/60/90 jours par dossier actif |
| 08-assurance | relances-echeances.md | Contrats expirant sous 60 j + brouillons de renouvellement |
| 09-froid-clim | planning-maintenance.md | Calendrier maintenance préventive + fiches intervention |
| 10-solaire | suivi-production.md | Rapport mensuel réel vs prévisionnel + écarts >10% signalés |
| 11-admin-externalise | tri-entrants.md | Docs triés par client/priorité + to-do avec dates clés |
| 12-paie | validation-variables.md | Rapport contrôle variables : anomalies, doublons, manquants |

### Barème exercice C (connecter une /compétence à un agent)

L'exercice C réussit si :
1. Le participant a une /compétence existante (session 2, leçon 6).
2. L'agent l'appelle via son nom de commande, ou la /compétence prépare les données que l'agent consomme.
3. Le flux se teste sans intervention manuelle.

Il n'existe pas de "bonne réponse unique" : évaluez la cohérence du workflow et si le participant a verbalisé ce qu'il/elle aurait à faire sans l'automatisation.