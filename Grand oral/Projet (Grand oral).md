#GrandOral

## Les robots:

### _Exposer la problématique :
Un robot : KÉZAKO!?
Le préjugé : Non, c'est pas le truc machin qui fait bib bib ou qui parle métaliquement.

### _Notre besoin:
Placement automatique et guidé par le sol  des dominos. (Machine de Rube Goldberg)

Il faut un système capable de rendre autonome le déplacement du robot en fonction du tracé de la route.

### Capteurs :
Capteurs de couleur/luminosité

L'appareil détecte l'intensité lumineuse (en fonction de différentes longueurs d'ondes pour le capteur de couleur.)

L'effet photoélectrique peut être utilisé pour mesurer la lumière réfléchie ou émise par l'environnement.

La valeur détectée est analogique puis convertie en numérique ce qui permet d'avoir la valeur d'intensité lumineuse du capteur ou la couleur moyenne.

Pour notre projet, nous avons choisi deux capteurs de luminosité car cela permet de suivre les deux limites d'une ligne noire sur blanc.
Il serait aussi possible d'utiliser trois capteurs pour suivre les trois intensités sur et à côté de la ligne.

### Asservissement:

Le but de l'asservissement est qu' il faut en permanence que le système puisse vérifier si les actions correspondent à la consigne car il peut ya avoir un changement de la consigne ou un facteur extérieur. Par exemple, si notre robot détecte un déséquilibre entre la luminosité des deux capteur, il faudra effectuer un changement de direction des roues. Sinon, le robot rencontre une bosse et qu'il est dévié, il devra se remettre imédiatement sur la bonne direction.

Pour ce faire il y a plusieurs moyens de résoudre le problème.

La première idée est une action proportionelle à l'écart de la consigne.
Imaginons que la différence entre le capteur de droite et celui de gauche est de -30% de luminosité par rapport à la luminosité maximale, le système devra effectuer une action de $k \times 0,3α$ vers la  avec $α$ en t