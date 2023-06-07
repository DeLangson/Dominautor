Le cercle et la sphère, c'est intriguant, c'est pas non plus très pratique à mesurer.
Un disque ou une sphère, c'est pas comme un rectangle ou un bloc qu'on peut mesurer avec une règle.

On sait que les collégiens apprennent comment on calcule la surface du disque et le volume de la sphère :
$S = πr^2$ ; $V = \frac{4}{3}πr^3$ 

On nous les a données comme ça sans nous expliquer comment.
En fait le but de nous les donner, c'était juste pour qu'on puisse les utiliser, les appliquer.

Évidement, quelqu'un les a trouvées ces formules.

Le plus intéressant dans les mathématiques c'est la démonstration (du moins pour moi).

Alors comment peut-on expliquer comment démontrer ces formules?

Nous avons commencé cette année a parler de ce qu'on appelle l'intégration.
Ça consiste a faire la somme infinitésimale des parties d'un domaine défini par une ou plusieurs variables.

Pour faire plus clair, c'est comme si on découpait un domaine en parties infiniment petites et qu'on en faisait la somme. Et là c'est tout d'un coup plus pratique pour la mesure des formes qu'on arrive pas à comprendre : comme le disque par exemple.

Dans le cas du disque, on peut par exemple, faire l'intégrale de la fonction $f(x) = \sqrt{R^2-x^2}$ qui fait un demi cercle:

*Montrer le support* : avec le graphique sur la feuille.

Il suffit de faire la somme des surfaces infiniment petites de longueur $f(x)$ et de largeur $dx$, une partie infiniment petite du diamètre du cercle.

*Sur la feuille* : Sur le papier ça se note comme ça :
$S = 4\int_{0}^{R} \sqrt{R^2-x^2}dx$

Nous avons vu en cours que pour le calculer, il faut déterminer la primitive de $\sqrt{R^2-x^2}$.
Le problème c'est qu'il n'existe pas de formule de primitive qui permette de calculer cette intégrale.

Mais il existe une autre méthode :

En utilisant les coordonnées polaires, on a un point dans l'espace sur un cercle de rayon $r$ et d'angle $θ$ au lieu de $x$ et $y$ en coordonnées cartésiennes.

Cela semble bien plus facile à comprendre dans un repère adapté à la forme du cercle.

Nous allons donc faire la somme de toutes les variation d'angles fois le rayon $rdθ$ fois la somme de toutes les variations de longueur du rayon, $dr$.

*Montrer le schéma.

Cela nous donne : $S = \int_0^R\int_0^{2π} rdθdr$.

En faisant le calcul de primitive on obtient bien:

$S = \int_0^R[θr]_0^{2π}dr$
$S = \int_0^R2πrdr$ 
$S = [πr^2]_0^R$
$S = πR^2$ 

On retrouve donc bien la formule $S = πr^2$.

Maintenant que nous avons la surface du disque, on peut l'utiliser pour démontrer le volume d'une sphère.

Si on décompose le volume comme la somme de tous les cylindres de hauteur $dz$ suffisamment petite et de rayon $r$ variant sur l'intervalle $[-R;R]$ on peut encore faire une intégrale pour le calculer.

Le volume du cylindre se calcule de la manière suivante : $V = πr^2 dz$.

*Montrer le schéma*

D'après le théorème de Pytagore : $R^2 = r^2 + z^2$ donc $r^2 = R^2 - z^2$ 