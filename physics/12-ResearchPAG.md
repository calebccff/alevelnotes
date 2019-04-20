# Applying Archimedes principle in the context of a weather balloon
**Or how we’re sending a balloon to the ‘edge’ of space**

## Purpose
The aim of this paper is to explore the viability of sending a small weather balloon to space and additionally produce a model to calculate the expected maximum drift during the flight and expected terminal velocity with and without a parachute.

## Archimedes principle
Archimedes principle state that the weight of fluid displaced by a submerged object is equal to the difference between the weight of the object in a vacuum and the net weight of the object in the fluid.

$$W_{fd} = W_v - W_f$$
Where:
$W_{fd}$ is the weight of the displaced fluid,
$W_v$ is the weight of the object in a vacuum and
$W_f$ is the weight of the object in the fluid (The weight $-$ the upthrust in the fluid)

## Bouyancy force
The bouyancy force for a fluid is:
$F_B = W$ where $W$ is the weight of the fluid (in a vacuum)
The weight of the fluid can be calulcated with $W = \rho \times V \times g$ where $\rho$ is the density of the fluid $V$ is the volume of the submerged part of the object and $g$ is acceleration due to gravity ($g \approxeq 9.81ms^{-2}$)

### Net force
The net force on the submerged object is equal to the difference between weight of the object in vacuum and the bouyancy force. I will refer to the net force as the **upward force** from now.

## Calculating the density of the fluid
The specific focus of this paper is on balloons in air, therefore this equation is specific to air and can't be applied to other fluids (like water).
$$\rho_{air} = \frac{P_{air}}{R\times T}$$
Where:
$P_{air}$ is the air pressure
$R$ is the specific gas constant for air ($287.058 JK^{-1}kg^{-1}$)
$T$ is the temperaure ($\degree K$)

## The key properties of a helium balloon.
In order to calculate the bouyancy force on a helium balloon in the atmosphere there are several key properties to account for:

1. The changing pressure
> As the balloon rises through the atmosphere the air pressure decreases, this means the bouyancy equation has to account for varying pressure. This can be done easily using the approximation:
> $$P = 101325(1 -[2.25577\times 10^{-5}\times h])^{5.25588}$$
> where $h$ is the altitude above sea level
> This results in the density of the air varying.

2. Changing temperature
> The temperature affects the density of the air and the helium


# Equations
$$F_B=g(\frac{P}{R_{specific}\times T_1}-\frac{M_0\;T_0}{V_0T_1e^{cy}})\,(V_0(\frac{T_1}{T_0})e^{cy})$$
$$ F_B = \rho g V $$
$$ \rho = \rho_{air}-\rho_{inBalloon}$$
$$ \rho_{air} = \frac{P}{R_{specific} T} $$
$$\rho_{inBalloon}=\frac{M_0}{V} $$
$$ V = V_0{(\frac{T_1}{T_0}})e^{cy}$$
$$ V_0 = \frac{4}{3} \pi r_0^3$$

$$ M_0 = \rho_{He}V_0$$
$$ c = \frac{\rho_0g}{P_0} $$

>$R_{specific} = 287.058 JK^{-1}kg^{-1}$
$F_B =$ Force of Buoyancy
$g =$ Accelleration due to gravity, which equals 9.81$ms^{-2}$
$\rho_{air} =$ Density of air, which equals 1.225$kgm^{-3}$
$V_0 =$ The volume at the start, measured in $m^3$
$M_0 =$ Mass at the beginning in kg 
$\rho_{He} = 0.1785$
$T_0 =$ Temperature at ground level, which the standard 288.15$K$
$T_1 =$ Temperature at a given height, measured in $K$
$c = \frac{\rho_0g}{P_0}$
Where $P_0 =$ air pessure at ground, 101325$Pa$
$y =$ The altitude of the balloon.
$r_0 =$ The radius of the balloon on the ground. 
