On cherche à démontrer pourquoi $S_{disque} = πr_{disque}^2$ .

On sait que l'équation cartésienne du cercle est :
$x^2 + y^2 = 2\sqrt{r_{disque}}$ 
Et donc que l'équation demi cercle défine sur $[-r_{disque};r_{disque}]$ est $y = \sqrt{2\sqrt{r_{disque}}-x^2}$ 

On sait aussi que $cos^{-1}(x) = α$ et donc que l'équation $y = r_{disque}\times sin(cos^{-1}(x))$ est aussi l'équation demi cercle définie sur $[-r_{disque};r_{disque}]$.

On a donc la fonction $f(x) = \sqrt{2\sqrt{r_{disque}}-x^2} = r_{disque} \times sin(cos^{-1}(x))\geq0$.

On sait aussi que la surface d'une fonction entre sa courbe et l'axe des abscisses est son intégrale :
Ici $2\int_{-r}^{r}f(x)dx = S_{disque}$

En supposant que $S_{disque} = πr^2$:
$\int_{-r}^{r}f(x)dx = \frac{1}{2} πr^2$

$\int_{-r}^{r}f(x)dx = []