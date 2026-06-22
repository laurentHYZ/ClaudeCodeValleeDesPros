# Démo plugin juridique — exercice `review-contract`

Mallette prête à l'emploi pour faire vivre la skill **`/review-contract`** (alias FR
**`/revision-contrat`**) du plugin Legal. Tout est **fictif**.

## Le pitch en une phrase
On donne aux participants un vrai-faux contrat SaaS truffé de pièges, et leur propre
« playbook » d'entreprise. La skill compare l'un à l'autre et sort des drapeaux
VERT / JAUNE / ROUGE avec des propositions de réécriture (redlines).

## Contenu du dossier
| Fichier | Rôle |
|---|---|
| `contrat-saas-cloudaxe.docx` | Le contrat à analyser. Cloudaxe (fournisseur) ↔ NetPro (client). |
| `legal.local.md` | Playbook **client/acheteur** (NetPro). Chargé **automatiquement** par la skill. |
| `playbook-fournisseur-cloudaxe.md` | Playbook **fournisseur** (Cloudaxe), pour l'exercice « changez de camp ». |
| `README-ANIMATEUR.md` | Ce fichier. **Ne pas distribuer** : il contient les réponses. |

## Déroulé (15 min)
1. Le participant sélectionne ce dossier dans Claude.
2. Il tape : `/review-contract contrat-saas-cloudaxe.docx`
3. La skill demande le contexte → répondre : **« côté client/acheteur, pas de deadline,
   point sensible = données personnelles (RGPD) »**.
4. La skill charge `legal.local.md` toute seule et rend son analyse clause par clause.
5. **Exercice « changez de camp »** : refaire en se plaçant côté fournisseur (playbook
   `playbook-fournisseur-cloudaxe.md`). Les drapeaux s'inversent → c'est l'enseignement.

## Anomalies plantées — corrigé (drapeau attendu, côté CLIENT)

| Art. | Clause | Piège planté | Drapeau attendu |
|---|---|---|---|
| 3 | Durée / résiliation | 36 mois fermes, pas de sortie pour le client, le fournisseur sort à 30 j | 🔴 ROUGE (asymétrie + verrou) |
| 3 | Reconduction | Préavis de dénonciation 90 j | 🟡 JAUNE |
| 4 | Paiement | Échéance 15 j ; pénalités = 3× taux légal ; suspension sans mise en demeure | 🟡 JAUNE |
| 4 | Révision tarifaire | Jusqu'à +12 %/an, unilatérale | 🟡 JAUNE |
| 5 | Propriété intellectuelle | Cession au fournisseur des éléments **préexistants** du client + licence feedback perpétuelle | 🔴 ROUGE |
| 6 | Données personnelles | **Pas de DPA** alors que données perso traitées ; hébergement **US sans CCT** ; sous-traitants sans info ; notif violation **30 j** (vs 72 h) | 🔴 ROUGE (le plus grave, RGPD) |
| 8 | Garanties | Service « en l'état », exclusion **totale** de garantie | 🔴 ROUGE |
| 9 | Responsabilité | Plafond = **3 mois** de redevances, non réciproque | 🔴 ROUGE |
| 10 | Indemnisation | **Unilatérale** à la charge du client, **sans plafond**, aucune indemnité contrefaçon du fournisseur | 🔴 ROUGE |
| 12 | Cession | Fournisseur cède librement (y c. changement de contrôle), client non | 🟡 JAUNE |
| 15 | Droit applicable | **Droit irlandais + tribunaux de Dublin** | 🔴 ROUGE (ou JAUNE selon enjeu) |
| Annexe 1 | Réversibilité | Export sous 5 j puis suppression définitive | 🟡 JAUNE |
| 7 | Confidentialité | Réciproque, 2 ans, exclusions usuelles | 🟢 VERT (clause saine témoin) |
| 13 | Force majeure | Standard, art. 1218 C. civ., sortie à 60 j | 🟢 VERT |

Une clause VERTE et une autre saine sont volontaires : montrer que la skill ne crie pas
au loup partout.

## Points d'animation
- Insister sur l'**Article 6** : c'est le réflexe RGPD attendu d'un dirigeant français.
- Montrer qu'un même article (ex. 9, 15) devient VERT vu du fournisseur → le drapeau
  dépend du **camp** et du **playbook**, pas du texte seul.
- Rappeler le disclaimer de la skill : aide à la décision, **pas un conseil juridique**.

> Données, sociétés, RCS, IBAN, montants : tous fictifs.
