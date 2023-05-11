#GrandOral

## Les robots:

### _Exposer la problématique :
Un robot : KÉZAKO!?
Le préjugé : Non, c'est pas le truc machin qui fait bib bib ou qui parle métaliquement.
La réalité ou pas : 

On s'intéresse à un robot qui se déplace en autonomie.

En réalité le robot n'est autonome qu'après une programation particulière et entièrement prévue par les humains après de nombreux échecs.

Comment peut-on 

### _Notre besoin:
Placement automatique et guidé par le sol  des dominos. (Machine de Rube Goldberg)

### Solution(ou pas):
_ Le grand bloc non maniable.(différentiel)
_ La remorque (mieux)
_ Suivi de ligne (à développer)
_ système bielle manivelle
_ direction(programmation)

### Capteurs :
Capteurs de couleur/luminosité

L'appareil détecte l'intensité lumineuse (en fonction de différentes longueurs d'ondes pour le capteur de couleur.)

La valeur détectée est analogique puis convertie en numérique ce qui permet d'avoir la valeur d'intensité lumineuse du capteur ou la couleur moyenne.

Pour notre projet, nous avons choisi deux capteurs de luminosité car cela permet de suivre les deux limites de la ligne. Il serait aussi possible d'utiliser trois capteurs pour suivre les trois intensités sur et à côté de la ligne.

### Asservissement:
La valeur aura pour consigne un écart des deux valeurs nulle.
