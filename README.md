# 🚢 Hasta Luego

Un mini-jeu de navigation en pixel art pour célébrer un départ mémorable après 7 ans d'aventure !

![Pixel Art Boat Game](https://img.shields.io/badge/style-pixel%20art-blue) ![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

## 🎮 Concept du jeu

Naviguez sur les flots avec votre petit voilier et évitez les obstacles pour atteindre le port ! Un jeu rétrogaming inspiré des classiques 8-bit, accompagné de la mélodie nostalgique d'"Hasta Luego" d'Hugues Auffray.

## 🎯 Objectif

Guidez votre bateau à travers 12 obstacles variés pour atteindre le port de départ et découvrir une invitation spéciale !

## 🕹️ Contrôles

- **Flèches directionnelles** : Déplacer le bateau (↑ ↓ ← →)
- **Barre ESPACE** : Lancer le jeu / Recommencer après un game over

## 🌊 Les obstacles

### 🪨 Rochers marrons
Des cailloux traîtres que vous devez éviter en passant à droite ou à gauche. 
*Attention : S'échouer sur un rocher révélera votre vraie nature de... quanti !*

### 🔴 Bouées bâbord (rouges - carrées)
Situées sur la moitié gauche de l'écran. **Vous devez TOUJOURS passer à DROITE**.
*"On doit passer à droite des bouées bâbord rouges ! Marin d'eau douce !"*

### 🟢 Bouées tribord (vertes - triangulaires)
Situées sur la moitié droite de l'écran. **Vous devez TOUJOURS passer à GAUCHE**.
*"On doit passer à gauche des bouées tribord vertes ! Même Fred !"*

## 🎨 Style visuel

Le jeu adopte une esthétique pixel art rétrogaming avec :
- Mer animée avec effet de vagues
- Sprites dessinés en pixel art
- Palette de couleurs vibrante et nostalgique
- Interface inspirée des jeux 8-bit

## 🎵 Bande son

Le jeu est accompagné de la chanson **"Hasta Luego"** d'Hugues Auffray, qui se lance automatiquement et joue en boucle tout au long de votre navigation.

## 📦 Installation

### Pour jouer localement :

1. Clonez ce repository :
```bash
git clone https://github.com/[votre-username]/HastaLuego.git
cd HastaLuego
```

2. Ajoutez le fichier audio `hasta-luego.mp3` dans le même dossier que `index.html`

3. Ouvrez `index.html` dans votre navigateur web préféré

### Pour jouer en ligne :

Visitez simplement : `https://[votre-username].github.io/HastaLuego/`

## 📁 Structure du projet

```
HastaLuego/
│
├── index.html          # Le jeu complet (HTML + CSS + JavaScript)
├── hasta-luego.mp3     # Fichier audio de la chanson (à ajouter)
└── README.md           # Ce fichier
```

## 🎓 Règles de navigation maritime

Ce jeu vous apprendra les bases du code maritime pour les bouées :

- **Bouées bâbord (rouges)** : À laisser sur la gauche du bateau (donc passer à droite)
- **Bouées tribord (vertes)** : À laisser sur la droite du bateau (donc passer à gauche)

*"Rouge à droite, vert à gauche, on rentre au port !"*

## 🏆 Victoire

Après avoir évité les 12 obstacles, votre bateau rejoindra automatiquement le "po(r)t de départ" marqué par un drapeau jaune. Une fois arrivé, vous découvrirez les détails de l'invitation au pot de départ !

## 🔧 Technologies utilisées

- **HTML5 Canvas** : Pour le rendu graphique
- **Vanilla JavaScript** : Logique du jeu et animations
- **CSS3** : Style de l'interface
- **Web Audio API** : Gestion de la musique

## 📝 Notes techniques

- Le jeu se lance automatiquement après 8 secondes si le joueur n'appuie pas sur ESPACE
- Vitesse de défilement : 2 pixels par frame
- Durée moyenne d'une partie : ~30 secondes
- Obstacles générés aléatoirement dans des zones prédéfinies
- Système de collision précis basé sur les hitboxes

## 🐛 Dépannage

**La musique ne se lance pas ?**
- Certains navigateurs bloquent la lecture automatique. Cliquez n'importe où sur la page pour activer l'audio.
- Vérifiez que le fichier `hasta-luego.mp3` est bien présent dans le même dossier.

**Le jeu ne s'affiche pas correctement ?**
- Utilisez un navigateur moderne (Chrome, Firefox, Edge, Safari)
- Assurez-vous que JavaScript est activé

## 🎉 Message spécial

Ce jeu a été créé pour célébrer un départ après 7 ans d'aventure chez Harris. Un grand merci à tous les équipiers qui ont partagé cette navigation !

*"Après 7 ans dans le même bateau, il est temps de changer d'équipage et de larguer les amarres vers de nouvelles aventures..."*

## 📅 Rendez-vous

**Jeudi 6 novembre** - Cafèt - Pot de départ
*Avant de se déhaler vers une destination plus festive !*

## 📜 Licence

Ce projet est un jeu personnel créé pour un événement privé.

---

⚓ *Bon vent et bonne mer !* ⛵
