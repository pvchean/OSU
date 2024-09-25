Centroid -> Integration

Centroid is the center of an area.

F = Area  under the curve
Balance of moments about o

$$
\begin{align}
\Sigma x \Delta W = \bar x W\\
\bar x = \frac{\bar x \Delta W}{W}\\
\bar x = \frac{\int x \Delta W}{\int dW}\\
\end{align}
$$
W = A×t ρ × g

$\bar y = \frac{\int y\ dA}{\int dA}$ 

#### Example
Find: $\bar y$
$y = 1 - \frac{1}{4}x^{2}$

###### Horizontal Strip:
$\int y\ dA = \int_{y=0}^{y=1} y*2x\ dY = \int_{0}^{1}4y\sqrt{1-y}\ dy$
$\int dA = \int_{y=0}^{y=1} 2x\ dY = \int_{0}^{1}4\sqrt{1-y}\ dy$
###### Vertical Strip:
$\int y\ dA = \int_{x=-2}^{x=2} (\frac{y}{2})y\ dx = \int_{-2}^{2} \frac{1}{2} y^{2}\ dx = \int_{-2}^{2} \frac{1}{2}(1 - \frac{1}{4}x^{2})^{2}\ dx$
$\int dA = \int_{x=-2}^{x=2} y\ dx = \int_{-2}^{2}(1- \frac{1}{4}x^{2})\ dx$

#### Example 2
For $y = -x$, $y^{2}= 2x$, and $x=2$, Find: $\bar x, \bar y$
Steel plate:
t = 0.3 m
$\rho = 7850 \frac{\text{kg}}{\text{m}^{3}}$
A=(0,0) is pin, B=(2, -2) is roller

$A = \int dA = \int_{x=0}^{x=2}(y_{2}-y_{1})dx \int_{0}^{2}[\sqrt{2x}-(-x)]\ dx = \int_{0}^{2}(\sqrt{2}x^{\frac{1}{2}} + x)\ dx$
$A = 4.667 m^{3}$

$\bar x = \frac{\int x\ dA}{A} = \frac{\int_{x=0}^{x=2}x\left(\sqrt{2}x^{\frac{1}{2}} + x\right)\ dx}{A} = 1.26m$ 
$\bar y = \frac{\int y\ dA}{A} = \int_{x=0}^{x=2}\left(\frac{y_{1}+y_{2}}{2}\right)\left(\sqrt{2}x^{\frac{1}{2}}+x\right)\ dx$ 
$\bar y = \int_{0}^{2} \frac{\left(\frac{\sqrt{2x}-x}{2}\right)\left(\sqrt{2x}+x\right)\ dx}{A} = 0.143m$ 
$\bar y = \frac{\iint yDa}{\iint dA}$

W = ρ\*A\*t\*g = $(4.667 \frac{kg}{m^{3}})(7850 m^{2})(0.3m)(9.81 \frac{m}{s^{2}})$
W = 107,810 N @ (1.26, 0.143)

##### Equilibrium
$\Sigma M_{A} = 0 = -107,81\ kN(1.26m) + F_{b}(\sqrt{8}\ m)$ 
$F_{b}=47.9 kN$

$\Sigma F_{xx}= 0 = Ax + Fb \cos45\deg = A_{x} = 1$ 