#MechEngr 2024-10-08

### Shear Stress
Two forces acting perpendicular to an object in opposite directions
**Single Shear:**
Average Shear Stress: $\tau = \frac{V}{A}$. Units: psi, $\frac{N}{m^{2}}$, Pa, etc. (Pressure)
![[markup_1000017656.jpg]]
**Double Shear:**
$\Sigma F_{x} = 0 \rightarrow F - 2V = 0 \rightarrow V = \frac{F}{2}$
![[markup_1000017656 (1).jpg]]

![[markup_1000017659.jpg]]

### Example
![[markup_1000017664.jpg]]
**FBD:**
![[markup_1000017661.jpg]]
**Equilibrium Equations**:
$\Sigma F_{x} = 0 \rightarrow V-600N \sin{30\degree} \rightarrow V = 300N$
$\Sigma F_{y} = 0 \rightarrow -N-600N\cos{30}\degree = 0 \rightarrow N = -520N$
$\Sigma M_{cut} = 0 \rightarrow M = 0$
**Hypotenuse:**
$\cos{30\degree} = \frac{100mm}{h}$
$A = \left(\frac{100mm}{h}\right)(50mm) = 5773.5mm^{2} = 5,7735\times10^{-3}\ m^{2}$
$\sigma = \frac{N}{A} = \frac{-520N}{5,7735\times10^{-3}\ m^{2}} = 52000 \frac{N}{m^{2}} = 52kPa$

### Example 2
![[markup_1000017666.jpg]]
A is Single Shear, C is double shear
$W = 75kg \times 9.81\frac{m}{s^{2}} = 735.75N$

**Two-Force member AB:**
![[Pasted image 20241008083821.png]]
**FBD:**
![[markup_1000017668.jpg]]
$\Sigma M_{C} = 0 \rightarrow 735.75N(0.3m) - 735.75N(2.8m) - (\frac{1.5}{2.5})F_{ab}(2m) = 0$
$F_{AB} = -1532.81N$
$\rightarrow^{+}\ \Sigma F_{x} = 0 \rightarrow C_{x} - (\frac{2}{2.5})F_{ab} - T = 0$
$C_{x} = -490.5N$
$\uparrow^{+}\ \Sigma F_{y} = 0 \rightarrow C_{y} - T - (\frac{1.5}{2.5})F_{AB} = 0$
$C_{y} = -184N$

**Shear Stress:**
Pin A: $\tau_{avg,_{A}} = \frac{V}{A} = \frac{|F_{AB}|}{A} = \frac{1532.81N}{\pi (0.005m)^{2}} = 19.52MPa$
Pin C:
$F_{BC}$ = $\sqrt{C_{x}^{2} + C_{y}^{2}} = 524N$
$V = \frac{F_{BC}}{2} = 262N$
$\tau_{avg,_{A}} = \frac{V}{2A} = \frac{262}{\pi (0.005m)^{2}} = 3.34MPa$