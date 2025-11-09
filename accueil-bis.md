---
hidden: true
---

# Accueil bis

Voici une version plus nette, cohérente et “copiable-collable” pour **la page d’accueil (Home)**. J’ai gardé tout ce que tu voulais, en resserrant la formulation, en évitant les doublons, et en rendant la lecture plus fluide.

***

## 🌌 IKAI – Live-to-Earn (L2E) : un univers Web3 géolocalisé et économique

**Ikai** est une application mobile Web3 sur **Solana** qui fusionne exploration du monde réel, mécaniques **RPG**, classes interconnectées et **économie décentralisée**. Les joueurs se déplacent physiquement, accomplissent des missions, combattent et échangent des ressources, **objets** et **NFT**, tout en faisant progresser leur profil.

Au cœur d’Ikai : le **Live-to-Earn (L2E)**

> **Vivre, jouer et se déplacer dans le monde réel génère de la valeur utile**, transformant l’activité quotidienne en progression durable et en opportunités économiques.

Ce document présente la vision d’Ikai : une **expérience fluide**, des **mécaniques de jeu immersives**, une **économie circulaire** régulée, et l’intégration des **Real World Assets (RWA)** pour ancrer la stratégie dans des territoires réels. Objectif : un écosystème où **activité physique**, **coopération** et **stratégie économique** se renforcent, avec la rapidité et les faibles coûts de **Solana**.

***

### 🎮 Expérience utilisateur & onboarding

Conçu pour **minimiser la friction**, Ikai accueille à la fois les curieux du Web3 et les experts.

#### 1) Écran d’accueil (Splash)

* **Barre d’énergie arc-en-ciel** (effet néon) = identité visuelle + feedback immédiat.
* **Mascotte Slime** animée.
* Pré-chargement rapide + vérification Web3.

#### 2) Connexion & création de compte

| Méthode                                | Détails                                                   |
| -------------------------------------- | --------------------------------------------------------- |
| **Wallet Solana** (Phantom, Backpack…) | Connexion Web3 sécurisée, accès immédiat aux actifs.      |
| **Email**                              | OTP rapide, avec possibilité de lier un wallet plus tard. |
| **Téléphone**                          | OTP SMS, idéal mobile-first.                              |

Pas de wallet ? Un assistant guide la **création ou l’import** (phrase de récupération, bonnes pratiques). Tout compte peut être **lié à un wallet** ultérieurement.

#### 3) Personnalisation de l’avatar

* **Genre** : Homme, Femme, Neutre (impact visuel sur l’avatar 3D / phases Unity).
* Réversible au début pour encourager l’expérimentation.
* L’avatar **évolue** avec la progression et les NFT.

***

### 🎁 Packs d’entrée (Starter Packs)

Les packs positionnent le joueur et injectent du fun via un tirage probabiliste (NFT & rang). Paiement en **SOL**.

| Pack              | Prix (SOL) | Probabilités principales           | Contenu                                                                                          |
| ----------------- | ---------: | ---------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Débutant**      |        0.5 | 95% rang G→D ; SSS possible (rare) | **NFT Personnage** non-transférable (lié à l’âme), objets essentiels (armes/skins), **crédits**. |
| **Intermédiaire** |          2 | 95% rang D→B ; SSS possible (rare) | Bonus de stats, objets avancés, **familier** de base.                                            |
| **Avancé**        |          3 | 95% rang C→A ; SSS possible (rare) | Bonus plus élevés, **skins exclusifs**, items rares, crédits sup.                                |

**Commun à tous** :

* **NFT Personnage évolutif** (non transférable) pour éviter la spéculation abusive.
* **Objets NFT** transférables (armes, skins, familiers).
* **Crédits initiaux** + **bonus de rang** impactant la progression.

**Packs Partenariats**

Possesseurs d’un **NFT partenaire** : possibilité de **burn** pour obtenir un **NFT IKAI Partenaire** (visuel unique, classe thématique, rang bonus). Ces NFT partenaires sont **transférables**.

***

### 🏅 Rangs : impacts & animations

Le rang est tiré à l’ouverture du pack (pondéré pour l’équilibre). Il influence fortement la progression.

| Rang              | Rareté indicative | Effets visuels       | Impacts (exemples)                                     |
| ----------------- | ----------------- | -------------------- | ------------------------------------------------------ |
| **SSS / SS / S**  | \~1–5%            | Cinématiques premium | **x2 XP**, +50% loot rare, −30% coûts de craft/upgrade |
| **A / B / C**     | \~10–20%          | Animations colorées  | **x1.5 XP**, +20% loot, −15% coûts                     |
| **D / E / F / G** | \~75%             | Minimal              | Progression standard                                   |

Des rangs **Divins** ultra-rares (événements/ventes limitées) peuvent offrir des accès VIP ou des effets signature.

***

### 🧩 Classes principales & sous-classes

**12 classes** ancrées dans la **fonction économique** pour forcer l’interdépendance :

* **Invocateur** : crée des **familiers NFT** à vendre.
* **Agriculteur** : récolte des **ressources rares** (exploration IRL).
* **Guerrier** : donjons/combats, sous-classes **Ninja**, **Paladin**, **Berserker**…
* **Marchand** : bonus d’échange, frais réduits, **insights** économiques.

Chaque classe définit :

* **Stats de base**, **missions exclusives**, **recettes** & **arborescences** de progression.
* **Sous-classes** déverrouillées via XP + ressources **d’autres classes** (économie circulaire).

***

### 🗺️ Interface & navigation

#### Lobby principal (hub)

Accès rapide à : **Carte**, **Inventaire**, **Missions**, **Marché**, **Profil**. Notifications push pour **donjons proches**, événements, offres.

#### Carte géolocalisée 🌍

Propulsée par **Mapbox/OpenStreetMap** :

* Position GPS immédiate.
* Visibilité des autres joueurs (amis/guilde ; respect de la confidentialité).
* **Zones spéciales** :
  * **Loot spots** (collecte localisée),
  * **Quêtes IRL** (lieux réels),
  * **Donjons temporaires**,
  * **Bases de guildes**,
  * **Événements saisonniers**.

**Vision** : un **MMORPG géolocalisé** (esprit Pokémon GO) enrichi par une **économie crypto** et des **systèmes RPG profonds**.

***

### 🧠 Progression : la boucle de jeu

| Pilier                   | Rôle                                                                              |
| ------------------------ | --------------------------------------------------------------------------------- |
| **Rang**                 | Multiplicateurs de gains, coûts de craft, rareté des loots.                       |
| **Classe & Sous-classe** | Rôle économique + recettes ; dépendances inter-classes.                           |
| **XP / Niveaux**         | Marche/course, missions, combats → niveaux & branches d’évolution.                |
| **Objets & NFT**         | Loot, craft, fusion, évolution ; **équipables** et **échangeables** (selon type). |
| **$IKAI (utility)**      | Achats in-game, boosts/staking, coûts d’upgrade (mécaniques de **burn**).         |

La progression est **non linéaire**, pilotée par les **choix** et les **échanges** entre joueurs.

***

### ⚔️ Mécaniques clés

#### Exploration IRL

* Déplacements réels → **découvertes**, **loots**, **rencontres**.
* Anti-triche (ex. **limite de vitesse**) pour éviter les abus (véhicule).

#### Énergie / Endurance

* **1 à 3 barres** initiales (déblocables/évolutives).
* Exemple : 1 barre ≈ 30 min d’exploration active (variable selon niveau/équipement).
* **Recharge** : quotidienne, objets, ou **staking $IKAI**.

#### Missions & Donjons

* **Quotidiennes / Hebdo** (ex. marcher 5 km = XP + loot).
* **Donjons IRL** : apparition aléatoire, **solo** ou **guilde** (partage au **% contribution** : DPS, soins, etc.).

#### Marketplace

* **Intégré**, compatible **Magic Eden** / **OpenSea** (achat in-app).
* **Frais faibles** (ex. 1–2%) redistribués à l’écosystème et aux mécaniques de régulation.

***

### 💼 Tokenomics (synthèse)

* **$IKAI (utility token)** sur **Solana** : achats, boosts/staking, coûts d’upgrade (**burn** pour limiter l’inflation).
* **NFT évolutifs** : valeur liée à l’usage (et non à la seule rareté).
* **Économie circulaire** : la **dépendance entre classes** empêche l’autarcie.

_Exemple d’allocation initiale_ (indicative) : **40% communauté**, **20% équipe** (vesting), **20% liquidité**, **10% marketing**, **10% réserve**. Focus : **utilité long terme**, pas de mécaniques spéculatives “pump-and-dump”.

***

### 🌍 RWA : Royaumes & Villes réelles

Les **villes réelles** deviennent des **NFT territoriaux** (Solana) détenus par joueurs/guildes/organisations.

**Avantages principaux** :

* **Revenus passifs** : part des transactions locales (smart contracts + oracles géo).
* **Contrôle territorial** : emblème, **château** visible sur carte.
* **Taxation** : taux local **0–30%** sur gains (XP/loots) → équilibre **attractivité / revenus**.
* **Conquête & Défense** : guerres asynchrones, stratégie de **staking SOL**.

**NFT Ville** : métadonnées (nom, pays, superficie, **GeoHash**), statut (libre/contrôlée/en guerre), **transferts** via marketplace.

**Exemples mécaniques** :

* **Part marketplace** locale (ex. **1,5%**) versée mensuellement en **$IKAI** ou **SOL**.
* **Royaume (château)** via **staking** (ex. 1–100 SOL selon taille) : +défense, +gains, mais **risque** de perdre la mise et la ville en cas de défaite.

**Combats de royaumes** (semi-automatisés) :

* Le défenseur **déploie des créatures NFT** ; l’attaquant mise en **SOL** + sélectionne ses créatures.
* Vainqueur : **capture** la ville + récupère le **stake** adverse.

**Classements** : par pays, monde, hebdo (récompenses saisonnières), basés sur volume éco, taux d’imposition, niveau de mise SOL, historique de batailles.

***

### 🚀 En bref

Ikai transforme **la vie réelle en terrain de jeu économique** : marche, missions, donjons, commerce, territoires. Grâce à **Solana**, l’expérience est **rapide**, **évolutive** et **peu coûteuse**. Le **L2E** d’Ikai relie **exploration IRL**, **RPG profond** et **économie Web3** — avec des **RWA** qui donnent du poids stratégique aux villes du monde réel.

**Bienvenue dans Ikai.**
