# Système Territorial



#### Résumé

Le Système Territorial définit la manière dont les espaces (territoires, provinces, royaumes) sont représentés, possédés, exploités et valorisés dans l’écosystème Life 2 Tarn / IKAI. Il s’agit d’un système hybride : mécanique de jeu (ownership, conquêtes) + intégration RWA (actifs du monde réel tokenisés ou indexés) pour créer une valeur durable et traçable.

#### Objectifs

* Créer une hiérarchie territoriale claire (Territoires → Provinces → Royaumes).
* Lier chaque entité territoriale à des revenus RWA traçables (ressources, loyers, taxes).
* Permettre une gouvernance territoriale locale tout en garantissant des règles anti-fraude et une transparence totale des flux.

#### Composants principaux

1. **Territoire** — Unité de base (carte hex/tuile). Peuvent être possédés par joueurs, guildes ou organisations.
2. **Province** — Ensemble de territoires adjacents, géré par une administration locale (conseil).
3. **Royaume** — Entité politique et économique majeure (regroupe plusieurs provinces).
4. **Actifs RWA liés** — Parcelles réelles, bâtiments, portions d’infrastructure (si tokenisés ou indexés) rattachés aux entités territoriales.

#### Règles clés

* Chaque entité a une **propriété** (wallet/gouvernance) enregistrée on-chain (ou via registre d’attestation) pour assurer traçabilité.
* Les **droits d’exploitation** (collecte de revenus, taxes, commerce) sont définis par la structure du territoire et par les règles locales votées en gouvernance.
* Aucun mécanisme opaque de “spending” interne ne peut être utilisé pour générer des volumes artificiels : toute entrée/sortie majeure doit être auditable.
* Les transferts de propriété respectent un protocole d’enchères / ventes transparentes (log on-chain + enregistrement RWA).

#### Exemple d’usage

* Une guilde achète une province ; elle perçoit loyers sur les territoires, finance des infrastructures, et reverse une part aux détenteurs historiques via smart contracts.
