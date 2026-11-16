# GagaCad3D

Éditeur BIM tactile autonome pour iPhone — prototype V0.1.

## Fonctions V0.1
- Dessin de murs en plan 2D par deux points, avec grille et accrochage.
- Géométrie 3D synchronisée, navigation tactile et sélection.
- Édition des murs : longueur, orientation, épaisseur, hauteur, niveau, matériau.
- Projets enregistrés localement dans IndexedDB et restaurés sur l'appareil.
- Installation PWA depuis Safari et ouverture hors connexion après chargement des ressources nécessaires.

## Démarrage
Ouvrir `index.html` via un serveur HTTPS ou GitHub Pages. Dans Safari, ajouter le site à l'écran d'accueil. L'application reste indépendante d'Archicad et de Rhino.

**Attention :** il s'agit d'un éditeur BIM expérimental. Aucun import/export IFC, porte/fenêtre, étage, ni production de documents professionnels n'est disponible dans la V0.1. Les bibliothèques Three.js sont chargées via CDN lors de la première ouverture ; un premier chargement connecté est nécessaire.

## Usage
1. Choisir **Mur**, toucher le premier point puis le deuxième point sur le plan.
2. Choisir **Sélection**, toucher un mur pour modifier ses propriétés.
3. Passer à **3D** pour contrôler le modèle et sélectionner un mur.
4. Appuyer sur **Enregistrer**, **Ouvrir** ou **Nouveau**. Les projets restent dans le navigateur sur cet appareil.

## Licence
Tous droits réservés à GAGA.