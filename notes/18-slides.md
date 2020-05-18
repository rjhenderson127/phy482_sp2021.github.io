---
layout: slide
theme: white
transition: slide
---


<section data-markdown>

The time rate of change of the energy density is,

$\frac{\partial}{\partial t} u
_q = -\frac{\partial}{\partial t}(\frac{\varepsilon_0}{2}E^2 + \frac{1}{2\mu_0}B^2)-\nabla \cdot \mathbf{S}$

where $\mathbf{S} = \frac{1}{\mu_0}\mathbf{E} \times \mathbf{B}$.

How do you interpret this equation? In particular: Does the minus sign on the first term on the right seem ok?

1. Yup
2. It's disconcerting, did we make a mistake?
3. ??

Note:
* Correct Answer: A
* Talk about the signs with them
</section>

<section data-markdown>

If we integrate the energy densities over a closed volume, how would interpret $\mathbf{S}$?

$$\frac{\partial}{\partial t}\iiint (u_q + u_E)d\tau = -\iiint \nabla \cdot \mathbf{S} d\tau = - \iint \mathbf{S} \cdot d\mathbf{A}$$

1. OUTFLOW of energy/area/time or
2. INFLOW of energy/area/time
3. OUTFLOW of energy/volume/time
4. INFLOW of energy/volume/time
5. ???

Note:
* Correct Answer: A

</section>

<section data-markdown>

Our global statement of energy conservation is:
$$\dfrac{dU_q}{dt} + \dfrac{dU_e}{dt} = -\iint \mathbf{S}\cdot d\mathbf{A}$$
Which term describes that energy of the electromagnetic field?

1. $\frac{dU_q}{dt}$
2. $\frac{dU_e}{dt}$
3. $-\iint \mathbf{S}\cdot d\mathbf{A}$
4. ???

Note:
* Correct Answer: B
</section>

<section data-markdown>

Our global statement of energy conservation is:
$$\dfrac{dU_q}{dt} + \dfrac{dU_e}{dt} = -\iint \mathbf{S}\cdot d\mathbf{A}$$
What does the integral term (without the minus sign) refer to?

2. Total energy coming in
3. Total energy going out
3. Rate of total energy coming in
4. Rate of total energy going out

Note:
* Correct Answer: D
</section>

<section data-markdown>

Consider a current $I$ flowing through a cylindrical resistor of length $L$ and radius $a$ with voltage $V$ applied. What is the E field inside the resistor?

<img src="./images/cylindrical_resistor.png" align="center" style="width: 400px";/>

1. $(V/L) \hat{z}$
2. $(V/L) \hat{\phi}$
3. $(V/L) \hat{s}$
4. $(Vs/L^2) \hat{z}$
5. None of the above

Note:
* Correct Answer: A
</section>

<section data-markdown>
Consider a current $I$ flowing through a cylindrical resistor of length $L$ and radius $a$ with voltage $V$ applied. What is the B field inside the resistor?

<img src="./images/cylindrical_resistor.png" align="center" style="width: 400px";/>

1. $(I\mu_0/2\pi s) \hat{\phi}$
2. $(I\mu_0s/2\pi a^2)  \hat{\phi}$
3. $(I\mu_0/2\pi a)  \hat{\phi}$
4. $-(I\mu_0/2\pi a)  \hat{\phi}$
5. None of the above

Note:
* Correct Answer: B

</section>

<section data-markdown>

Consider a current $I$ flowing through a cylindrical resistor of length $L$ and radius $a$ with voltage $V$ applied.
What is the direction of the $\mathbf{S}$ vector on the outer curved surface of the resistor?

<img src="./images/cylindrical_resistor.png" align="center" style="width: 400px";/>

1. $\pm \hat{\phi}$
2. $\pm \hat{s}$
3. $\pm \hat{z}$
4. ???

Note:
* Correct Answer: B
</section>

<section data-markdown>


<img src="./images/cap_with_blue_cylinder.png" align="left" style="width: 400px";/>
Consider the cylindrical volume of space bounded by the capacitor plates.  Compute $\mathbf{S} = \mathbf{E} \times \mathbf{B} /\mu_0$  at the outside (cylindrical, curved) surface of that volume.
Which WAY does it point?

1. Always inward
2. Always outward
3. ???

Note:
* Correct Answer: A
</section>

<section data-markdown>

The energies stored in the electric and magnetic fields are:


1. individually conserved for both $\mathbf{E}$ and $\mathbf{B}$, and cannot change.
2. conserved only if you sum the $\mathbf{E}$ and $\mathbf{B}$ energies together.
3. are not conserved at all.
4. ???

Note:
* Correct Answer: C

</section>

<section data-markdown>

<img src="./images/third_law.png" align="center" style="width: 600px";/>

Newton’s 3rd Law is equivalent to...
1. Conservation of energy
2. Conservation of linear momentum
3. Conservation of angular momentum
4. None of these.  NIII is a separate law of physics.

Note:
* Correct Answer: B

</section>

<section data-markdown>

Consider two point charges, each moving with constant velocity $\mathbf{v}$, charge 1 along the $+x$ axis and charge 2 along the $+y$ axis.
They are equidistant from the origin.

What is the direction of the magnetic force on charge 1 from charge 2? (*You'll need to sketch this! Don’t do it in your head!*)

1. +x
2. +y
3. +z
4. More than one of the above
5. None of the above

Note:
* Correct Answer: B

</section>

<section data-markdown>

Consider two point charges, each moving with constant velocity $\mathbf{v}$, charge 1 along the $+x$ axis and charge 2 along the $+y$ axis.
They are equidistant from the origin.

What is the direction of the magnetic force on charge 2 from charge 1? (You’ll need to sketch this! Don’t do it in your head!)

1. Equal to the answer of the previous question
2. Equal but opposite to the answer of the previous question
3. Something *different* than either of the above.

Note:
* Correct Answer:  C
</section>
