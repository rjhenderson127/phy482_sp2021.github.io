---
layout: homework
use_math: true
title: Homework 7 (Due. Feb. 21)
---

## 1. Energy conservation

Consider an infinitely long solenoid (turns per length $n$) of radius $a$ that is at the center of a large resistive ring (radius $b$; resistance $R$), here $b \gg a$. The current in the solenoid varies with time, $I_s(t)$, such that an electric field is created everywhere in space and thus a current is driven in the wire. In this problem, you will show that the power dissipated in the resistive wire is equal to the integral of the Poynting vector over the outside surface of the solenoid.

1. Consider first the EMF produced by the changing magnetic field. Determine the EMF and show that the current running through the resistive ring, $I_r$, is $-\frac{1}{R}\mu_0 n \pi a^2 \dfrac{dI_s}{dt}$.
2. Next, use Faraday's Law to find the curly electric field just outside the solenoid (this is the field responsible for driving the current in the ring). Which direction is that electric field?
3. The ring produces it's own magnetic field. If we assume the solenoid is very small, we can say that the magnetic field produced by that ring at the location of the solenoid is nearly like that of a loop of wire at it's center. Derive or look up that magnetic field. Which way does it point?
4. In our discussion of energy conservation, $(\dfrac{dU_{mech}}{dt} + \dfrac{dU_{em}}{dt} = - \iint \mathbf{S} \cdot d\mathbf{A})$, we found we needed to pick a system. What system is appropriate to choose when considering the power dissipated in the resistive ring? What does that tell you about the energy transported by the surroundings? That is, which fields are transporting energy into the resistive wire?
5. Find the Poynting vector $\mathbf{S}$ based on the relevant electric and magnetic field in part 4. Show that the resulting Poynting vector is of magnitude $\dfrac{1}{4}\mu_0 I_r \dfrac{dI_s}{dt} \dfrac{ab^2n}{(b^2+z^2)^{3/2}}$. Which direction does it point?
6. Finally show by integrating $\mathbf{S}$ over the whole outside surface of the solenoid (recall it is small compared to the ring, so the Poynting vector you found above is valid), that you recover $P = I_r^2 R$.


## 2. Slowly accumulating charge

Consider a volume current that is (very slowly) flowing towards the $z$-axis,

$$\mathbf{J} = -\dfrac{\vert c \vert s}{2} \hat{s}.$$

Charge begins to accumulate along the $z$-axis.

1. Find an expression for the accumulating charge density as a function of time.
2. Determine the electric field at a distance $s$ from the $z$-axis as a function of time in all of space.
3. Discuss your results in the context of conservation of energy. Which aspects of the energy are increasing/decreasing? What are you defining as the region of interest?

## 3. Charging Capacitor

![cap][cap]

[cap]: ./images/hw7/cap_and_rim.png

A capacitor with circular plates of radius $R$ separated by distance $d \ll R$ is being charged by a steady current $I$. The plates are sufficiently close that fringe effects can be ignored.

1. Compute the magnitude of the B-field between the plates at all distances $r$ from the center of the plates ($r < R$ & $r > R$). Sketch the magnitude of the B-field vs. $R$.
2. Compute the Poynting vector $\mathbf{S}$ (magnitude and direction) on the rim of the capacitor, between the plates, at $r = R$. (The "rim" is the ribbon of area at $r = R$ between the plates; see the diagram.)
3. Show that the rate at which the capacitor's stored energy is increasing $dU/ dt$ is equal to the rate at which field energy is entering through the rim: $\iint \mathbf{S}\cdot d\mathbf{A}$.

## 4. Poynting Vector of a Solenoid

Consider a very long solenoid of length $L$, radius $r$, and turns per length $n$. The current $I$ in the solenoid is linearly ramped from $I=0$ to $I=I_0$ over a period $t_0$ as shown in the graph.

![graph][graph]

[graph]: ./images/hw7/ramped_current.png

1. Integrate the magnetic field energy density to derive a formula for the total field energy stored in the solenoid at times $t > t_0$.
2. Solve for the electric field everywhere at times $0 < t < t_0$.
3. Solve for the Poynting vector $\mathbf{S}$ (direction and magnitude) at $r = R$ (just inside the walls of the solenoid) as a function of time $t$.
4. Show that the total field energy/time passing from the walls of the solenoid into its interior, when integrated from $t = 0$ to $t = t_0$, gives the same total energy as you computed in part 1.

## 5. Energy flow in a coax

We now want to investigate energy flow in a cylindrical coax cable. For now, let's just look at fields constant in time, not varying in time. Assume that constant current $I$ flows in the $+z$ direction on the inner wire and that total current $I$ flows in the opposite direction in the shell. Also assume that there is a constant voltage difference $V$ between the wire and the shell, as shown.

![coax][coax]

[coax]: ./images/hw7/coax.png

1. For this steady current and voltage case: Find $\mathbf{E}$ and $\mathbf{B}$ everywhere in space. You may assume that the coax cable (wire plus shell) is neutral.
2. Calculate the Poynting vector $\mathbf{S}$ everywhere.
3. The magnitude of $\mathbf{S}$ gives the energy flux density and represents the power per area moving through space. Does its direction make sense for the coax?
4. Integrate this flux through the cross sectional area of the coax to find the power transported down the coax line. Does your answer make sense relative to the circuit maintaining the current and voltage? Briefly comment!
