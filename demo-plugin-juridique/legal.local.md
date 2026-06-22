# Playbook de revue de contrats — NETPRO SERVICES SAS (côté CLIENT / acheteur)

> Document fictif à usage pédagogique. Positions de négociation de NetPro Services
> lorsqu'elle **achète** un service (SaaS, prestation, licence). C'est ce fichier que la
> skill `review-contract` charge automatiquement pour cadrer ses drapeaux VERT / JAUNE / ROUGE.
>
> Profil : PME française de 35 salariés, services aux entreprises. Achète des outils
> logiciels pour son usage interne. Pas de juriste interne à plein temps — la Présidente
> arbitre, un avocat conseil est saisi pour les points ROUGE.

## Signataires et seuils d'escalade

- Jusqu'à 25 000 € HT / an et aucun drapeau ROUGE : la Présidente peut signer.
- Au-delà, ou dès qu'un drapeau ROUGE est présent : revue par l'avocat conseil obligatoire avant signature.

## Positions standard par clause

### Responsabilité (limitation)
- **Standard** : plafond ≥ 12 mois de redevances, **réciproque**. Exclusion des dommages indirects réciproque.
- **Acceptable (à négocier)** : plafond entre 6 et 12 mois.
- **Escalade (ROUGE)** : plafond < 6 mois ; plafond non réciproque ; aucune exception au plafond pour les manquements graves (confidentialité, données personnelles, atteinte aux droits des tiers).

### Indemnisation
- **Standard** : **réciproque**. Le prestataire indemnise NetPro en cas d'action d'un tiers pour contrefaçon (PI) et en cas de violation de données imputable au prestataire.
- **Acceptable** : indemnisation plafonnée au plafond de responsabilité global.
- **Escalade (ROUGE)** : indemnisation **unilatérale** à la charge de NetPro ; indemnisation « sans plafond » à la charge de NetPro ; absence d'indemnisation contrefaçon par le prestataire.

### Propriété intellectuelle
- **Standard** : chaque partie conserve sa PI préexistante. NetPro reste propriétaire de **ses données** et de ses paramétrages métier.
- **Escalade (ROUGE)** : cession au prestataire des éléments **préexistants** de NetPro ; licence « feedback » perpétuelle et irrévocable ; cession de configurations/développements payés par NetPro.

### Données personnelles (RGPD)
- **Standard** : **accord de traitement (DPA / art. 28 RGPD) obligatoire** dès qu'il y a des données personnelles. Hébergement dans l'UE, ou transfert hors UE encadré par des **clauses contractuelles types (CCT)**. Notification de violation **sous 72 h**. Sous-traitants ultérieurs : information préalable et **droit d'opposition**.
- **Escalade (ROUGE)** : absence de DPA alors que des données personnelles sont traitées ; hébergement/transfert hors UE sans CCT ni garanties ; délai de notification de violation > 72 h ; autorisation générale des sous-traitants sans information.

### Confidentialité
- **Standard** : réciproque, durée 2 à 3 ans après le terme, exclusions usuelles (domaine public, etc.).
- **Acceptable** : 1 à 2 ans.

### Garanties
- **Standard** : garantie de conformité du service à sa documentation et aux niveaux de service.
- **Escalade (ROUGE)** : service fourni « en l'état » avec exclusion **totale** de garantie.

### Durée et résiliation
- **Standard** : durée initiale ≤ 12 mois ; résiliation pour convenance **réciproque** avec préavis de 60 à 90 jours ; tacite reconduction avec préavis de dénonciation ≤ 60 jours.
- **Acceptable** : durée initiale jusqu'à 24 mois si résiliation pour convenance possible.
- **Escalade (ROUGE)** : engagement ferme de 36 mois sans sortie ; droit de résiliation **asymétrique** (le prestataire peut sortir, pas NetPro) ; reconduction tacite avec préavis > 60 jours.

### Droit applicable et juridiction
- **Standard** : **droit français**, tribunal de commerce de Lyon.
- **Acceptable (à négocier)** : droit français, autre tribunal français.
- **Escalade (ROUGE)** : droit étranger et/ou juridiction étrangère.

### Conditions financières
- **Standard** : paiement à 30–45 jours ; révision tarifaire annuelle plafonnée à un indice public ou à 5 % / an ; pas de suspension de service sans mise en demeure préalable.
- **Escalade (JAUNE/ROUGE)** : pénalités > 3× taux légal ; révision > 5 % / an unilatérale ; suspension immédiate sans préavis ; frais de mise en service non remboursables élevés.

### Cession
- **Standard** : cession soumise à accord de l'autre partie, avec exception pour les opérations intra-groupe ; clause **réciproque**.
- **Escalade (JAUNE)** : cession libre par le prestataire (y compris changement de contrôle) sans accord de NetPro, alors que NetPro ne peut pas céder.

### Assurances
- **Standard** : prestataire justifiant d'une RC professionnelle ≥ 1 000 000 € ; attestation annuelle.

### Réversibilité (SaaS)
- **Standard** : export des données dans un format réutilisable, fenêtre d'au moins 30 jours après le terme avant suppression.
- **Escalade (JAUNE)** : fenêtre de réversibilité < 15 jours ; export facturé ; suppression immédiate.

## Rappel
Cette analyse assiste la décision mais ne constitue pas un conseil juridique.
Tout point ROUGE doit être validé par l'avocat conseil avant signature.
