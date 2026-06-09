=============================================================
       CAHIER DES CHARGES — PORTFOLIO EN LIGNE
             Agence Digitale « IgoTech »
=============================================================
Cours      : Génie Logiciel
Filière    : Génie Informatique — Niveau II
Établissement : CEFOD Business School
Date de remise : 09 juin 2026
Prof       : Ing Betan Gildas Ongbaye
=============================================================

1. PRÉSENTATION DU PROJET
--------------------------
1.1 Contexte
IgoTech est une agence de communication digitale spécialisée dans :
  - La création de sites web
  - La gestion des réseaux sociaux
  - La création de contenu visuel
  - Les campagnes de marketing digital

1.2 Objectif
Concevoir et développer un portfolio numérique en ligne qui :
  - Présente les services offerts par l'agence
  - Met en valeur les projets réalisés
  - Affiche les témoignages de clients satisfaits
  - Facilite la prise de contact avec les prospects

2. EXIGENCES FONCTIONNELLES
----------------------------
REQ-F01 : Affichage de la section Hero (accueil / bannière principale)
REQ-F02 : Présentation des services de l'agence
REQ-F03 : Galerie des projets réalisés (portfolio)
REQ-F04 : Section témoignages clients
REQ-F05 : Formulaire de contact (nom, email, message)
REQ-F06 : Navigation fluide par ancrage (one-page scroll)
REQ-F07 : Pied de page avec liens sociaux

3. EXIGENCES NON FONCTIONNELLES
---------------------------------
REQ-NF01 : Responsive design — compatible ordinateur, tablette, smartphone
REQ-NF02 : Temps de chargement optimisé (pas de dépendance lourde)
REQ-NF03 : Code lisible, commenté et structuré (séparation HTML / CSS / JS)
REQ-NF04 : Accessibilité de base (balises sémantiques HTML5)
REQ-NF05 : Compatible avec les navigateurs modernes (Chrome, Firefox, Edge)

4. ARCHITECTURE DU PORTFOLIO
------------------------------
4.1 Structure des pages (one-page)
  #hero       → Bannière d'accueil avec slogan et bouton CTA
  #services   → Cartes des services proposés
  #projets    → Grille des projets réalisés
  #temoignages → Avis de clients satisfaits
  #contact    → Formulaire de prise de contact
  footer      → Réseaux sociaux, copyright

4.2 Structure des fichiers (séparation des responsabilités)
  index.html       → Structure et contenu (HTML sémantique)
  css/style.css    → Mise en page globale et typographie
  css/components.css → Style des composants (cartes, boutons, formulaire)
  css/responsive.css → Media queries pour l'adaptabilité
  js/main.js       → Navigation, smooth scroll, interactions générales
  js/contact.js    → Validation et gestion du formulaire de contact
  assets/          → Images, icônes, logo

5. TECHNOLOGIES CHOISIES
--------------------------
Technologie    Justification
-----------    ---------------------------------------------------
HTML5          Structure sémantique standard du web
CSS3           Mise en forme, animations, Flexbox/Grid
JavaScript ES6 Interactions légères sans dépendance externe
Google Fonts   Typographie distinctive et gratuite
GitHub Pages   Hébergement gratuit et versioning du code source

Pas de framework lourd (React, Vue) → facilité de mise à jour
par les membres non techniques de l'agence.

6. MAQUETTE (WIREFRAME)
------------------------
Voir Livrable 2 — wireframe.html

7. CONTRAINTES
---------------
- Date de remise : 09 juin 2026
- Hébergement : GitHub (lien à envoyer à tibetan.dev@gmail.com)
- Optionnel : codage complet du portfolio

8. LIVRABLES
-------------
1. Cahier des charges (ce document)
2. Squelette du portfolio en version image (wireframe.html)
3. Code source HTML/CSS/JS multi-fichiers

=============================================================