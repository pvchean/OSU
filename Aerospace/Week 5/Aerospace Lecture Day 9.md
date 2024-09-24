#Aerospace 2024-09-17

### Low speed subsonic  wind tunnels

Resivoir -> Wind Tunnel -> Fan

Resivoir:
A = ∞, V = 0, $P_0$ $T_0$

Windtunnel:
Start:
$V_{1}$ $P_{1}$ $A_{1}$
Test Section:
$V_{2}$ $P_{2}$ $A_{2}$


Need ΔP =$P_1$ - $P_2$
Continuity: $V_{1}A_1$ = $V_{2}A_{2}$
Bernoulli: $P_{1} + \frac{1}{2}\rho V_{1}^{2} = P_{2} + \frac{1}{2}\rho V_{2}^{2}$

Question: for $A_1$, $A_{2}$, $P_{1}$, $P_{2}$ is known, what is $V_{2}$?

$V_{1}= \frac{A_{2}}{A_{1}}V_{2}$
$P_{1} + \frac{1}{2}\rho V_{1}^{2} = P_{2} + \frac{1}{2}\rho V_{2}^{2}$
$P_{1} + \frac{1}{2}\rho (\frac{A_{2}}{A_{1}}V_{2})^{2} = P_{2} + \frac{1}{2}\rho V_{2}^{2}$
$V_{2}= \sqrt{\frac{2(P_{1}-P_{2})}{\rho(1-\frac{A_{2}}{A_{1}})^{2}}}$

### Airspeed Measurement
### Definitions:
- **Static Pressure** p: Non-moving air pressure. ambient pressure.
- **Total Pressure** $P_0$: Measured as a moving pressure slowing down to geo isentropically.

V>0, P -> V=0, $P_0$
- The slow down process is imaginary, $P_{0}$ is a property of moving flow.
- $P_0$ > P for moving flow
- $P_0$ = P for  static fluid.

#### Calculating velocity
For M < 0.3 where $V_{0} = 0$
$P_{0} + \cancel{\frac{1}{2}\rho V_{0}^{2}} = P + \frac{1}{2}\rho V^{2}$
$P_{0}-P = \frac{1}{2}\rho V^2$
$V = \sqrt{\frac{2q}{\rho}}$ 
where: $q = P_{0}-P = \frac{1}{2}\rho V^2$