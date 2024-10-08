#MechEngr 2024-09-30

$\bar y = \frac{\int y\ dA}{\int da}$
$I_{y}= \int y^{2}\ dA$

#### Examples
![[Pasted image 20240930081238.png]]
let x = $\frac{y^{2}}{2}$

Find: $I_x$
$I_{x} = \int y^{2}\ dA$
x = right bound - left bound -> 2 - x
$I_{x} = \int y^{2}\ dA$
$I_{x}= \int_{y=0}^{y=2}y^{2}(2-x)\ dy$
$I_{x}= \int_{y=0}^{y=2}y^{2}(2 - \frac{y^{2}}{2})\ dy$
$I_{x} = 2.14\ m^4$

#### Example 2:
![[Pasted image 20240930082217.png]]
$y = 2x^4$ and $x = \left(\frac{y}{2}\right)^{\frac{1}{4}}$

Find: $I_{x}$ & $I_{y}$

$I_{x} = \int y^{2}\ dA$
$I_{x} = \int_{y=0}^{y=2}y^{2}\left(1-\left(\frac{y}{2}\right)^{\frac{1}{4}}\right)dy$
$I_{x} = \int_{0}^{2}\left(y^{2} - \frac{y^{\frac{9}{4}}}{2^{\frac{1}{4}}}\right)dy$
$I_{x} = \frac{y^{3}}{3} - \frac{y^{\frac{13}{4}}}{\frac{13}{4}\times2^\frac{1}{4}}|_{0}^{2}$  

$I_{y} = \int x^{2}\ dA$
$I_{y} = \int_{x=0}^{x=1} x^{2}2x^{4}\ dx = \frac{2x^{7}}{7}|_{0}^{1} = 0.286$

#### Example 3
triangle where hyp goes from y axis to x axis, corner at origin, height h, base b.
$y = \frac{h}{b}(b-x)$ & $x = b - \frac{b}{h}y$

$I_{x} = \int_{y=0}^{y=h} y^{2}\left(b - \frac{b}{h}y\right)dy$
$I_{x} = \left(\frac{by^{3}}{3} - \frac{b}{h}\times \frac{y^{4}}{4}\right)|_{0}^{h} = \frac{bh^{3}}{12}$

### Parallel Axis theorem

$I_{x} = \bar I_{x'} + A\ (d_{y})^{2}$
Where:
- $I_x$ is the moment of inertia around the X axis
- $\bar I_{x'}$ = Moment of inertia about centroidal axis
- $(d_{y})^{2}$ = distance between the two axes

Same triangle as example 3.
$I_{x} = \frac{h^{3}b}{12}$
$A = \frac{1}{2}hb$
$d_{y} = \frac{h}{3}$
$\frac{h^{3}b}{12} = \bar I_{x'} + \frac{1}{2}hb(\frac{h}{3})^{2}$
$\bar I_{x'} = \frac{h^{3}b}{12} - \frac{1}{2}hb(\frac{h}{3})^{2}$
$\bar I_{x'} = \frac{h^{3}b}{36}$
