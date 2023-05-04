On cherche à démontrer pourquoi $S_{disque} = πr_{disque}^2$ .

On sait que l'équation cartésienne du cercle est :
$x^2 + y^2 = r_{disque}^2$ 
Et donc que l'équation demi cercle défine sur $[-r_{disque};r_{disque}]$ est $y = \sqrt{r_{disque}^2-x^2}$ 

On sait aussi que $cos^{-1}(\frac{x}{r_{disque}}) = α$ et donc que l'équation $y = r_{disque}\times sin(cos^{-1}(\frac{x}{r_{disque}}))$ est aussi l'équation demi cercle définie sur $[-r_{disque};r_{disque}]$.

On a donc la fonction $f(x) = \sqrt{r_{disque}^2-x^2} = r_{disque} \times sin(cos^{-1}(\frac{x}{r_{disque}}))\geq0$.

On sait que $f(0) = r$ donc $\int_{r}^{0} f(x) dx = F(0)-F(r)$ 

$f(x)=\frac{u'}{2\sqrt{u}}$ ; $F(x)=\sqrt{u}$ 

$\frac{u'}{2\sqrt{u}} = \sqrt{r_{disque}^2-x^2}$ 