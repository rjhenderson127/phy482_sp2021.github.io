---
layout: homework
use_math: true
title: Homework 1 (Due. Jan 10)
---

## 1. Sketching

1. Make a quick sketch, in the x-y plane, of the following (two-dimensional) vector function. Plot enough different vectors to give a feeling for what this field looks like in the x-y plane.
$$\dfrac{x}{\left(x^2+y^2\right)^{3/2}}\hat{\mathbf{x}}+\dfrac{y}{\left(x^2+y^2\right)^{3/2}}\hat{\mathbf{y}}$$
2. Explain briefly in words what this plot is showing. Is it physically realizable as an electrostatic field?
3. Do the same as above for the field:
$$\left(2\cos \theta\,\hat{\mathbf{r}} + \sin \theta\,\hat{\mathbf{\theta}}\right)/r^3$$
(Here, I am assuming we are in 3-D spherical coordinates, but there is no azimuthal dependence. How should you "sketch" this?) Where have you seen this field before?

## 2. Divergence and Curl of a Vector Field

For each of the vector fields sketched below:

1. Which of them have nonzero divergence somewhere? If the divergence is nonzero only at isolated points, which point(s) would that be?
2. Which of the following fields have nonzero curl somewhere? If the curl is nonzero only at isolated points, which point(s) would that be?

A. ![Image A][a]

(Note: All arrows are the same length)

B. ![Image B][b]

(Note: Arrows have no length in the middle)

C. ![Image C][c]

(Note: Arrows growing in length as $r^2$)

D. ![Image D][d]

E. ![Image E][e]

(Note: Arrows decreasing in length as $1/r^2$.  Think of a "Coulomb field" of a point charge here...)

## 3. A few short computations

1. Compute the divergence and curl of $(x+y)\hat{\mathbf{i}}+(y+z)\hat{\mathbf{j}}+(x-2z)\hat{\mathbf{k}}$.
2. Could this field be a physical electrostatic field in some limited region of space near the origin? Very briefly, explain your reasoning.
3. Given the following mathematical form for a volume charge density $\rho(\mathbf{r})$, describe the charge distribution in words, and also draw a little sketch showing where the charges are: $\rho(\mathbf{r}) = a\delta^3(\mathbf{r}-\mathbf{R}) + b\delta(r-R)$, where $a$, $b$ are given constants with appropriate units, $\mathbf{R}=\langle 2,0,0\rangle$, and as usual $r = \lvert\mathbf{r}\rvert$.
4. What are the (SI metric) units of $a$ and $b$ in the charge density expression above?
5. What is the total charge, in terms of the given constants in the equation?

## 4. The Electric Field and Gauss' Law

1. What exactly is $\mathbf{E}$, the electric field? Define it. How do you think about it, both mathematically and in words. Please define any technical words you introduce.
2. Gauss' Law states: $\oint_S \mathbf{E}\cdot\hat{\mathbf{n}}\,dA = \frac{q_{enclosed}}{\varepsilon_0}$
Suppose I evenly fill a cube (length $L$ on a side) with electric charge. I then imagine a larger, closed cubical surface neatly surrounding this cube (length $2L$ on a side). Can you use Gauss' law (above) to simply compute the value of the electric field at arbitrary points outside the charged cube? (Don't try, just tell me if you could, and why/why not?)

## 5. Field, Charge, and Voltage

Given that an electric field in some region of space is given by $\mathbf{E}(x,y,z) = cy\hat{\mathbf{j}}$, where $c$ is a given constant.

1. What are the SI units of c?
2. What, if anything, can you tell us about the charge density throughout this region, $\rho(x,y,z)$?
3. What is the voltage associated with this E field? (Is your answer unique?)

## 6. The Magnetic Field

You have an infinitely tall, infinitesimally thin cylindrical sheet of surface current running around the $z$-axis, i.e., $\mathbf{K} = K_0 \hat{\phi}$ at $s=R$ (otherwise 0), as shown below.

![K in phi direction][K]

1. What are the SI units of $K_0$?
2. Sketch the magnitude of the resulting $B$ field as a function of radial distance, $s$
(both inside and outside the sheet).
3. Briefly, show/explain your work for part 2. (*If you grabbed a formula from Griffiths, explain concisely where it comes from.*)

[a]: ./images/hw1/a.png
[b]: ./images/hw1/b.png
[c]: ./images/hw1/c.png
[d]: ./images/hw1/d.png
[e]: ./images/hw1/e.png
[K]: ./images/hw1/K_phi.png

## 7. Plotting The Electric Field

In this problem, use a Jupyter notebook to plot the field of:

1. a positive point charge
2. an electric dipole
3. an electric quadrupole

You might want to review homework sets from PHY 481 or just look up how to use [quiver plot with Matplotlib](http://matplotlib.org/examples/pylab_examples/quiver_demo.html).

**You will turn this in using your own GitHub repository.**

## 8. Project Problem - What is interesting?

This problem is to help you get started on your individual research project. First, define your phenomenon: what is it and why is it interesting to you? Find a few papers (at least 4) that you can use to start your background research. Please give the full references to these papers. Write 2 to 3 paragraphs that describe your phenomenon and your interest in it.

**You will turn this in using your own GitHub repository.**
