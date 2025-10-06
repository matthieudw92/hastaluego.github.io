# ⛵ HastaLuego - Mini-jeu de Navigation

Un mini-jeu rétro pixel art créé pour célébrer un départ après 7 années d'aventures chez Harris Interactive.

## 🎮 Description

Naviguez à travers une mer parsemée d'obstacles pour atteindre votre nouveau port ! Ce jeu nostalgique de style pixel art vous met aux commandes d'un petit voilier qui doit éviter des rochers pour rejoindre sa destination finale.

## 🕹️ Comment jouer

### Contrôles
- **Touches directionnelles** (↑ ↓ ← →) : Déplacer le bateau
- **ESPACE** : Lancer le jeu / Réessayer après un crash

### Objectif
- Évitez les 12 rochers qui apparaissent sur votre route
- Naviguez prudemment entre les obstacles
- Atteignez le drapeau jaune du "po(r)t de départ"
- Ne vous échouez pas sur les rochers !

## 🎵 Musique

Le jeu est accompagné de la chanson **"Hasta Luego"** d'Hugues Aufray qui se joue en boucle.

### Installation de la musique
Pour que la musique fonctionne, placez votre fichier audio dans le même répertoire que `index.html` et nommez-le :
- `hasta_luego.mp3`

Si vous utilisez un autre format ou nom de fichier, modifiez cette ligne dans le code HTML :
```html
<source src="hasta_luego.mp3" type="audio/mpeg">
```

## 📁 Installation

1. Clonez ce repository :
```bash
git clone https://github.com/votre-username/HastaLuego.git
cd HastaLuego
```

2. Ajoutez le fichier audio `hasta_luego.mp3` dans le dossier

3. Ouvrez `index.html` dans votre navigateur web

C'est tout ! Aucune installation supplémentaire nécessaire.

## 🎨 Style visuel

- **Thème** : Pixel art rétrogaming
- **Palette de couleurs** : Tons bleus océaniques, marrons pour les rochers, jaune doré pour le drapeau
- **Inspiration** : Jeux d'arcade des années 80-90

## 🏆 Scénario du jeu

Après 7 années passées dans le même bateau chez Harris, il est temps de larguer les amarres vers de nouvelles aventures. Ce mini-jeu célèbre ce départ et invite tous ceux qui réussissent à naviguer jusqu'au bout à rejoindre le pot de départ :

**📅 Jeudi 6 novembre**  
**📍 À la cafèt**  
Puis direction vers une destination plus festive !

## 🛠️ Technologies utilisées

- HTML5 Canvas pour le rendu graphique
- JavaScript vanilla (pas de framework)
- CSS3 pour le style des bannières
- API Web Audio pour la musique

## 📝 Structure du projet

```
HastaLuego/
│
├── index.html          # Fichier principal du jeu (HTML + CSS + JavaScript)
├── README.md          # Ce fichier
└── hasta_luego.mp3    # Fichier audio (à ajouter)
```

## 🎯 Fonctionnalités

- ✅ Démarrage automatique après 8 secondes ou manuel avec ESPACE
- ✅ Musique de fond en boucle
- ✅ Génération procédurale d'obstacles
- ✅ Détection de collision pixel-perfect
- ✅ Animation de l'eau avec effet de vagues
- ✅ Système de scoring (obstacles évités)
- ✅ Bannières d'information stylisées
- ✅ Responsive design adapté aux différentes tailles d'écran

## 🐛 Dépannage

**La musique ne se lance pas ?**
- Vérifiez que le fichier `hasta_luego.mp3` est présent dans le même dossier
- Certains navigateurs bloquent l'autoplay audio : cliquez dans la page avant le démarrage
- Essayez avec un autre navigateur (Chrome, Firefox, Safari)

**Le jeu est trop rapide/lent ?**
- Modifiez la variable `scrollSpeed` (ligne ~95 du code) pour ajuster la vitesse
- Modifiez `player.speed` (ligne ~86) pour ajuster la vitesse du bateau

## 🤝 Contribution

Ce jeu a été créé spécialement pour un événement unique, mais n'hésitez pas à le forker et l'adapter pour vos propres occasions !

## 📜 Licence

Libre d'utilisation pour usage personnel et non commercial.

## 👋 À propos

Créé avec ❤️ pour célébrer 7 années formidables et un nouveau départ vers l'aventure !

---

**Hasta luego, amigos ! ⛵🌊**
