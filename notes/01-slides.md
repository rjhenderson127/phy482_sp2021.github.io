---
layout: slide
theme: white
transition: slide
---

<section data-markdown>
## Welcome to PHY 482

### Electrodynamics

Prof. Danny Caballero

</section>

<section data-markdown>
### Contacting Danny

Office: 1310-A BPS

Email: <caballero@pa.msu.edu>

Cell phone: 517-420-5330 (texting is fine)

</section>

<section data-markdown>
### Important Sites

* Course Webpage: <http://dannycab.github.io/phy482msu_s2020/>
* Slack Team: <https://phy482msuspring2020.slack.com/>

</section>

<section data-markdown>

### Course Activities
* Projects:
  * 2 of them; Feb 28 & Apr 28 - 20% each
* In-Class Quizzes:
  * 7 of them; Every other Friday; 1 dropped - 20%
* Homework:
  * 14 of them; Due on Fridays by 5pm; 1 dropped - 40%
* Clickers:
  * Participation; no credit

[Much more detail on website](http://dannycab.github.io/phy482msu_s2020/)

</section>

<section data-markdown>

Learning is a social and collaborative act!

### Homework Help Session

**Once per week (Location TBD)**

Question to you: When should we do this?

Reminder: Homework is due on Fridays.

</section>

<section data-markdown>

## This Week!!!

* Homework 1 is already up (Due Fri. Jan. 10 at 5pm)
* Submitted on gradescope.com

* Read (seriously do this!)
  * Griffiths Ch 7.1.1-7.1.2 (Review? Chs 1-6)
* [Download Anaconda distribution of Python](https://www.continuum.io/downloads)

**Stay up-to-date by checking website, calendar, and discussion forum regularly.**

</section>

<section data-markdown>

### Computational Homework problems

* We will be using Python on homework problems this semester.
* Homework solutions should take the form of a Jupyter notebook, which you will upload using GitHub.
* If you get stuck somewhere, post on Slack, so your classmates benefit from your question.

</section>

<section data-markdown>

### Projects

#### Individual Project (Feb. 28)
* Literature review of some interesting topic in E&M (4-5 pages)
* Homework questions will support you on this
  * See syllabus for sample questions
* Paper should be typed, inline references, bibliography, etc.
* Evaluation rubric is online

</section>

<section data-markdown>

### Projects

#### Pair Project (Apr. 28)
* Poster presentation of an original contribution (theory and computation)
* Homework questions will support you on this
  * See syllabus for sample questions
* Can be something that has been done before that you just extend
* Evaluation rubric is online
* There will be a significant self-evaluation component to this also

</section>

<section data-markdown>

# Questions?

</section>

<section data-markdown>

## What do you think PHY 482 is about?

</section>

<section data-markdown>

### Electromagnetism is the foundational field theory of physics

Think about everything you already know about electromagnetism (it's a lot already!).

Work with a partner to map out the electromagnetism concepts that you know and how they are related to each other.

</section>

<section data-markdown>

5 charges, q, are arranged in a regular pentagon, as shown.
What is the E field at the center?

<img src ="./images/5charges.png" align="center" style="width: 250px";/>

1. Zero
2. Non-zero
3. Really need trig and a calculator to decide

Note:
CORRECT ANSWER: A
</section>


<section data-markdown>

<img src ="./images/zappa.jpeg" align="right" style="width: 100px";/>

1 of the 5 charges has been removed, as shown. What’s the E field at the center?

<img src ="./images/4charges.png" align="center" style="width: 400px";/>

1. $+(kq/a^2)\hat{y}$
2. $-(kq/a^2)\hat{y}$
3. 0
4. Something entirely different!
5. This is a nasty problem which I need more time to solve



Note:
CORRECT ANSWER:  B
Superposition!

</section>

<section data-markdown>

To find the E-field at P from a thin line (uniform charge density $\lambda$):

<img src ="./images/linecharge.png" align="right" style="width: 400px";/>
$$ \mathbf{E}(\mathbf{r}) = \dfrac{1}{4\pi\varepsilon_0}\int \dfrac{\lambda dl'}{\mathfrak{R}^2}\hat{\mathfrak{R}}$$
What is $\mathfrak{R}$?

1. $x$
2. $y'$
3. $\sqrt{dl'^2 + x^2}$
4. $\sqrt{x^2+y'^2}$
5. Something else

Note:
CORRECT ANSWER: D

</section>


<section data-markdown>

What do you expect to happen to the field as you get really far from the rod?

$$E_x = \dfrac{\lambda}{4\pi\varepsilon_0\}\dfrac{L}{x\sqrt{x^2+L^2}}$$

1. $E_x$ goes to 0.
2. $E_x$ begins to look like a point charge.
3. $E_x$ goes to $\infty$.
4. More than one of these is true.
5. I can't tell what should happen to $E_x$.

Note:
CORRECT ANSWER: D (A and B)

</section>



<section data-markdown>

Given the location of the little bit of charge ($dq$), what is $|\vec{\mathfrak{R}}|$?

<img src ="./images/sphereintegrate.png" align="left" style="width: 300px";/>


1. $\sqrt{z^2+r'^2}$
2. $\sqrt{z^2+r'^2-2zr'\cos\theta}$
3. $\sqrt{z^2+r'^2+2zr'\cos\theta}$
4. Something else

Note:
CORRECT ANSWER: B


</section>


<section data-markdown>

Which of the following are vectors?

(I) Electric field, (II) Electric flux, and/or (III) Electric charge

1. I only
2. I and II only
3. I and III only
4. II and III only
5. I, II, and II

Note:
* CORRECT ANSWER: A

</section>

<section data-markdown>
A positive point charge $+q$ is placed outside a closed cylindrical surface as shown.  The closed surface consists of the flat end caps (labeled A and B) and the curved side surface (C). What is the sign of the electric flux through surface C?

<img src="./images/ABC_cylinder.png" align="center" style="width: 600px";/>

1. positive
2. negative
3. zero
4. not enough information given to decide

Note:
* CORRECT ANSWER: B
* This is meant to be hard to visualize, next slide illustrates it better.

</section>

<section data-markdown>

Let's get a better look at the side view.

<img src="./images/ABC_cylinder_side.png" align="center" style="width: 350px";/>


</section>

<section data-markdown>

Which of the following two fields has zero divergence?

| I | II |
|:-:|:-:|
| <img src ="./images/cq_left_field.png" align="center" style="width: 400px";/> | <img src ="./images/cq_right_field.png" align="center" style="width: 400px";/> |

1. Both do.
2. Only I is zero
3. Only II is zero
4. Neither is zero
5. ???

Note:
* CORRECT ANSWER: B
* Think about dE/dx and dE/dy
* Fall 2016: 7 [34] 13 43 3; (Asked them to consider dvx/dx and dvy/dy) 3 [90] 3 4 0

</section>