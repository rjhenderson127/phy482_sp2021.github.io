---
layout: homework
use_math: true
title: Homework 12 (Due. Apr. 6)
---

## 1.  Lorentz transformation for the general velocity vector

Textbooks tend to only give you the Lorentz transformation along a single coordinate axis, but it is not always convenient to keep redefining the coordinate system for problems with several different velocities. To derive a more general formula using vector notation, use the idea that the part of a position vector $\vec{r}$ that is parallel to the velocity is the part that is changed by the transformation, while the part that is perpendicular to the velocity is unchanged.

1. Assume that you wish to transform from your inertial frame (the ($\vec{r}, ct$) frame] to the "primed" inertial frame ($\vec{r}', ct'$) moving with velocity $\vec{v} = c\vec{\beta}$ that points in some arbitrary direction (e.g., it has an $x$, $y$ and $z$ component). You should find the following: $c t' = \gamma (c t − \vec{r} \cdot \vec{\beta})$ and $\vec{r}'=\vec{r}+(\gamma −1)(\vec{r}\cdot \hat{\beta})\hat{\beta}−\gamma ct \vec{\beta}$.
2. Show that in the case that the velocity is in the x-direction, you get back the usual transformation.
3. How would you write this using 4-vector notation? What is $\Lambda_{\nu}^{\mu}$?

## 2. Transformation of velocity and acceleration components

We derived the transformation of velocity in 1D (i.e., when there is one frame moving at a speed $v$ in the $x$ direction, $S'$ relative to the other, $S$) using the Lorentz transformations. We found that

$$u = \dfrac{u' + v}{1+\frac{u'v}{c^2}}$$

1. Derive the relationship between the velocity components in each frame (for both the $y$ and $z$ directions) for the same scenario. Recall that length measurements will be the same in both frames!
2. Derive the relationship between the acceleration measured in the $S$ frame and the $S'$ frame in just the x-direction.
3. Show check the limits of your results in part 2 when $v$ approaches 0. Does you result make sense? What about when $v$ approaches $c$?

## 3. Rapidity

It is common in nuclear physics to talk about "rapidity" of a particle, defined as an angle $\phi = \cosh^{-1} \gamma$ (here $\gamma$ is the usual relativistic gamma factor, and that's an inverse hyperbolic $\cosh$).

1. Prove that the usual relativistic $\beta = v/c$ is given by $\beta = \tanh \phi$, and then show $\beta \gamma = \sinh \phi$. With these, rewrite the Lorentz transformations in matrix form entirely in terms of the rapidity angle. The result you get might remind you of a rather different kind of transformation, please comment!
2. Suppose that observer B has rapidity $\phi_1$ as measured by observer A, and C has rapidity $\phi_2$ as observed by B (both velocities are on the x-axis). Show that the rapidity of C as measured by A is just $\phi_1 + \phi_2$, i.e. rapidities "add" (unlike velocities, which do not "properly" add in relativity!)

*Here is a hyperbolic identity you might find useful:*
$$\tanh(a+b) = \dfrac{\tanh a + \tanh b}{1 + \tanh a \tanh b}$$.

## 4. Invariance of the space-time interval

Prove that the interval between two events is Lorentz Invariant:

$$I = \Delta {x}'_{\mu} \Delta {x}'^{\mu} = \Delta {x}_{\mu} \Delta {x}^{\mu}$$

Recall that the Lorentz transformation is $\Delta {x}'^{\mu} = \Lambda_{\nu}^{\mu} \Delta x^{\nu}$.
