#Aerospace 2024-10-22

## Chapter 6
### Aircraft Performance:
- Stall Speed
- Maximum Speed
- Climb Rate
- Range
- Stability And Control
These metrics combined are the Flight Dynamics of the aircraft.


$C_{d}$ = Profile Drag
$C_{D}$ = Drag including fuselage
$C_{D} = C_{D,e} + \frac{C_{L}^{2}}{\pi\ AR\ e}$
$C_{D,e} = C_{D,0} + rC_{L}^{2}$
thus
1)$C_{D} = C_{D,0} + (r + \frac{1}{\pi\ AR\ e})C_{L}^{2}$
where e = span efficiency factor
now:
2)$C_{D} = C_{D,0} + \frac{C_{L}^{2}}{\pi\ AR\ e}$
where e is now efficiency factor (0.7 < e < 0.9)

- $C_{D,0}$ is independent of lift. It is also called parasite drag.

$\Sigma F_{||} = T\cos(\alpha_{T}) - D - W\sin(\theta) = m \frac{dv}{dt}$
$\Sigma F_{\perp} = L - W\cos(\theta) + T\sin(\alpha_{T}) = m \frac{V^{2}}{R}$

If the aircraft is not climbing or turning:
- T = D
- L = W

##### 6.3) Thrust req for steady flight
W=L, $T_{r}$ = D
$L = \frac{1}{2}\rho v^{2} S C_{L} = W$
$C_{L} = 2\frac{W/S}{\rho V^{2}}$

For a fixed wing loading (W/S):
$V \uparrow, C_{L} \downarrow$
$V \downarrow, C_{L} \uparrow$

How D vs V?
$D_{total} = \frac{1}{2}\rho V^{2} S (C_{D,0} + \frac{C_{L}^{2}}{\pi\ AR\ e})$
$= (\frac{1}{2}\rho\ S\ C_{D,0})V^{2} + \left(\frac{2W^{2}}{\rho S \pi\ AR\ e}\right)V^{-2}$
$= D_{0} + D_{i}$

![[Pasted image 20241022094545.png]]
Flying at $D_{min}$ is the most efficient speed of flight.

$\frac{dD}{dV} = \frac{d\left(\left(\frac{1}{2}\rho\ S\ C_{D,0}\right)V^{2} + \left(\frac{2W^{2}}{\rho S \pi\ AR\ e}\right)V^{-2}\right)}{dV}$ $= 2(\frac{1}{2}\rho S C_{D,0})V + (-2)\left(\frac{2W^{2}}{\rho S \pi\ AR\ e}\right)V^{-3} = 0$
$C_{D,0} = \frac{1}{\pi\ AR\ e}\left[2\frac{\frac{W}{S}}{\rho V^{2}}\right]^{2} = C_{L}^{\frac{2}{\pi\ AR\ e}} = C_{D,i}$
$C_{D,0} = C_{i} \rightarrow D_{0} = D_{i}$
$D_{min}$ at $D_{0}=D_{i} or C_{D,0} = C_{Di}$

$\frac{T_{R}}{W} = \frac{D}{L} \rightarrow T_{R} = \frac{W}{\frac{L}{D}} = \frac{W}{\frac{C_{L}}{C_{D}}}$

for $W_{fixed}$: $T_{R}$ occurs when $(\frac{L}{D})_{max}$

![[Pasted image 20241022095826.png]]
