# HastaLuego 🚢

Un jeu de navigation maritime rétro en pixel art pour dire au revoir à l'équipage d'Harris après 7 ans d'aventures !

![HastaLuego Game](https://img.shields.io/badge/status-ready%20to%20sail-blue)

## 🎮 Description

**HastaLuego** est un mini-jeu de navigation où vous devez guider votre voilier à travers une série d'obstacles maritimes pour atteindre le port de départ. Évitez les rochers et respectez les règles de navigation des bouées pour réussir votre traversée !

## 🎯 Objectif

Naviguer à travers 12 obstacles sans collision pour atteindre le drapeau du port de départ et découvrir une invitation spéciale.

## 🕹️ Comment jouer

### Contrôles
- **Flèches directionnelles** : Déplacer le bateau (↑ ↓ ← →)
- **ESPACE** : Lancer le jeu / Réessayer après un échec

### Règles de navigation
1. **Rochers 🪨** : Évitez-les en passant à droite ou à gauche
2. **Bouées rouges carrées** : Passez toujours à **droite** (règle bâbord)
3. **Bouées vertes triangulaires** : Passez toujours à **gauche** (règle tribord)

### Collisions
- Collision avec un rocher → "Tu t'es échoué ! Tu dois sûrement être un quanti…"
- Passage incorrect d'une bouée rouge → "On doit passer à droite des bouées bâbord rouges ! Marin d'eau douce !"
- Passage incorrect d'une bouée verte → "On doit passer à gauche des bouées tribord vertes ! Même Fred !"

## 📁 Installation

### Méthode 1 : Clone du repository
```bash
git clone https://github.com/votre-username/HastaLuego.git
cd HastaLuego
```

### Méthode 2 : Téléchargement direct
1. Téléchargez le fichier `index.html`
2. Téléchargez le fichier audio `hasta_luego.mp3` (musique "Hasta Luego" de Hugues Aufray)
3. Placez les deux fichiers dans le même dossier

## 🎵 Configuration audio

**Important** : Le jeu nécessite un fichier audio pour fonctionner correctement.

1. Téléchargez ou obtenez la chanson "Hasta Luego" de Hugues Aufray
2. Convertissez-la en format MP3 si nécessaire
3. Renommez le fichier en `hasta_luego.mp3`
4. Placez-le dans le même dossier que `index.html`

Si vous n'avez pas le fichier audio, le jeu fonctionnera quand même, mais sans musique.

## 🚀 Lancement

Ouvrez simplement le fichier `index.html` dans votre navigateur web préféré :
- Double-cliquez sur le fichier
- Ou faites un clic droit → "Ouvrir avec" → Votre navigateur

**Navigateurs recommandés** : Chrome, Firefox, Edge, Safari

## 🎨 Style visuel

Le jeu adopte une esthétique **pixel art rétrogaming** avec :
- Une palette de couleurs marines et chaudes
- Des sprites pixelisés pour un effet nostalgique
- Un rendu crisp-edges pour préserver l'aspect rétro
- Des animations fluides malgré le style pixel art

## 🎪 Événement spécial

En terminant le jeu, vous découvrirez les détails d'un pot de départ :
- **Date** : Jeudi 6 novembre
- **Lieu** : À la cafèt
- **Suite** : Destination plus festive à suivre !

## 💻 Technologies utilisées

- HTML5 Canvas
- JavaScript Vanilla
- CSS3
- Web Audio API

## 📝 Notes techniques

- Résolution du canvas : 800x600 pixels
- 60 FPS
- 12 obstacles à éviter
- Durée approximative : 30-40 secondes par partie
- Auto-démarrage après 8 secondes sur l'écran d'accueil

## 🤝 Contribution

Ce jeu est un projet personnel pour un événement spécifique. Si vous souhaitez créer votre propre version, n'hésitez pas à forker le projet !

## 📜 Licence

Ce projet est à usage personnel et événementiel.

## 👏 Remerciements

- Hugues Aufray pour la chanson "Hasta Luego"
- L'équipe Harris pour 7 années incroyables
- Tous les marins d'eau douce qui tenteront leur chance !

---

**Bon vent et bonne navigation ! ⛵**

*"Hasta luego, hasta luego, je reviendrai..."*
