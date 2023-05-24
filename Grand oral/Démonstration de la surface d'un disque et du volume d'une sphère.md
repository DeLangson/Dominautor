[Le site qui explique](https://www.mathweb.fr/euclide/2019/05/18/pourquoi-laire-dun-disque-est-egale-a-pi-r2/)
[Le site qui explique](https://www.mathweb.fr/euclide/2020/10/10/pourquoi-le-volume-dune-sphere-est-egal-a-frac43pi-r3-explications-avec-les-integrales/)

## On cherche à démontrer pourquoi $S_{disque} = πR_{disque}^2$

On sait par Pytagore que : $y = \sqrt{R^2-x^2}$ ce qui nous donne $f(x) = \sqrt{R^2-x^2}$.
La surface du disque est donc $S = \int_0^r \sqrt{R^2-x^2} dx$:

On cherche la primitive de $\sqrt{R^2-x^2}$ mais il n'y a pas de formule qui coresponde donc il faut poser: $x = R cos(θ)$ en passant des coordonnées cartésiennes aux coordonnées polaires.
Donc $dx = R sin(θ)d(θ)$

$S = 4\int_0^{\frac{π}{2}} \sqrt{R^2-(R cos(θ))^2} R  sin(θ)dθ$
$S = 4\int_0^{\frac{π}{2}} \sqrt{R^2(1-cos^2(θ))} R sin(θ)dθ$
$S = 4R\int_0^{\frac{π}{2}} \sqrt{1-cos^2(θ)} R sin(θ)dθ$
$S = 4R^2\int_0^{\frac{π}{2}} \sqrt{1-cos^2(θ)} sin(θ)dθ$
On sait que $cos^2(θ) + sin^2(θ) = 1$ et donc que $sin(θ) = \sqrt{1-cos(θ)}$ :
$S = 4R^2\int_0^{\frac{π}{2}}sin^2(θ)dθ$
$S = 4R^2\int_0^{\frac{π}{2}}sin^2(θ)dθ$
On sait que $sin(2θ) = sin(θ)sin(θ)-cos(θ)cos(θ) = cos^2(θ) -sin^2(θ)  = sin^2(θ)-(1-sin^2(θ)) = 2cos^2(θ)-1$
$cos^2(θ) = \frac{1+cos(2θ)}{2}$
$S = 2R^2\int_0^\frac{π}{2} 1+cos(2θ) dθ$
$S = 2R^2 [θ+\frac{sin(2θ)}{2}]_0^\frac{π}{2}$
$S = 2R^2(\frac{π}{2}+\frac{sin(π)}{2}-0-\frac{sin(0)}{2})$
$S = πR^2$

## On cherche à démontrer que $V_{sphere} = \frac{4}{3}πr^3$

Soit $O$ en $(0;0;0)$ le centre de la sphère $G$ et le plan $P : x+y=0$ :
Soit $A$ appartenant à $G$ et $B$ le projeté orthogonal de $A$ sur $P$.
Soit $Z$, projeté orthogonal de $A$ sur l'axe $z$.

$OA$ est le rayon de $G$ et $ZA = OB$ est le rayon du cercle de centre $Z$ passant par A.

On sait par Pytagore que $OA^2 = AB^2 + OB^2$
Avec $OA=R$ et $AB = z$ on a la fonction $r(z) = \sqrt{R^2-z^2}$ tel que $r^2(z) = R^2 - z^2$

Le volume de $G$ est donc la somme infinitésimale des aires de disques de rayon $r(z)$.

$V_G = π\int_{-R}^R r^2(z) dz$
$V_G = π[R^2z -\frac{1}{3}z^3]_{-R}^R$
$V_G = 2π(R^2R-\frac{1}{3}R^3)$
$V_G = \frac{4}{3}πR^3$ 