# HastaLuego

**Lien du jeu (GitHub Pages)** – *Jouez en ligne ici :* **https://YOUR-USERNAME.github.io/HastaLuego/**

## Description du jeu

HastaLuego est un mini-jeu rétro en HTML5/CSS/JS où vous naviguez un petit voilier pixelisé jusqu’à bon port. Le bateau avance en mer sur un fond animé style 8-bit, et doit éviter des obstacles tout en respectant les règles de navigation maritime :
- **Bouées rouges (bâbord)** : doivent être passées **par la droite** du bateau.
- **Bouées vertes (tribord)** : doivent être passées **par la gauche** du bateau.
- **Rochers** : doivent être évités, sinon c’est l’échouage assuré !

Après avoir correctement passé 12 obstacles, un **drapeau jaune** apparaît représentant le port d’arrivée (le pot de départ). À vous de guider le bateau jusqu’au drapeau pour gagner et afficher le message de fin !

## Contrôles

- **Flèche gauche/droite** – Déplacer le bateau latéralement vers la gauche ou la droite.
- **Espace** – Lancer la partie (ou relancer après un échec).

*(Note : Le bateau se déplace automatiquement vers l’avant. Il n’est pas nécessaire d’accélérer ou de ralentir – concentrez-vous sur sa direction.)*

## Installation et lancement

1. **Installation** – Clonez ce dépôt GitHub ou téléchargez le code source, puis hébergez-le sur votre ordinateur ou un serveur web. Aucune dépendance n’est requise, tous les assets (images pixel art en base64, script, etc.) sont inclus dans `index.html` et la musique est fournie.
2. **Lancement** – Ouvrez simplement le fichier `index.html` dans un navigateur web moderne. Pour une meilleure expérience, hébergez le jeu via un serveur web (par exemple en utilisant GitHub Pages ou un plugin Live Server), afin que la musique **hasta-luego.mp3** se charge correctement.
3. **GitHub Pages** – Vous pouvez également accéder au jeu déployé sur GitHub Pages à l’URL indiquée ci-dessus (remplacez `YOUR-USERNAME` par votre nom d’utilisateur GitHub après avoir poussé le code sur un repo public nommé *HastaLuego*).

## Crédits

- **Musique** – *“Hasta Luego”* (`assets/hasta-luego.mp3`). Merci à son auteur pour cette bande-son entraînante accompagnant le jeu.
- **Graphismes** – Sprites et arrière-plan en **pixel art** réalisés pour ce projet, inspirés du style rétro 8-bit des vieux jeux vidéo. (Le design des bouées et du bateau reprend les conventions de couleur et forme du balisage maritime réel.)
