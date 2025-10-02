# HastaLuego &nbsp; ![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

**Live Demo:** Remplacez `YOUR-USERNAME` par votre nom d’utilisateur GitHub pour jouer sur GitHub Pages: **https://YOUR-USERNAME.github.io/HastaLuego/**

## Résumé du jeu

**HastaLuego** est un mini-jeu HTML5 en style *pixel art* dans lequel vous contrôlez un petit voilier sur la mer. Le but du jeu est de naviguer en évitant les obstacles et en respectant les bouées de balisage pour finalement atteindre un drapeau jaune d’arrivée. Le jeu est développé en HTML/CSS/JavaScript *vanilla* sans aucune dépendance externe, et il est entièrement jouable sur une page web.

## Contrôles et Règles du Jeu

**Contrôles :**  
- **Flèches gauche/droite :** déplacer le voilier vers la gauche ou la droite.  
- **Barre d’espace :** démarrer la partie (peut également activer la musique) ou mettre le jeu en pause à l’écran de titre.

**Règles :**  
- Évitez de percuter les **rochers marron** qui apparaissent sur la mer.  
- Les **bouées rouges carrées** doivent être contournées **par la droite** du voilier (le voilier doit passer à droite de ces bouées).  
- Les **bouées vertes triangulaires** doivent être contournées **par la gauche** du voilier.  
- Si vous touchez un rocher ou une bouée (erreur de passage), un message d’erreur s’affiche et la partie redémarre depuis le début.  
- Après avoir esquivé correctement **12 obstacles** consécutifs, un **drapeau jaune** apparaît : attrapez-le avec votre bateau pour gagner. Le message de victoire met en évidence la date **“jeudi 7 novembre”** pour célébrer votre arrivée.

## Comment Tester / Héberger le Jeu

- **Test local :** Ouvrez simplement le fichier `index.html` dans un navigateur web moderne. Le jeu affichera un écran d’introduction pendant 8 secondes avant de démarrer automatiquement (appuyer sur *Espace* démarre immédiatement). Assurez-vous d’activer le son pour entendre la musique de fond.  
- **GitHub Pages :** Pour héberger le jeu en ligne, placez `index.html`, `README.md` et le dossier `assets` (contenant `hasta-luego.mp3`) dans un nouveau dépôt GitHub nommé *HastaLuego*. Activez GitHub Pages dans les paramètres du dépôt (branche `main` ou `docs`), puis accédez à l’URL du dépôt GitHub Pages (par exemple **YOUR-USERNAME.github.io/HastaLuego/**) pour jouer.  

Le jeu est responsive et s’adapte à la taille de la fenêtre. Aucune installation n’est requise : tous les éléments (code, sprites en base64, musique) sont intégrés localement.

## Crédits

- **Graphismes :** Les sprites pixel art (voilier, rochers, bouées, drapeau) ont été créés spécialement pour ce jeu, en s’inspirant du style visuel des jeux rétro 8-bit. Ils sont encodés en base64 directement dans le code HTML.  
- **Musique :** Une musique d’ambiance intitulée *“Hasta Luego”* (fichier audio `assets/hasta-luego.mp3`) est jouée pendant la partie. Pensez à activer le son pour en profiter. Cette musique est incluse localement dans le projet pour une expérience de jeu immersive.
