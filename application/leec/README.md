# Reproduction du site Modelis Group Applications

## Contexte du projet

Ce dossier contient une reproduction en HTML/CSS du site web : https://applications.modelisgroup.com/

**Date de création** : 31 décembre 2024
**Dernière mise à jour** : 31 décembre 2024 - Adaptation à la charte graphique LEEC

## Charte graphique LEEC

Le site respecte la charte graphique de LEEC basée sur le logo officiel :

### Couleurs principales

- **Bleu turquoise** : `#1B9BD8` / `#0B8FD0` - Couleur principale utilisée pour le fond et les icônes
- **Orange** : `#F47920` / `#E67E22` - Couleur d'accentuation pour les boutons et liens
- **Blanc** : Utilisé pour le texte et les cartes

### Éléments visuels

- Logo LEEC intégré dans le header avec fond blanc
- Dégradés bleu turquoise pour l'arrière-plan et les icônes
- Boutons orange pour les appels à l'action
- Design cohérent avec l'identité visuelle LEEC

## Analyse du site original

Le site original est une page d'accueil centralisée qui répertorie les différentes applications utilisées par Modelis Group. Il présente :

### Applications listées :
1. **ERP** - Avec deux liens (Adresse Interne et Adresse Externe)
2. **GITHUB** - Lien vers GitHub
3. **GED** - Gestion Électronique de Documents
4. **ZOOM** - Plateforme de visioconférence
5. **ASANA** - Outil de gestion de projet
6. **SLACK** - Plateforme de communication

### Design et structure :
- Layout en grille responsive
- Cartes pour chaque application
- Icônes/badges pour identifier visuellement chaque application
- Liens d'accès directs
- Footer avec copyright Modelis Group

## Structure des fichiers créés

```
application/leec/
├── index.html      # Page principale HTML
├── styles.css      # Feuille de style CSS
├── logo.jpg        # Logo LEEC
└── README.md       # Ce fichier de documentation
```

## Fichiers créés

### 1. `index.html`

Page HTML principale contenant :

- Structure sémantique HTML5
- Logo LEEC dans le header
- 6 cartes d'applications avec logos SVG intégrés (ERP, GITHUB, GED, ZOOM, ASANA, SLACK)
- Système d'overlay au hover pour afficher les liens
- Header avec logo et titre
- Footer avec copyright et lien vers Modelis Group
- Design responsive

### 2. `styles.css`
Feuille de style CSS avec :

- **Design moderne** : Dégradé bleu turquoise (#1B9BD8 → #0B8FD0) en arrière-plan
- **Logo LEEC** : Intégré dans le header avec fond blanc et ombres
- **Cartes élégantes** : Fond blanc, ombres portées, coins arrondis
- **Logos SVG** : Icônes vectorielles de 80x80px en couleur bleu turquoise
- **Effet hover avancé** : Overlay sombre (rgba(0, 0, 0, 0.75)) qui apparaît au survol
- **Transition fluide** : Animation d'opacité pour le contenu et l'overlay
- **Boutons attractifs** : Dégradé orange (#F47920 → #E67E22), visibles uniquement au hover
- **Responsive** : Grid adaptative (auto-fit, minmax)
- **Mobile-friendly** : Media queries pour petits écrans et logo adaptatif

## Caractéristiques techniques

### Technologies utilisées :
- HTML5 sémantique
- CSS3 moderne (Grid, Flexbox, Gradients, Transitions)
- Design responsive sans framework

### Fonctionnalités :
- Grid responsive (3 colonnes sur grand écran, 1 colonne sur mobile)
- Logo LEEC responsive (300px → 200px sur mobile)
- Animations au survol (transform, box-shadow)
- Dégradés de couleurs LEEC (bleu turquoise et orange)
- Ombres portées pour la profondeur
- Typographie moderne (Segoe UI)

## Utilisation

Pour visualiser le site :
1. Ouvrir `index.html` dans un navigateur web
2. Le site est entièrement statique et fonctionne sans serveur

## Personnalisation possible

Pour adapter le site à vos besoins :
- **Ajouter des applications** : Dupliquer un bloc `.app-card` dans `index.html`
- **Modifier les couleurs** : Changer les valeurs des gradients dans `styles.css`
- **Changer les liens** : Mettre à jour les attributs `href` dans les balises `<a>`
- **Ajouter des icônes** : Intégrer une bibliothèque d'icônes (Font Awesome, etc.)

## Notes de développement

- Le site est une reproduction visuelle et fonctionnelle
- Respect strict de la charte graphique LEEC (bleu turquoise #1B9BD8 et orange #F47920)
- Logo LEEC intégré dans le header avec fond blanc
- Logos SVG intégrés directement dans le HTML (pas de fichiers externes)
- Effet hover avec overlay sombre inspiré du site Modelis Group
- Les boutons apparaissent uniquement au survol des cartes
- Les liens sont des placeholders (#) sauf pour GitHub, Zoom, Asana et Slack
- Le design a été modernisé avec des effets visuels améliorés
- Totalement responsive et mobile-first
- Aucune dépendance externe (pas de framework CSS ou JS)

## Historique des modifications

### 31 décembre 2024 - Version 3.2
- Modification de la grille pour afficher exactement 3 cartes par ligne
- Remplacement du SVG GitHub par un SVG de mail (enveloppe)
- Commentaire de la carte GED (désactivée temporairement)
- Ajout d'un breakpoint pour tablettes (2 colonnes entre 769px et 1024px)

### 31 décembre 2024 - Version 3.1
- Ajout de couleurs personnalisées pour chaque carte d'application
- ERP : Bleu turquoise (#1B9BD8)
- Mail : Vert (#7CB342)
- GED : Cyan (#26C6DA) - Désactivée
- ZOOM : Orange (#FF9800)
- ASANA : Violet (#AB47BC)
- SLACK : Jaune (#FDD835)
- Réduction de la taille des cartes (min-height: 200px au lieu de 250px)
- Réduction de la taille des logos (60px au lieu de 80px)
- Texte et logos en blanc sur fond coloré

### 31 décembre 2024 - Version 3.0
- Remplacement des textes par des logos SVG pour chaque application
- Ajout d'un effet hover avec overlay sombre (rgba(0, 0, 0, 0.75))
- Les boutons "Acceder au site" apparaissent uniquement au survol
- Animation fluide de transition entre état normal et hover
- Logos SVG intégrés directement dans le HTML (pas de dépendances externes)

### 31 décembre 2024 - Version 2.0

- Adaptation complète à la charte graphique LEEC
- Remplacement des couleurs violet/bleu par bleu turquoise (#1B9BD8)
- Remplacement des boutons par la couleur orange LEEC (#F47920)
- Intégration du logo LEEC dans le header
- Ajout du responsive pour le logo

### 31 décembre 2024 - Version 1.0

- Création initiale du site
- Reproduction du site Modelis Group Applications
- Design moderne avec dégradés violet/bleu

## Copyright

Reproduction du site original  2022 [MODELIS GROUP](http://www.modelisgroup.com)