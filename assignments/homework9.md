---
layout: homework
use_math: true
title: Homework 9 (Due. Mar 13)
---

**Griffiths makes several statements and claims in Chapter 9 without really working out all the details. So please show what you feel are the main steps/big ideas in the questions below:**

## 1. The wave equation and boundary conditions

1. Starting with Maxwell’s equation in matter (in terms of the $\mathbf{D}$ and $\mathbf{H}$ fields) show that, for a linear homogeneous dielectric ($\mathbf{D} =  \varepsilon \mathbf{E}$, $\mathbf{B} = \mu \mathbf{H}$) with no free charges or currents ($\rho_{free} = 0$,  $\mathbf{J}_{free} = 0$), both the $\mathbf{E}$ and the $\mathbf{B}$ fields obey a wave equation with a wave speed given by $v=1/\sqrt{\mu \varepsilon}$.
2. Starting from the same equations as in part 1, rewrite them in integral form, and then briefly sketch out for us the reasoning which leads to all the boundary conditions on $\mathbf{E}$ and $\mathbf{B}$ at a planar interface between two different linear materials (labeled 1 and 2), with permittivities and permeabilities $\varepsilon_1$, $\mu_1$ and $\varepsilon_2$, $\mu_2$, respectively.  (Again, assume no free charge or current densities)

## 2. Reflection and Transmission

In Griffiths’ section 9.3.2, (Reflection and transmission at normal incidence) he finds reflection and transmission coefficients ($R$ and $T$). But he has made the assumption that $\mu_1 = \mu_2 = \mu_0$.
Drop that assumption, i.e. keep $\mu_1$ and $\mu_2$ general, and find the general formulas for $R$ and $T$.
To check, explictly confirm that $R+T=1$, still (as it must be).
*Hint: Don’t redo work Griffiths has done for you. Use whatever you need from section 9.3.2, just be careful not to use results where he has assumed $\mu_1 = \mu_2 = \mu_0$.   I claim you can express your final results for R and T purely as very simple functions of $\beta$ only!*

## 3. Perpendicular polarization

In the lecture notes (and/or Griffiths 9.3.3), we worked out the case of reflection and transmission at any angle. But we considered the case where the incident E-field is polarized in the plane of incidence.  Go through that section again, but work out the different case where the E-field is polarized perpendicular to the plane of incidence. (You may once again assume $\mu_1=\mu_2=\mu_0$.)
Specifically, what I mean by “work out” is:

1. Make a clear sketch (modeled on Griffiths figure 9.15) of the geometry and angles for this case. Then, write out what the four boundary conditions become in this case (i.e. modify Griffiths Eq 9.101 through 9.104 appropriately for this new situation).

2. Find the new "Fresnel Equations", i.e. a version of Eq 9.109, but for this polarization case. Explicitly check that your Fresnel equations reduce to the proper results at normal incidence!

3. Replicate Griffiths Figure 9.16, (but of course for this perpendicular polarization case.) **Use a Jupyter notebook** please. Assume $n_2/n_1=2.0$ Briefly, discuss what is similar, and what is different, about this case from what Griffiths solved. Is there a "Brewster’s angle" for your situation, i.e. a non-trivial angle where reflection becomes zero?

4. Again **in a Jupyter notebook**, replicate Griffiths Figure 9.17  (the one at the end of 9.3) but again, for this perpendicular polarization case, and again assuming $n_2/n_1=2.0$ and again using a computer to plot.  Show using your graph that $R+T=1$ for this situation, no matter what the angle. Briefly, comment on the physics!

**Turn in parts 3 and 4 using your GitHub repo.**



## 4. Paired Project Problem - Starting your pair project

This second project can (but doesn't have to) build on the project you just complted. It is a team project that you will complete with a partner. This project is meant to mimic the common practice of poster preparation and presentation. In a nutshell, you will conduct an original modeling project where you analytically and computationally model some E&M phenomenon of your choosing, prepare a poster of the project, and present it to your classmates and me. In working on this project, you will be trying to answer the following questions:

* What is the area of E&M that you are doing research on?
* What are the questions that you are trying to answer about this area?
* What theoretical models can be used to answer those questions?
* What analytical and computational work did you do to answer those questions?
* What were the resulting predictions that your work produced?
* What are the limitations of what you have done? * What are some remaining open questions?
* What did each member of your pair contribute?

There will be six homework problems to help scaffold your work and poster development. In this first homework problem, you and your partner will write up a single document that answers the following questions:

* Who are the partners in this team?
* What are you and your partner proposing to do?
* What area of E&M will you be conducting original calculations for?
* What source material are you drawing from?
* What has been done so far and what are you going to do? It's ok if it's a solved problem, but you will need to reproduce what has been done and extend it beyond what your reference material offers.

**As usual, you will turn in this document using GitHub.**
