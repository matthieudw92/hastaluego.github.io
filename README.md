# HastaLuego – Mini-Jeu Retro de Voile

**HastaLuego** est un mini-jeu d’arcade rétro où vous pilotez un petit voilier à travers des eaux semées d’embûches pour atteindre votre destination. Ce projet a été conçu comme un clin d’œil d’au revoir (*“Hasta Luego”* signifie *“À la prochaine”*) – le jeu contient un message final personnalisé pour une occasion de départ.

## Règles du jeu

- **Objectif :** Amener votre bateau à bon port sans accident. Il faut naviguer jusqu’au drapeau jaune marqué *“po(r)t de départ”* en haut de l’écran, en évitant ou en contournant tous les obstacles sur le chemin.
- **Obstacles :** 
  - Des **rochers bruns** apparaissent au milieu du passage. Si vous heurtez un rocher, votre bateau s’échoue (*“Tu t’es échoué !”*) et la partie est perdue.
  - Des **bouées rouges (carrées)** apparaissent sur le côté gauche du chenal. Ce sont des balises de **bâbord** – vous devez impérativement les laisser sur votre gauche en les contournant par la droite. Si vous passez du mauvais côté (entre la bouée rouge et le bord gauche de l’écran), vous échouez (*“on doit passer à droite des bouées bâbord rouges !”*).
  - Des **bouées vertes (triangulaires)** apparaissent sur le côté droit. Ce sont des balises de **tribord** – vous devez les laisser sur votre droite en les contournant par la gauche. Si vous tentez de passer à droite d’une bouée verte (entre la bouée et le bord droit), vous échouez (*“on doit passer à gauche des bouées tribord vertes !”*).
- **Durée :** Le parcours comporte 12 obstacles et dure environ 30 secondes si vous ne vous échouez pas. Après avoir franchi tous les obstacles, un drapeau jaune apparaît : rejoignez-le pour terminer la partie avec succès.

## Contrôles

- **Flèche gauche (←)** : Diriger le bateau vers la gauche.  
- **Flèche droite (→)** : Diriger le bateau vers la droite.  
- **Flèche haut (↑)** : Accélérer vers l’avant (utile uniquement à la fin pour atteindre le drapeau).  
- *(La flèche bas (↓) n’est pas utilisée dans ce jeu.)*  
- **Espace** : 
  - Depuis l’écran d’introduction, appuyer sur *Espace* lance la partie. 
  - Après un échec, appuyer sur *Espace* permet de redémarrer immédiatement (sinon le jeu redémarre automatiquement après quelques secondes).  

*Astuce :* Vous pouvez aussi simplement attendre ~8 secondes sur l’écran d’intro pour que la partie démarre automatiquement (avec la musique).

## Style et Graphismes

- Le jeu adopte un style **pixel art rétro**. Tous les textes sont affichés dans une police pixelisée (type arcade des années 80). Les éléments du jeu (bateau, rochers, bouées, drapeau) sont représentés par des formes simples et colorées pour rappeler le pixel art. 
- **Bateau :** petit triangle blanc (la voile) avec une base brune (la coque).  
- **Rochers :** disques bruns.  
- **Bouées rouges :** carrés rouges.  
- **Bouées vertes :** triangles verts.  
- **Drapeau d’arrivée :** texte jaune *“po(r)t de départ”* affiché avec une petite icône de drapeau.  

*Remarque :* Ces graphismes sont des **sprites provisoires**. Vous pouvez les remplacer par de véritables images pixel art pour plus d’esthétique. Par exemple, utiliser une image PNG pour le bateau et les obstacles. Veillez alors à ajuster les dimensions dans le code si nécessaire pour correspondre à la taille des sprites.

## Musique

La chanson **“Hasta Luego” d’Hugues Aufray** accompagne le jeu et joue en boucle pendant la partie. Pour des raisons de copyright, le fichier audio n’est pas inclus dans ce dépôt. Vous pouvez ajouter le fichier MP3 dans le dossier du projet (et mettre à jour le chemin dans le code HTML `<audio src="...">`). La musique démarre lorsque le jeu commence (après une interaction de l’utilisateur, conformément aux politiques des navigateurs).

## Lancer le jeu

Aucun prérequis particulier n’est nécessaire. Il suffit d’ouvrir le fichier `index.html` dans un navigateur web moderne :

- Téléchargez les fichiers du projet (**index.html** et ce **README.md**, ainsi que les assets que vous ajouterez).
- Ajoutez les fichiers de **sprites** (images PNG/GIF pour le bateau, les rochers, les bouées, etc.) et le fichier de **musique** dans un sous-dossier (par exemple `assets/` ou `music/`) et ajustez les chemins dans `index.html` si besoin. Par exemple, mettez votre `HastaLuego.mp3` dans un dossier `music/` et vérifiez que la balise `<audio>` pointe vers `music/HastaLuego.mp3`.
- Ouvrez `index.html` avec votre navigateur (double-cliquez le fichier, ou lancez un petit serveur local et accédez-y). Assurez-vous que le navigateur autorise le son – il faudra cliquer sur la page ou appuyer sur Espace pour que la musique démarre.
- Vous verrez l’écran d’accueil *Hasta Luego* avec les instructions. Appuyez sur **Espace** pour commencer à jouer.

Le jeu peut également être hébergé sur **GitHub Pages** ou un autre hébergeur statique. Il vous suffit de publier le contenu du projet (y compris les assets ajoutés) et d’accéder à la page `index.html` via l’URL GitHub Pages. Le jeu étant en JavaScript pur côté client, il fonctionnera tant que tous les fichiers (HTML, CSS, JS, images, audio) sont correctement servis.

## À propos du projet

Ce mini-jeu a été créé pour une occasion spéciale de départ, d’où son nom *HastaLuego*. N’hésitez pas à forker le projet et à le modifier pour vos propres événements ou juste pour le plaisir d’améliorer le gameplay et les graphismes. Amusez-vous bien, et bon vent au capitaine qui quitte le navire ! ⛵
