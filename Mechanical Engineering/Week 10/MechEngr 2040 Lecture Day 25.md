#MechEngr 2024-10-21

### Axially-Loaded Members
![[markup_1000019160.jpg]]
Assumptions:
- Neglect End Effect (Blue and Purple)
- Assume stress is uniform (Green)
- Long, Slender object. $\frac{L}{d} > \approx10$

### Example 1
Assume a long slender cylinder pulled by force P on each end.
Find $\Delta{P}$:
Material E, Area A, Length L

Normal Stress: $\sigma = \frac{P}{A}$
Normal Strain: $\epsilon = \frac{\Delta{L}}{L}$
Hooke's law: $\sigma = E\epsilon$

Combining the three above:
$E\epsilon = \frac{P}{A} \rightarrow E(\frac{\Delta{L}}{L}) = \frac{P}{A} \rightarrow \Delta{L} = \frac{PL}{AE}$
1)$\Delta{L} = \frac{PL}{AE}$
With units: $\frac{\cancel{N}m}{\cancel{m^{2}}(\frac{\cancel{N}}{\cancel{m^{2}}})} \rightarrow m$
Where: P = internal force

![[markup_1000019166.jpg]]
$\Delta{L} = \int_{0}^{L} \frac{N(x)dx}{A(x)E}$

![[markup_1000019168.jpg]]
$\Delta{L} = \Sigma\left(\frac{PL}{AE}\right)$

### Example 1
![[markup_1000019169.jpg]]
$\Delta{L} = \frac{PL}{AE} = \frac{(300N)(200mm)}{\pi(7.6mm)^{2}2.7\times10^{9} \frac{N}{m^{2}}(\frac{1m}{1000mm})^{2}} = 0.126mm$

### Example 2
![[markup_1000019173.jpg]]

| AB                              | BC                              | CB                              |
| ------------------------------- | ------------------------------- | ------------------------------- |
| $E_{al} = 10 \times 10^{3} ksi$ | $E_{cu} = 18 \times 10^{3} ksi$ | $E_{st} = 29 \times 10^{3} ksi$ |
| A = 0.09in$^2$                  | A = 0.12in$^2$                  | A = 0.06in$^2$                  |
**Cut at AB:**
Cylinder cut in the middle of AB, with one force pulling left with 2 kip and N_AB pulling right.
$\Sigma F_{x} = 0 = N_{AB} - 2kip \rightarrow N_{AB} = 2kip$

**Cut BC:**
Cylinder cut in the middle of AB, with one force pulling left with 2 kip, two 3.5 kip forces pulling right, and N_BC pulling right.
$\Sigma F_{x} = 0 = N_{BC} + 2\times3.5kip - 2kip \rightarrow N_{BC} = -5kip$

**Cut at CD:**
Cylinder cut in the middle of CD, with one force pulling left with 2 kip and N_AB pulling left.
$\Sigma F_{x} = 0 = -N_{CD} - 1.5kip \rightarrow N_{CD} = -1.5kip$

$\delta_{AD} = \Sigma \frac{NL}{AE} = \frac{(+2kip)(18in)}{(0.09inch^{2})(10\times10^{3)} \frac{kip}{in^{2}}} + \frac{(-5kip)(12in)}{(0.12inch^{2})(18\times10^{3)} \frac{kip}{in^{2}}} + \frac{(-1.5kip)(16in)}{(0.06inch^{2})(29\times10^{3)} \frac{kip}{in^{2}}} = -0.00157 in$

### Example 3

![[markup_1000019175.jpg]]
Find $\delta_{F}$
$A_{CD} = 45mm^{2}$
$A_{EF} = 75mm^{2}$
