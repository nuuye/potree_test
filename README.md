# Explications :

Dans un premier temps, j'ai essayé de comprendre le projet étant donné le nombre important de fichiers.

Ensuite, j'ai localisé l'endroit où la largeur de la barre latérale était définie. Afin de rendre cette dernière dynamique en termes de largeur, j'ai envisagé de suivre les mouvements de la souris de l'utilisateur, de détecter quand il cliquait et relâchait le bouton.

Pour ce faire, j'ai utilisé la méthode .on() pour gérer les évenements 'mousemove' et 'mousedown' afin de recueillir ces informations, puis j'ai ajusté dynamiquement la largeur en fonction de l'abscisse X de la page.