#Aerospace 2024-10-01

### Definitions:
**Laminar**: The flow is straight and with no turbulence. Smooth stream line.
**Turbulence**: A flow with unpredictable and highly energetic path. Random Streamline streamline.


![[_20241001_093729.jpg]]

**Viscous Flow**
Air forces  on the body = Pressure + shear force
Exists between 2 layers of fluids, sliding against each other,

Inviscid=No separation
sticky=Separation, makes a wake, low pressure, pressure drag increases.
P1 > P2


$T_{w}$ relates to viscocity $\mu$, a fluid property.
$\mu_{air} < \mu_{water} < \mu_{oil}$

1)$T_{w} = \mu \frac{\partial{u}}{\partial{y}})_{y=0}$ 

Outside the boundary layer, there is no sheer force.

$\delta$ is the thickness of the boundary layer

### Reynolds Number
$R_{ex} = \frac{rho_{\infty}V_{\infty}x}{\mu_{\infty}}$ 
Ratio of momentum to shear force


When flow becomes turbulent, it has a tendency to bring more fluid from outside the boundary layer into the turbulent region

Velocity of the laminar flow near the surface is very low.
Velocity of the turbulent flow near the surface is very high.

velocity gradient = $\frac{\partial V}{\partial y}$
A high velocity gradient means there is a lot of friction.

$\mu\left(\frac{\partial{V}}{\partial{y}}\right)_{y=0\text{, laminar}} < \mu\left(\frac{\partial{V}}{\partial{y}}\right)_{y=0\text{, turbulent}}$

Adverse Pressure Gradient: $\frac{\partial{p}}{\partial{x}} > 0$
- Encourages turbulence.

$\frac{\partial{p}}{\partial{x}} < 0$
- favorable p.g.
- encourages laminar flow
- Sensitive to surface roughness

Laminar Flow is easier to separate, unlike turbulent flow which sticks more strongly to the surface. This is because turbulent flow has greater velocity and momentum thus resists more easily.

If the flow becomes separated, there is a huge drag due to vortices.
Because flow separation causes such massive drag, turbulence is preferred as the extra shear friction is magnitudes less than separation drag.

### Formulas
![[Pasted image 20241001095958.png]]
Boundary Layer Formula for flat plate:
**Laminar**: 
- $\delta = \frac{2.5x}{\sqrt{R_{ex}}} around x^{0.5}$
- $\frac{T_{w}}{\frac{1}{2}\rho_{\infty}V_{\infty}^{2}} = C_{f,x} = \frac{0.664}{\sqrt{R_{ex}}}$
- $\frac{1}{2}\rho_{\infty}V_{\infty}^{2} = q_{\infty}$
- $D_{f} = \int_{0}^{L} T_{w}(dx*1)$
- $\frac{D_{f}}{\rho_{\infty}(L*1)} * C_{f} = \frac{1.328}{\sqrt{R_{el}}}$
- $R_{el} = \frac{\rho_{\infty}V_{\infty}L}{\mu_{\infty}}$
- 

**Turbulent**: 
$\delta = \frac{0.37x}{R_{ex}^{0.2}}$
N/A


