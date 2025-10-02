# 🚢 HastaLuego - Jusqu'au port de départ

Un mini-jeu de navigation maritime en pixel art pour célébrer un départ après 7 ans d'aventure !

## 🎮 Comment jouer

### Objectif
Navigue avec ton voilier à travers 12 obstacles pour atteindre le port de départ !

### Contrôles
- **Flèches directionnelles ←→** : Diriger le bateau
- **ESPACE** : Lancer le jeu

### Règles de navigation
Évite trois types d'obstacles :

1. **🪨 Rochers (marron)** : Ne les percute pas ! Passe à droite ou à gauche
2. **🟥 Bouées rouges (carrées)** : Passe TOUJOURS à droite (règle bâbord)
3. **🟩 Bouées vertes (triangulaires)** : Passe TOUJOURS à gauche (règle tribord)

### Conditions de défaite
- Collision avec un rocher → "Tu t'es échoué ! Tu dois sûrement être un quanti…"
- Passer à gauche d'une bouée rouge → "On doit passer à droite des bouées bâbord rouges ! Marin d'eau douce !"
- Passer à droite d'une bouée verte → "On doit passer à gauche des bouées tribord vertes ! Même Fred !"

## 🎵 Musique

Le jeu nécessite le fichier audio `hasta_luego.mp3` (chanson "Hasta Luego" de Hugues Aufray) à placer à la racine du projet.

## 🛠️ Installation

1. Clone ce repository :
```bash
git clone https://github.com/[username]/HastaLuego.git
cd HastaLuego
```

2. Ajoute le fichier audio :
   - Place `hasta_luego.mp3` à la racine du projet

3. Lance le jeu :
   - Ouvre `index.html` dans ton navigateur
   - Ou utilise un serveur local (recommandé pour la musique)

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (npx http-server)
npx http-server
```

4. Accède au jeu sur `http://localhost:8000`

## 📁 Structure du projet

```
HastaLuego/
│
├── index.html          # Le jeu complet
├── hasta_luego.mp3     # Fichier audio (à ajouter)
└── README.md           # Ce fichier
```

## 🎨 Style

Jeu en pixel art rétrogaming avec :
- Mer animée avec vagues
- Obstacles en pixel art
- Voilier simple et maniable
- Bannières de texte pixelisées
- Esthétique années 80-90

## 🏆 Message de victoire

Après avoir évité 12 obstacles, tu atteindras le port de départ et découvriras l'invitation pour le pot de départ le **jeudi 6 novembre** à la cafèt !

## 🎯 Durée de jeu

Environ 30 secondes pour une partie complète (sans collision).

## 💡 Conseils

- Anticipe les obstacles : ils apparaissent en haut de l'écran
- Les rochers sont au centre, les bouées sur les côtés
- Mémorise la règle : Rouge à Droite, Vert à Gauche (RDVg)
- Reste concentré jusqu'au bout !

## 🐛 Dépannage

**La musique ne se lance pas :**
- Vérifie que `hasta_luego.mp3` est bien présent
- Certains navigateurs bloquent l'autoplay : clique sur la page pour lancer la musique
- Utilise un serveur local plutôt que d'ouvrir directement le fichier HTML

**Le jeu est trop rapide/lent :**
- Modifie les valeurs `boat.speed` et `obs.y += 3` dans le code

## 📝 Licence

Projet personnel pour un pot de départ. Code libre d'utilisation.

## 🙏 Crédits

- Musique : "Hasta Luego" - Hugues Aufray
- Concept et développement : [Ton nom]
- Inspiré par l'esprit de la navigation et de l'aventure

---

*Bon vent matelot ! ⛵*
