# Foot Boutons Mondial

Jeu de foot-boutons au tour par tour, jouable hors ligne (PWA), avec les 211 nations FIFA.

## Jouer
Ouvrir `index.html` dans un navigateur, ou servir le dossier en HTTP (`python3 -m http.server`) pour activer le mode hors ligne et l'installation sur l'écran d'accueil.

## Modes
- **Tournée** : bats 3 nations d'un niveau pour débloquer le suivant (5 niveaux, du rang 211 au top 10).
- **Amical** : affronte n'importe quelle nation, en 3, 5 ou 7 buts.
- **Tournois** : Coupe du Monde, Euro, Copa América, CAN, Coupe d'Asie, Gold Cup, Coupe d'Océanie (groupes + tableau final).
- **2 joueurs** : deux joueurs sur le même écran ; le joueur 2 joue le camp du haut.

## Fichiers
- `index.html` : tout le jeu (moteur physique, IA, menus, tournois).
- `sw.js` : service worker (cache hors ligne).
- `manifest.webmanifest`, `icon-*.png` : installation PWA.
