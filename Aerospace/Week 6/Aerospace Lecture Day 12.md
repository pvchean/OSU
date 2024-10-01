`#Aerospace 2024-09-26

### Class Question No. 1
Rocket Engine:
$T_{0}= 3144\text{°K}$
$P_{0}= 20 \text{ atm}$
$P_{e} = 1\text{ atm}$
$R=378 \frac{J}{kg*°K}$
$\gamma = 1.26$
$A_{throat}=0.1m^{2}$


Assume isentropic flow, what is $V_e$ and $\dot{m}_{e}$

$V_{e} = M_{e}\ a_{e}$
where:
	$M_e$: Mach Number
	$a_e$: Sound Speed

To calculate sound speed we need
$\frac{P_0}{P_{e}} = (1 + \frac{\gamma-1}{2}M_{e}^{2})^\frac{\gamma}{\gamma-1}$ -> $\frac{20}{1}=(1 + \frac{1.26-1}{2} M_{e}^{2})^\frac{1.26}{1.26-1}$
$20 = (1 + 0.13M_{e}^{2})^{4.846}$
$20^{\frac{1}{4.846}}= 1 + 0.13M_{e}^{2}$ 
$M_{e}^{2} = \frac{20^{\frac{1}{4.846}} - 1}{0.13}$
$M_{e}^{2} = 2.566$ <- Supersonic!

$\frac{T_0}{T_{e}} = (1 + \frac{\gamma-1}{2}M_{e}^{2})$ -> 1694°K

$V_{e} = M \sqrt{\gamma RT_{e}}$
$V_{e} = 2.566 \sqrt{1.26 \times 378 \times 1694} = 2,305 \frac{m}{s}$
$\dot{m} = \rho A V$ 

We dont know the area of the nozzle exit, so calculating mass flow rate is hard. as such, we use the area of the throat. since the throat in a C-D nozzle is always Mach=1, we can calculate $V_{Throat}$ and $\rho_{Throat}$ to calculate $\dot{m}$.

$\dot{m}_{exit} = \dot{m}_{Throat}$

$\frac{T_0}{T_{Throat}} = \left(1 + \frac{\gamma-1}{2}M_{Throat}^{2}\right) = \left(1 + \frac{1.26-1}{2}1^{2}\right) = 1.13$
$\frac{T_{0}}{1.13} = T_{Throat}$ -> $T_{Throat} = 2782.3\text{°K}$

$\frac{P_0}{P_{Throat}} = (1 + \frac{\gamma-1}{2}M_{Throat}^{2})^{\frac{\gamma}{\gamma-1}} = (1 + \frac{1.26-1}{2}1^{2})^{\frac{1.26}{1.26-1}}$
$P_{Throat} = 1.117\times10^{6} \frac{N}{m^{2}}$

$\rho = \frac{P}{RT}$ ->$\rho_{Throat} = 1.062 \frac{kg}{m^{3}}$

$V_{throat} = 1 \times \sqrt{\gamma RT_{Throat}}$ 

### Class Question No. 2

Reservoir -> C-D (A1) -> Test Section -> Convergent-Diffuser-Divergent (A2)

- The shock when supersonic transition to subsonic is called the normal shock.
- Shocks create a lot of losses, thus the flow at and after is no longer isentropic.
- During a shock, $P, P_{0}, \rho, \rho_{0}, T$ are discontinued, except $T_{0}$ is constant.
- $P_{02} < P_{01}$ because of shock losses.

Prove $A_{2} > A_{1}$ by deriving $\frac{A_{2}}{A_{1}}$ as a function of $\frac{P_{02}}{P_{01}}$

Sol: $\dot m_{1} = \dot m_{2}$ & $T_{01} = T_{02}$

$\rho_{1}V_{1}A_{1} = \rho_{2}V_{2}A_{2}$
$\rho_{1}a_{1}A_{1} = \rho_{2}a_{2}A_{2}$
$\rho_{1}A_{1}\sqrt{rRT_{1}} = \rho_{2}A_{2}\sqrt{rRT_{2}}$
$\frac{P_{1}}{\cancel{R}T_{1}}A_1\sqrt{\cancel{rR}T_{1}} = \frac{P_{2}}{\cancel{R}T_{2}}A_2\sqrt{\cancel{rR}T_{2}}$ -> $\frac{P_{1}A_{1}}{\sqrt{T_{1}}} = \frac{P_{2}A_{2}}{\sqrt{T_{2}}}$

@ Throat 1 $M_1$ = 1
$\frac{T_{01}}{T_{1}}= (1+ \frac{\gamma-1}{2}1^{2}) = \frac{\gamma+1}{2}$ -> $T_{1} = T_{01} \frac{2}{\gamma+1}$
$\frac{P_{01}}{P_{1}} = (1 + \frac{\gamma-1}{2} 1^{2})^{\frac{\gamma}{\gamma-1}}$ -> $P_{1} = P_{01} (\frac{\gamma+1}{2})^{\frac{-\gamma}{\gamma-1}}$


$\frac{P_{01}A_{1}}{\cancel{\sqrt{T_{01}}}} = \frac{P_{02}A_{2}}{\cancel{\sqrt{T_{02}}}}$ -> $P_{01}A_{1} = P_{02}A_{2}$ -> $\frac{A_{1}}{A_{2}} = \frac{P_{2}}{P_{1}}$ 
$T_{01} = T_{02}$

