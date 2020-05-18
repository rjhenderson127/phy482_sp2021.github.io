---
layout: homework
use_math: true
title: Homework 8 (Due. Feb 28)
---

## 1. Analyzing a single E&M wave

Consider the electric field $\mathbf{E}(x,y,z,t) = E_0\cos(k(x-ct))\hat{y}$ (where $k$ and $c$ are known constants).

1. What is the charge density $\rho (x,y,z,t)$ that this E field implies? What are the units of $k$ and $c$?
2. Come up with the simplest possible B field which satisfies Faraday’s law, given this E field. Then, CHECK that the remaining free-space Maxwell’s equations are satisfied, if you make the correct choice for the constant $c$. What is this required $c$? What is the required magnitude of the B field? What is the current density $\mathbf{J}(x,y,z,t)$ which this E and B field imply?
3. What is the Poynting vector, $\mathbf{S}$, associated with these fields? Describe in words what this E and B field look like. Can you "interpret" them physically? What does the constant "k" tell you?
4. Does this set of E and B provide a valid, self-consistent, physically possible solution to Maxwell's equations? What's the physics here?

## 2. 3D E&M Waves

Consider a 3D electromagnetic plane wave in vacuum, described in usual complex form by $\widetilde{\mathbf{E}}(\mathbf{r},t) = \widetilde{\mathbf{E}}_0 e^{i(\mathbf{k}\cdot \mathbf{r}-\omega t)}$, in which $\widetilde{\mathbf{E}}_0$ is a constant vector equal to $\widetilde{E}_0\hat{x}$, with $\widetilde{E}_0 = E_0e^{i\pi/2}$. Assume $\mathbf{k}$ is the wave vector $k\hat{y}$, $\omega$ is the angular frequency. As usual, the real field is $\mathbf{E} = Re[\widetilde{\mathbf{E}}]$.

1. Describe in words what this mathematical expression represents physically. You may use sketches, but if you do, they should be well described. In which direction the wave is moving? What is the speed, wavelength, and period of the wave? What does that phase of $\pi/2$ in $\widetilde{E}_0$ do?
2. Sketch the *real* field $\mathbf{E}(x=0,y,z=0,t=0)$ (a 2D plot with $y$ as the horizontal axis) and $\mathbf{E}(x=0,y=0,z=0,t)$ (a 2D plot with $t$ as the horizontal axis). Clearly indicate the direction of the field and the scale of both your axes. How is the field at $x=a$, i.e. $\mathbf{E}(x=a,y,z=0,t=0)$, different from the case at $x=0$?
3. Why is this called a plane wave (where is (are) the plane(s))? Sketch or represent this in 3D. - Describe how the direction of the electric field changes in time. If $\mathbf{E}$ always points in the same direction, the wave is said to be linearly polarized. Is this wave linearly polarized?
4. Find the associated magnetic field $\mathbf{B}(\mathbf{r},t)$ for this plane electric wave. Sketch the magnetic fields, $\mathbf{B}(x=0,y,z=0,t=0)$ and $\mathbf{B}(x=0,y=0,z=0,t)$ indicating field direction. (As above, be clear about your axes) A 3D sketch of $\mathbf{B}$ would be helpful here too, what's the simplest way to draw it?
5. Describe in words how B compares/contrasts with E.
6. Calculate the energy density $u_{EM}$, Poynting vector $\mathbf{S}$, and momentum density for these fields. Interpret the answers physically Make sense of them, including units, signs, directions, etc!
7. Calculate the angular momentum density $\mathbf{l}_{EM}$ (see Griffiths’ p. 358) about the origin (0,0,0). If you integrate this density over a cube of centered at the origin at one instant in time, would the angular momentum in that cube be zero or non-zero? Briefly, discuss.
8. Suppose now that we add two plane waves, $\mathbf{E}_1$ and $\mathbf{E}_2$, (superposition still works!) to find the total electric field. Let $\mathbf{E}_1(\mathbf{r},t) = \mathbf{E}_1 \cos(\mathbf{k}\cdot \mathbf{r} - \omega t + \delta_1)$ and $\mathbf{E}_2(\mathbf{r},t) = \mathbf{E}_2 \cos(\mathbf{k}\cdot \mathbf{r} - \omega t + \delta_2)$ so in this simple case the waves propagate in the same direction. Let's say the amplitudes are $\mathbf{E}_1 = E_1\hat{z}$ and $\mathbf{E}_2 = E_2\hat{z}$. Use complex notation (taking the real part only at the very end) to find $\mathbf{E}_T(\mathbf{r},t) = \mathbf{E}_1(\mathbf{r},t)+\mathbf{E}_2(\mathbf{r},t)$ in the form $\mathbf{E}_T(\mathbf{r},t) = \mathbf{E}_T \cos(\mathbf{k}\cdot \mathbf{r} -\omega t + \delta_T)$, giving expressions for the total amplitude and phase shift in terms of those from $\mathbf{E}_1(\mathbf{r},t)$ and $\mathbf{E}_2(\mathbf{r},t)$. Explicitly check your answer in the special case $\delta _1 = \delta_2$.
9. Let's examine one more situation, this time $\mathbf{E}(\mathbf{r},t)=\mathbf{E}_1 \cos(\mathbf{k}\cdot\mathbf{r} - \omega t) + \mathbf{E}_2 \cos(\mathbf{k}\cdot\mathbf{r}-\omega t + \pi/2)$,
in which $\mathbf{E}_1$ is a constant vector equal to $\mathbf{E}_0 \hat{z}$, $\mathbf{E}_2$ is a constant vector equal to $\mathbf{E}_0\hat{x}$, $\mathbf{k}$ is the wave vector $k\hat{y}$ (as before,) and $\omega$ is the angular frequency. Find the total $\mathbf{E}(\mathbf{r},t)$. Describe how the direction and magnitude of $\mathbf{E}$ changes in time. Is this wave linearly polarized? Consider all points in space where $\mathbf{k}\cdot\mathbf{r} = 0$ (in this case, how would you describe such a set of points in words?), and describe in words or pictures what your E field looks like. Does this help you describe the polarization state? (If you look down the axis with the wave approaching you, is the E vector circling CW? CCW? Or, something else?)
