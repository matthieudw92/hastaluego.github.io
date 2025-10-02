# HastaLuego – Mini jeu navigateur rétro

## Présentation
**HastaLuego** est un mini-jeu web en style pixel art rétro, jouable sur un navigateur desktop. Le joueur y dirige un petit voilier afin de le mener à bon port en évitant les obstacles et en respectant les règles de navigation. Ce projet a été réalisé sans framework, uniquement avec du HTML, CSS et JavaScript pur, dans un but ludique et pédagogique.

Ce jeu a également une dimension événementielle : il sert de faire-valoir à une invitation pour un pot de départ, d’où le clin d’œil maritime et le message final intégrés au gameplay.

## Gameplay et règles du jeu
Au lancement du jeu, un écran d’introduction affiche les instructions _« à l’aide des touches directionnelles, emmène ton bateau à bon port ! »_ ainsi que l’indication _« ESPACE pour commencer »_. La musique *“Hasta Luego”* de Hugues Aufray démarre automatiquement et joue en boucle en fond sonore.

Une fois la partie lancée (après avoir appuyé sur **Espace** ou automatiquement au bout de 8 secondes), le bateau du joueur apparaît sur une mer pixellisée vue du dessus. Le décor marin défile vers le bas pour simuler l’avancée du bateau vers le haut de l’écran. Le voilier est initialement centré horizontalement et situé au tiers inférieur de l’écran.

**Obstacles :** Au cours de la navigation, 12 obstacles apparaissent progressivement sur le trajet. Il existe trois types d’obstacles qu’il faut négocier de la manière suivante :

- **Rochers (4)** : de gros cailloux marron émergent dans la zone centrale du parcours (environ 25 % à 75 % de la largeur). Si le bateau entre en collision avec un rocher, la partie est perdue ; un message s’affiche (*« Tu t’es échoué ! Tu dois sûrement être un quanti… »*) et le jeu redémarre depuis le début.
- **Bouées rouges carrées (4)** : elles délimitent le côté bâbord (gauche) du chenal et apparaissent plutôt sur la partie gauche du plan d’eau (env. 30 % à 55 % de la largeur). Le joueur doit passer **à droite** de ces bouées (c’est-à-dire garder la bouée rouge sur la gauche du bateau). Si le bateau passe du **mauvais côté** d’une bouée rouge (à sa gauche, entre la bouée et le bord gauche de l’écran), un message d’échec s’affiche (*« On doit passer à droite des bouées bâbord rouges ! Marin d’eau douce ! »*) et le jeu redémarre.
- **Bouées vertes triangulaires (4)** : elles marquent le côté tribord (droit) du chenal et sont placées plutôt sur la partie droite (env. 45 % à 70 % de la largeur). Il faut passer **à gauche** de ces bouées vertes (les garder sur la droite du bateau). Si le bateau passe du mauvais côté d’une bouée verte (à sa droite, c’est-à-dire entre la bouée et le bord droit de l’écran), un message d’échec apparaît (*« On doit passer à gauche des bouées tribord vertes ! Même Fred ! »*) et la partie redémarre.

Après avoir surmonté les 12 obstacles, le bateau pourra avancer librement jusqu’à apercevoir un **drapeau d’arrivée** jaune arborant le texte *« po(r)t de départ »*. C’est le port qu’il fallait atteindre ! Lorsque le voilier atteint ce drapeau final, c’est la **victoire** : le jeu affiche un écran de félicitations. Le message final invite les joueurs au pot de départ (dans le contexte réel du projet) en affichant :

> *« Bien joué !  
> Après 7 ans dans le même bateau, je vais changer d’équipage et quitter Harris pour une autre aventure.  
> Tu as prouvé ta valeur aujourd’hui ; je t’invite à rejoindre de la même façon mon pot de départ le **jeudi 6 novembre**, à la cafèt, avant de se déhaler vers une autre destination plus festive ! »*

*Remarque :* le texte **jeudi 6 novembre** est mis en évidence dans ce message final afin de marquer la date de l’événement.

En cas de victoire, la musique s’arrête et le jeu reste sur l’écran final jusqu’à ce que l’utilisateur le ferme ou le redémarre manuellement (par exemple en rechargeant la page). En cas d’échec à cause d’un obstacle, le jeu redémarre automatiquement après quelques secondes en ré-affichant l’écran d’introduction (il est possible d’appuyer sur Espace immédiatement pour relancer plus vite la partie).

## Contrôles
- **Flèche gauche / droite** : Déplacer le bateau latéralement vers la gauche ou la droite.
- **Flèche haut** : Faire avancer/accélérer le bateau vers l’avant.
- **Barre d’espace** : Lancer la partie (depuis l’écran d’intro). Après un échec, permet également de recommencer immédiatement (sans attendre le démarrage automatique).

**Remarque :** Le jeu est conçu pour un contrôle au clavier sur ordinateur. Il n’est pas optimisé pour les écrans tactiles ou l’utilisation sur mobile.

## Installation et lancement
1. Assurez-vous d’avoir un navigateur web moderne sur un ordinateur de bureau (Chrome, Firefox, Edge, etc.).
2. Placez le fichier audio **`assets_Hugues Aufray - Hasta Luego.mp3`** dans le même répertoire que le fichier `index.html` du jeu (ou adaptez le chemin dans le code HTML si nécessaire). Ce fichier contient la musique de fond.
3. Ouvrez le fichier `index.html` dans votre navigateur. L’écran d’introduction du jeu devrait apparaître, avec la musique jouant en arrière-plan.
4. Appuyez sur **Espace** pour commencer la partie (ou patientez 8 secondes pour un démarrage automatique).

Si le jeu est ouvert depuis un fichier local, il est possible que le navigateur bloque la lecture automatique de la musique pour des raisons de sécurité. Dans ce cas, appuyez sur **Espace** ou interagissez avec la page pour déclencher la lecture audio. Veillez également à ce que le volume de votre ordinateur soit adéquat pour profiter de la chanson.

## Réalisation technique
- **Technologies utilisées :** HTML5, CSS3 et JavaScript. Le jeu utilise un canevas `<canvas>` HTML5 pour le rendu des graphismes et des animations. Aucune librairie ni moteur tiers n’est requis, tout est codé “from scratch”.
- **Graphismes pixel-art :** Les éléments visuels (bateau, vagues, rochers, bouées, drapeau) sont dessinés directement via le canvas en utilisant des formes simples (rectangles, triangles) pour reproduire une esthétique rétro pixelisée. Par exemple, le voilier est composé d’un rectangle pour la coque et d’un triangle pour la voile ; les rochers sont des blocs marron avec quelques pixels plus clairs pour simuler la texture, etc. Le fond marin est animé avec un motif de vagues simplifié (bandes de pixels plus clairs se déplaçant pour simuler le mouvement de l’eau).
- **Musique :** La musique de fond est intégrée à l’aide d’un élément `<audio>` HTML en boucle. Elle se lance au début de la partie (juste après l’écran d’intro). Aucun autre effet sonore n’est inclus, afin de rester focalisé sur la musique et l’aspect rétro.
- **Structure du code :** Tout le code HTML, CSS et JS est regroupé dans le fichier `index.html` pour faciliter la portabilité. Des commentaires en français sont présents dans le code source pour expliquer les différentes sections (initialisation, boucle de jeu, dessin des éléments, gestion des collisions, etc.). Le JavaScript est organisé en plusieurs fonctions (par exemple `initGame()`, `gameLoop()`, `drawBoat()`, etc.) pour clarifier les étapes du fonctionnement du jeu. Une variable d’état gère la progression (écran d’intro, partie en cours, victoire/échec).
- **Accessibilité :** Le jeu étant une expérience ludique visuelle et sonore, il n’est pleinement accessible qu’aux utilisateurs pouvant voir les graphismes et entendre la musique. Il n’y a pas de mode alternatif texte ou son. La navigation se fait au clavier, et le jeu est prévu pour un écran d’ordinateur (pas d’adaptation mobile).

## Crédits
- **Musique :** *“Hasta Luego”* – Hugues Aufray (1966). Merci à cette chanson iconique de donner son ambiance marine au jeu.
- **Police de caractères :** *“Press Start 2P”* par CodeMan38 (disponible via Google Fonts), qui offre le style pixel art rétro pour les textes à l’écran.
- **Idée et réalisation :** Ce mini-jeu a été conçu dans un contexte professionnel (pot de départ) pour une touche d’originalité. Code et graphismes par **[Votre Nom]**, en hommage aux jeux d’arcade des années 80 et aux aventures maritimes.
