#MechEngr 2024-10-22

### Axial Deflection
$\delta = \frac{FL}{AE} = \frac{PL}{AE} = \frac{NL}{AE} = \Sigma \frac{FL}{AE}$
![[markup_1000019175.jpg]]
Find $\delta_{F}$
$A_{CD} = 45mm^{2}$
$A_{EF} = 75mm^{2}$
$A_{AB} = 60mm^{2}$
$E_{\times} = 350GPa$

#### FBD
$\Sigma F_{y} = 0 = N_{AB} + N_{CD} - 20kN$
$M_{A} = 0 = N_{CD}(1.25) - 20kN(0.5m)$
$N_{CD} = 8kN$
$N_{AB} = 12kN$

#### Deflections
![[markup_1000019263.jpg]]
$\delta_{AB} = \frac{N_{AB}L_{AB}}{A_{AB}E_{AB}} = \frac{(12kN)(2m)}{(60mm^{2})(350GPa)}=0.001143m$
$\delta_{CD} = \frac{N_{CD}L_{CD}}{A_{CD}E_{CD}} = \frac{(8kN)(2m)}{(45mm^{2})(350GPa)}=0.001016m$
$\delta_{EF} = \frac{N_{EF}L_{EF}}{A_{EF}E_{EF}} = \frac{(20kN)(1.5m)}{(75mm^{2})(350GPa)}=0.001143m$
- $1GPa = \frac{1kN}{mm^{2}}$ and $1MPa = \frac{1N}{mm^{2}}$


$\delta_{E} = \delta_{E_{1}} + \delta_{E_{2}}$
![[markup_1000019268.jpg]]
$\delta_{E} = \delta_{CD} + \frac{0.75}{0.125}(\delta_{AB}-\delta_{CD})$
$= 0.001016m + \frac{0.75}{0.125}(0.001143m - 0.001016m) = 0.001092m$

$\delta_{F} = \delta_{E} + \delta_{EF} = 0.001092m + 0.001143m = 2.235mm$

### Example 2
![[markup_1000019271.jpg]]
#### Outline:
- FBD -> Equilibrium to find forces and internal forces
- $\delta = \frac{FL}{AE}$ -> length change of each bar
- Geometry

#### FBD ABC
$\Sigma M_{B} = 0 = F_{AF}(2.4m) - 30kN(1.8m) \rightarrow F_{AF} = 22.5kN(T)$
$\Sigma F_{y} = 0 = -F_{AF} - F_{BE} - 30kN$
$F_{BE} = -52.5kN \rightarrow 52.5kN \text{ Compression}$

#### Deflections
$\delta_{AF} = \frac{FL}{AE} = \frac{(22.5kN)(3.6m)}{(500mm^{2})\left(18\frac{kN}{mm^{2}}\right)} = 9.00mm$
$\delta_{BE} = \frac{(-52.5kN)(3.6m)}{(1500mm^{2})\left(18 \frac{kN}{mm^{2}}\right)} = -7.00mm$
$\delta_{CD} = \frac{(30kN)(3m)}{(500mm^{2})\left(18 \frac{kN}{mm^{2}}\right)} = 10.00mm$

#### Geometry
![[markup_1000019280.jpg]]
