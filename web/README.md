# ALBI RP™ | L'ULTIME EXPÉRIENCE ROLEPLAY

Bienvenue sur le dépôt du site web officiel de **ALBI RP™**. Ce projet est une landing page immersive pour le serveur Roblox Roleplay basé sur la ville d'Albi.

## 📝 À Propos

Ce site sert de portail d'entrée pour la communauté ALBI RP. Il présente le serveur, ses fonctionnalités (police, gangs, économie réaliste), et permet d'accéder aux liens essentiels (Discord, Boutique).

L'interface est conçue avec une esthétique **Néo-Brutaliste / Cyberpunk** unique, intégrant des effets visuels avancés (Glitch, CRT, Marquee) et un système de thèmes dynamiques.

## 🛠 Technologies Utilisées

Ce projet est construit avec des technologies web standards pour une performance maximale et une simplicité de déploiement :

- **HTML5** : Structure sémantique et accessibilité.
- **Tailwind CSS (CDN)** : Framework CSS utilitaire pour le styling rapide et réactif.
- **Vanilla JavaScript** : Logique légère sans framework lourd (pas de React/Vue/Angular).
- **Vercel Edge Middleware** : Gestion des en-têtes de sécurité (HSTS, X-Frame-Options, etc.) via `middleware.js`.

## ✨ Fonctionnalités Clés

- **Système de Thèmes Dynamique** :
  - _Neo Brutalist_ (Défaut) : Couleurs vives, contours noirs épais.
  - _Albi Historique_ : Tons rouges brique et ocres, rappelant la Cité Épiscopale.
  - _Data / Terminal_ : Mode sombre "hacker" pour le lore.
  - _Vote / Socials / Shop_ : Thèmes contextuels adaptés aux sections.
- **Effets Visuels Immersifs** :
  - Effet **CRT** (Cathode Ray Tube) avec scanlines et scintillement.
  - Animations de texte **Marquee** (défilement) et typographie cinétique.
  - Effets **Glitch** interactifs au scroll.
  - Curseur personnalisé avec états hover/click.
- **Navigation SPA-like** : Transition fluide entre les sections ("Home", "Concept", "Team") sans rechargement de page.
- **Optimisation SEO** : Balises Meta complètes pour le partage social (Open Graph, Twitter Cards).

## 🚀 Déploiement

Le site est conçu pour être déployé sur **Vercel**.

1.  Le fichier `middleware.js` est automatiquement détecté par Vercel pour appliquer les headers de sécurité.
2.  Le fichier `package.json` est présent pour définir le projet, bien qu'aucune dépendance npm ne soit requise pour le build (le CSS est chargé via CDN).

## 📄 Licence & Copyright

**© ALBI RP™ - TOUS DROITS RÉSERVÉS (COPYRIGHT ALL TIME)**

Ce code source et les assets associés sont la propriété exclusive de ALBI RP™ Staff (Aïssa BELKOUSSA). Toute reproduction ou redistribution non autorisée est interdite.
