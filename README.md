Je voudrais que tu crée le code d’un mini-jeu selon la description suivante, que je puisse ensuite copier-coller les fichiers dans les fichiers github.
Il me faut d’une part le code index.html du jeu, et d’autre part le fichier readme.md.
 
Concept du gameplay :
Le jeu s’ouvre automatiquement avec un panneau indiquant « à l’aide des touches directionnelles, emmène ton bateau à bon port ! » puis « ESPACE pour commencer ». En même temps, la piste musicale de la chanson « hasta luego » de Hugues Auffray se lance (asset chargé ultérieurement dans github), et est jouée en boucle jusqu'à la fin du jeu. Le jeu se lance dès que le joueur enfonce sa barre « espace », ou au bout de 8 secondes s’il ne fait rien. Puis la bannière s’efface et laisse apparaitre l’arrière-plan qui est une mer avec quelques vagues. 
Au centre un bateau (un petit voilier sommaire), que le joueur dirige avec les touches directionnelles. L’arrière-plan défile pour donner l’impression que le bateau avance vers le haut (mais le bateau est en réalité statique sur la page, au centre sur l’axe gauche-droite et sur le premier tiers en partant du bas). Le bateau doit avancer sur la mer, vers le haut de l’écran donc. 
Des obstacles apparaissent de temps en temps, que le bateau contrôlé par le joueur doit éviter. Ils sont de trois types : 
1)      Des rochers représentés par des cailloux marrons. Ils apparaissent plutôt au centre de l’écran (25%-75% largeur). Le bateau doit les éviter en passant à droite ou à gauche. Il y a collision si le bateau passe sur un rocher. Dans ce cas, une bannière affiche « Tu t’es échoué ! Tu dois sûrement être un quanti… » et le jeu reprend du début.
2)      Des bouées rouges carrées. Elles apparaissent dans la partie gauche de l’écran, 30-55% largeur) que le bateau doit éviter en passant à droite.  Il y a collision si le bateau passe à gauche de la bouée (0%-bouée largeur). Dans ce cas, une bannière affiche « on doit passer à droite des bouées bâbord rouges ! Marin d’eau douce ! » et le jeu reprend du début.
3)      Des bouées vertes triangulaires. Elles apparaissent dans la partie droite de l’écran, 45%-70% largeur) que le bateau doit éviter en passant à gauche.  Il y a collision si le bateau passe à droite de la bouée (bouée-0% largeur). Dans ce cas, une bannière affiche « on doit passer à gauche des bouées tribord vertes ! Même Fred ! » et le jeu reprend du début.
Au bout de 12 obstacles, soit une trentaine de secondes de jeu maximum, le bateau poursuit sa route vers le haut de l’écran (et n’est donc plus statique au centre) pour rejoindre un petit drapeau jaune au-dessus duquel il est écrit « po(r)t de départ ».
Lorsque le bateau arrive sur ce drapeau, le jeu s’arrête et un panneau s’affiche avec le texte suivant :
« Bien joué !
Après 7 ans dans le même bateau, je vais changer d’équipage et quitter Harris pour une autre aventure.
Tu as prouvé ta valeur aujourd’hui ; je t’invite à rejoindre de la même façon mon pot de départ le jeudi 6 novembre, à la cafèt, avant de se déhaler vers une autre destination plus festive ! »
Les mots « jeudi 6 novembre » doivent être accentués, par une couleur ou une typographie spécifique.
 
Contrôles : flèches directionnelles (pour faire avancer le bateau), barre espace (pour lancer le jeu).
Style : pixel art, rétrogaming, couleurs. Voir photo jointe pour référence / inspiration.
Nom du jeu et nom du repo : HastaLuego

Je veux absolument les deux codes prêts à être copiés-collés : 
1) le code index.html
2) le code readme.md
