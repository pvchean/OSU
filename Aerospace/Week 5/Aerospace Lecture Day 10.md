#Aerospace 2024-09-19

For compressible flow, speed 0.3< M < 1
- Bernoulli's equation is no good.
- ρ changes

for h = entropy
(1) $h = e + pv$
h solely depends on temperature.
(2) h = $C_{p}T = C_{T} + pv$

$\frac{1}{T}\{C_pT = C_vT + pv\}$
(3) $C_{p}= C_{v}+ \frac{pv}{T}$ 

$C_{p}= C_{v}+ R$ because $\frac{pv}{t}=R$ (from the equation of state)
(4) 1 = $\frac{C_{v}}{C_{p}} + \frac{R}{C_{p}}$

don't forget $\frac{C_{v}}{C_{p}} = \frac{1}{\gamma}$
(5) $C_{p} = \frac{\gamma R}{\gamma- 1}$ 

Isentropic, an adiabatic and non-viscous process.
$\frac{1}{C_{p}T}\{C_{p}T_{0} + \cancel{\frac{V_{0}^{2}}{2}} = C_{p}T_{1} + \frac{V_{1}^{2}}{2}\}$
$\frac{T_{0}}{T} = 1 + \frac{V_{1}^{2}}{2C_{p}}$
$=1+ \frac{(\gamma-1)V_{1}^{2}}{2(\gamma RT_{1})}$

$M_{1}^{2} = \frac{V_{1}^{2}}{\gamma RT_{1}}$

(6) $\frac{T_{0}}{T} = 1 + \frac{\gamma - 1}{2} M^{2}$

### Isentropic ref
$\frac{P_{0}}{P_{1}} = (\frac{\rho_{0}}{\rho_{1}})^{\gamma}=(\frac{T_{0}}{T_{1}})^{\frac{\gamma}{\gamma-1}}$ 
(7) $\frac{P_{0}}{P_{1}} = (1 + \frac{\gamma-1}{2}M_{1}^{2})^{\frac{\gamma}{\gamma-1}}$ 
(8) $\frac{\rho_{0}}{\rho_{1}} = (1 + \frac{\gamma-1}{2}M_{1}^{2})^{\frac{1}{\gamma-1}}$


(9) $M^{2} = \frac{2}{\gamma-1}\left[(\frac{P_{0}}{P})^{\frac{\gamma-1}{\gamma}}-1\right]$
(10) $V^{2} = \frac{2\alpha^{2}}{\gamma-1}\left[(\frac{P_{0}}{P})^{\frac{\gamma-1}{\gamma}}-1\right]$
- Pitot-Satic = $P_{0}-P$

(11) $V^{2} = \frac{2\alpha^{2}}{\gamma-1}\left[(\frac{P_{0}-P}{P}+1)^{\frac{\gamma-1}{\gamma}}-1\right]$
- good for all airflow M < 1


On modern A/C, we have a way to measure ($P_0-P$), p(with line above p), T to get $V_{\text{true}}$

### Supersonic Measurement

| Supersonic  | Measurement             |
| ----------- | ----------------------- |
| (1)         | (2)                     |
| $M_1$ > 1   | $M_2 < M_1$             |
| $P_1$       | $P_2 > P_1$             |
| $T_1$       | $T_{2} > T_1$           |
| $V_1$       | $V_{2} < V_{1}$         |
| $P_{0_{1}}$ | $P_{0_{2}} < P_{0_{1}}$ |
| $T_{0_{1}}$ | $T_{0_{1}} = T_{0_{2}}$ |

### Example Problem No. 1
$P_{\infty} = 2116 \frac{\text{lb}}{\text{ft}^{2}}$
$V_{\infty} = 7.33.3 \text{ft}/\text{s}$
$\rho_{\infty} = 0.00237 \frac{\text{slug}}{\text{ft}^3}$

A:
$P_{A}=1497 \frac{\text{lb}}{\text{ft}^{2}}$
$V_{\infty} = \text{ ?}$
$\rho_{\infty} = \text{ ?}$
Q: What is $M_A$ what is $V_{A}$?

##### Calculate var_0:
$T_{\infty}= \frac{P_{\infty}}{\rho_{\infty}R}$ = $518.8 \degree R$
$\alpha_{\infty}= \sqrt{\gamma R T_{\infty}}= 1116.4 \frac{\text{ft}}{\text{s}}$
$M_{\infty}= \frac{V_\infty}{\alpha_{\infty}} = 0.657$
$\frac{T_{0}}{T_{\infty}} = (1 + \frac{\gamma-1}{2}M_{\infty}^{2})$ -> $T_{0} = 563.6\degree R$
$\frac{P_{0}}{P_{\infty}}=(1 + \frac{\gamma-2}{2}M_{\infty}^{2})^{\frac{\gamma}{\gamma-1}}$ -> $P_{0} = 2827 \frac{\text{lb}}{\text{ft}^{2}}$

##### Calculate A_0:

@A, local mach number is
$\frac{P_{0}}{P_{A}}= (1 + \frac{\gamma-1}{2}M_{A}^{2})^{\frac{\gamma}{\gamma-1}}$ -> $M_{A} = 0.9977$
$\frac{T_{0}}{T_{A}}= (1 + \frac{\gamma-1}{2}M_{A}^{2})$ -> $T_{A} = 470\degree R$
$V_{A} = M_{A}\sqrt{\gamma RT_{A}} = 1060 \frac{\text{ft}}{\text{s}}$



