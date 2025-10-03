# HastaLuego 🚢

Un mini-jeu de navigation maritime en pixel art pour célébrer un départ après 7 ans d'aventure chez Harris !

## 🎮 Description du jeu

**HastaLuego** est un jeu de navigation où vous devez guider un petit voilier à travers les obstacles maritimes pour rejoindre le port de départ. Inspiré par l'esprit marin et la chanson d'Hugues Aufray, ce jeu est une invitation ludique à un pot de départ.

## 🕹️ Comment jouer

### Contrôles
- **Touches directionnelles** : Déplacer le bateau (gauche/droite/haut/bas)
- **Barre ESPACE** : Lancer le jeu

### Objectif
Naviguer à travers 12 obstacles pour atteindre le port de départ en évitant :
- **Rochers** (marrons) : À éviter complètement
- **Bouées rouges** (carrées) : Passer à droite (règles de navigation bâbord)
- **Bouées vertes** (triangulaires) : Passer à gauche (règles de navigation tribord)

### Règles de navigation
- Les bouées rouges (bâbord) doivent être laissées à gauche - passez à droite !
- Les bouées vertes (tribord) doivent être laissées à droite - passez à gauche !
- Les rochers doivent être évités complètement
- Après 12 obstacles, rejoignez le drapeau jaune "PO(R)T DE DÉPART"

## 🚀 Installation

1. Clonez ce repository :
```bash
git clone https://github.com/[votre-username]/HastaLuego.git
```

2. Ajoutez le fichier audio `hasta-luego.mp3` (la chanson "Hasta Luego" d'Hugues Aufray) à la racine du projet

3. Ouvrez `index.html` dans votre navigateur

## 📁 Structure du projet

```
HastaLuego/
│
├── index.html          # Fichier principal du jeu
├── README.md          # Documentation
└── hasta-luego.mp3    # Musique de fond (à ajouter)
```

## 🎨 Caractéristiques

- **Style pixel art** rétro gaming
- **Musique d'ambiance** : "Hasta Luego" d'Hugues Aufray en boucle
- **Physique maritime** simplifiée
- **Messages d'erreur** humoristiques en cas de collision
- **Animation des vagues** pour un effet mer dynamique
- **Système de progression** avec compteur d'obstacles

## 🛠️ Technologies utilisées

- HTML5 Canvas pour le rendu
- JavaScript vanilla pour la logique du jeu
- CSS3 pour le style des bannières
- Police "Press Start 2P" pour l'ambiance rétro

## 📝 Notes de développement

### Collisions
- Les rochers ont une zone de collision directe
- Les bouées ont une zone de passage obligatoire selon leur couleur
- La détection se fait en temps réel à chaque frame

### Performance
- Animation à 60 FPS via requestAnimationFrame
- Rendu optimisé avec canvas 2D
- Nombre d'obstacles limité à l'écran pour maintenir la fluidité

## 🎯 Améliorations futures possibles

- [ ] Ajout d'effets sonores (collision, victoire)
- [ ] Système de score basé sur le temps
- [ ] Niveaux de difficulté
- [ ] Effets visuels supplémentaires (éclaboussures, traînée)
- [ ] Mode multijoueur local
- [ ] Sauvegarde des meilleurs scores

## 🎉 Message spécial

Ce jeu a été créé pour célébrer un départ après 7 ans chez Harris. Il constitue une invitation originale et ludique au pot de départ du **jeudi 6 novembre** à la cafétéria.

*"Après 7 ans dans le même bateau, il est temps de changer d'équipage et de naviguer vers de nouvelles aventures !"*

## 📜 Licence

Ce projet est créé dans un but festif et amical. Libre d'utilisation et de modification pour des événements similaires !

## 🤝 Remerciements

- Hugues Aufray pour la musique inspirante
- L'équipe Harris pour ces 7 années de navigation commune
- Tous les marins d'eau douce qui tenteront l'aventure !

---

**Bon vent et bonne navigation !** ⛵

*PS : Les vrais marins savent qu'on ne dit jamais "corde" sur un bateau... c'est un bout !*
