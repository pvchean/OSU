#MechEngr 2024-10-14
Normal Stress => $\sigma= \frac{N}{A}$

### St. Venant
Treat **Stress** as uniform as long as we are not right at the end.
Good assumption for really long structures, where $L > 10d$

Force Shear => V
Average Shear Stress => $\tau = \frac{V}{A}$
- Single Shear: $V = F$
- Double Shear: $2V = F$
- Triple Shear: $3V = F$
- N Shear = $NV = F$

### Allowable Stress / Safety Factor
$\sigma_{allow}$ & $\tau_{allow}$ are the most stress  that is allowed by a design.

Factor of Safety (F.S.) => $\frac{\sigma_{fail}}{\sigma_{allow}}$ & $\frac{\tau_{fail}}{\tau_{allow}}$
F.S. > 1.0, always. Otherwise the structure can't handle the loads you designed it for.
$\sigma_{fail}$ & $\tau_{fail}$ are values for a material that are tested on a lab, thus can be found in a look up table.

### Example 1
![[markup_1000018379.jpg]]
Pin A, B, & C: Double shear, Diameter = 0.3", $\tau_{allow} = 12.5\text{ksi}$
Rod BC: D = 0.4", $\tau_{allow} = 22\text{ksi}$
Find: max W

**FBD**
![[markup_1000018381.jpg]]
$\Sigma M_{A} = 0 = -W(4ft)(2ft) + \frac{4}{5}F_{BC}(3ft)$
$F_{BC} = (3.33ft)W$

$\Sigma F_{x} = 0 = A_{x} - \frac{3}{5}F_{BC}$
$A_{x} = (2ft)F_BC$

$\Sigma F_{y} = 0 = A_{y} - 4ft(W) + \frac{4}{5}F_BC$
$A_{y} = (1.33ft)W$

**Rod BC**:
$\tau_{BC} = T_{allow} = \frac{F_{BC}}{A_{BC}}$
$22000 \frac{lb}{\cancel{in^{2}}} = \frac{(3.33ft)W}{\pi(0.2\cancel{in})^{2}}$ => $W = 830 \frac{lb}{ft}$

**Pin B&C**:
$F_{BC} = (3.33ft)W$
$\tau_{\text{pin B,C}} = \tau_{allow} = \frac{V}{A}$
$V = \frac{1}{2}F_{BC} = \frac{3.33ft}{2}W$ => $12,500lb = \frac{1}{2}?$

**Pin A**:
$F_{A} = \sqrt{Ax^{2} + Ay^{2}} = \sqrt{(1.33ft\ W)^{2} + (2ft\ W)^{2}} = (2.404ft)W$
$V_{A} = \frac{(2.404ft)W}{2}$
$\tau_{allow} = 12,500 \frac{lb}{in^{2}} = \frac{(2.404ft)W}{\pi(0.15in)^{2}}$