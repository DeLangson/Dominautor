[Le site qui explique](https://www.mathweb.fr/euclide/2020/10/10/pourquoi-le-volume-dune-sphere-est-egal-a-frac43pi-r3-explications-avec-les-integrales/)
[Le site qui explique](https://www.mathweb.fr/euclide/2019/05/18/pourquoi-laire-dun-disque-est-egale-a-pi-r2/)

On cherche à démontrer pourquoi $S_{disque} = πR_{disque}^2$ .

On sait par Pytagore que : $y = \sqrt{R^2-x^2}$ ce qui nous donne $f(x) = \sqrt{R^2-x^2}$.
La surface du disque est donc $S = \int_0^r \sqrt{R^2-x^2} dx$:

On cherche la primitive de $\sqrt{R^2-x^2}$ mais il n'y en a pas donc il faut poser: $x = R sin(θ)$ car nous savons que x st compris entre $0$ et $R$ ce qui signifie que $R sin(θ)$ est compris entre $0$ et $R$.
Aussi $dx = R cos(θ)$.

$S = \int_0^{\frac{π}{2}} \sqrt{R^2-(R sin(θ))^2} R  cos(θ)dθ$
$S = \int_0^{\frac{π}{2}} \sqrt{R^2(1-sin^2(θ))} R cos(θ)dθ$
$S = R\int_0^{\frac{π}{2}} \sqrt{1-sin^2(θ)} R cos(θ)dθ$
$S = R^2\int_0^{\frac{π}{2}} \sqrt{1-sin^2(θ)} cos(θ)dθ$
On sait que $cos^2(θ) + sin^2(θ) = 1$ et donc que $cos(θ) = \sqrt{1-sin(θ)}$ :
$S = R^2\int_0^{\frac{π}{2}} cos(θ)dθ$
