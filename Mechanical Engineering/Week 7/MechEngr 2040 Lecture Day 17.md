#MechEngr 

$I_{x} = \int y^{2}\ dA$ & $I_{y} = \int x^{2}\ dA$
1)
A  rectangle has a moment of inertia of:
$I_{x} = \frac{1}{12} bh^{3}$
$I_{y} = \frac{1}{12} hb^{3}$

2) Calculate $I_{x}$' for each shape
3) Use Parallel Axis Theorem
   $I_{x} = \bar I_{x'} + Ad_{y}^{2}$
4) $\Sigma I_{x}$

#### Example 1)
![[Pasted image 20241001081410.png]]
Because the shape is symmetric around the origin, the centroid is at the origin.
##### Simple Way, A)
![[Pasted image 20241001081834.png]]
$I_{x'} = \frac{1}{12}(5mm)(1.5mm)^{3}=1.406mm^{4}$
$I_{x'} = \frac{1}{12}(1.5mm)(11.5mm)^{3=}190.1mm^{4}$
$I_{x'} = 1.406mm^{4} + 1.406mm^{4} + 190.1mm^{4} = 193mm^{4}$
##### Hard/Long Way, B)
![[Pasted image 20241001081721.png]]
Short Tall Rectangle:
$I_{x'} = \frac{1}{12}(1.5mm)(5mm)^{3}=15.625mm^{4}$
Parallel Axis Theorem: $I_{x} = I_{x'} + Ad^{2} = 15.625mm^{4} + (1.5mm)(5mm)(3.25mm)^{2} = 94.84375mm^{4}$

Wide Rectangle:
$I_{x'} = \frac{1}{12}(11.5mm)(1.5mm)^{3=}3.234mm^{4}$

$I_{x'} = 94.84375mm^{4} + 94.84375mm^{4} + 1.234mm^{4} = 193mm^{4}$

#### Example 2)
![[Pasted image 20241001083113.png]]
##### Easy Way, A)
$I_{x'} = \frac{1}{12}(160mm)(160mm)^{3} - \frac{1}{12}(120mm)(80mm)^{3} = 49.5\times10^{6}\ mm^4$

##### Hard/Long Way, B)
![[Pasted image 20241001083312.png]]
$I_{x} = \frac{1}{12}(40mm)(160mm)^{3}$
$+ \left(\frac{1}{12}(120mm)(40mm)^{3} + (120mm)(40mm)(40mm+20mm)^{2}\right)$
$+ \left(\frac{1}{12}(120mm)(40mm)^{3} + (120mm)(40mm)(40mm+20mm)^{2}\right)$
$I_{x} = 49.5\times10^{6}\ mm^{4}$

##### What if the X Axis of rotation is not x' (around the centroid), but the bottom edge of the shape?
Take the moment of inertia of the whole shape, and parallel axis that around the new axis.
$I_{x} = \bar I_{x'} + Ad_{y}^{2}$
$I_{x} = 49.5\times10^{6}\ mm^{4} + ((160mm)(160mm)-(80mm)(120mm))\times(80mm)^{2}$
$I_{x} = 151.9\times10^{6}\ mm^{4}$
