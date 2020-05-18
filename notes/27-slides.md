---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

Virtual Clicker

https://pollev.com/dannycaballe980

Notes for today

http://dannycaballero.info/phy482msu_s2020/notes/27-slides.html

</section>

<section data-markdown>

## Announcements

* Quiz 5 (This Friday)
  * Write a quiz that deals with reflection and transmission of EM Waves
  * [Review Criteria now posted](../quizrubric.html)
  * Turn in using GradeScope
* Group Project
  * Great job finding partners!
  * Remember to tell me about your repository.

</section>

<section data-markdown>

What do y'all want to learn about after this week?
1. Potential theory and gauge (Ch. 10)
2. Accelerated charges and radiation (Ch. 11)
3. Special relativity (Ch. 12)

</section>

<section data-markdown>

An EM wave passes from air to metal, what does **your intution** say happens to the wave in the metal?

1. It will be amplified because of free electrons
2. It will die out over some distance
3. It will be blocked right at the interface because there's no E field in a metal
4. Not sure

</section>

<section data-markdown>

An EM wave passes from air to metal, which do you think is **most likely** the physics will give us?

1. It will be amplified because of free electrons
2. It will die out over some distance
3. It will be blocked right at the interface because there's no E field in a metal
4. Not sure

</section>


<section data-markdown>

Suppose I stick some charge $\rho_f$ down somewhere in a metal (with conductivity $\sigma$). What does $\rho(t)$ look like if we can invoke Ohm's law ($\mathbf{J} = \sigma \mathbf{E}$)? *Hint: Think about charge conservation.*

1. $\rho(t) = \rho_f \sin(\sigma t/\varepsilon_0)$
2. $\rho(t) = \rho_f \cos(\sigma t/\varepsilon_0)$
3. $\rho(t) = \rho_f e^{-\sigma t/\varepsilon_0}$
4. $\rho(t) = \rho_f e^{-\varepsilon_0 t/\sigma}$
5. Something else

Note:
* Correct Answer: C

</section>

<section data-markdown>

Consider a good conductor ($\sigma \sim 10^8$ S/m), how long roughly does it take for free charge to dissipate ($t \sim \varepsilon_0/\sigma$)?

1. 10$^{-19}$s
2. 10$^{-12}$s
3. 10$^{-8}$s
4. 10$^{12}$s
5. Something else

Note:
* Correct Answer: A

</section>

<section data-markdown>

Given our estimates of collision times (10$^{-14}$s), for what kinds of light is our analysis not so great for?

1. X-Rays ($\sim 10^{18}$ Hz)
2. Visible light ($\sim 10^{15}$ Hz)
3. IR ($\sim 10^{13}$ Hz)
4. Radio ($\sim 10^{8}$ Hz)
5. More than one of these

Note:
* Correct Answer: E (it's A and B)

</section>

<section data-markdown>

What does this ansatz attempt (i.e., using $\sim e^{(kz-i\omega t)}$) remind you for this?

1. Solving the simple harmonic oscillator
2. Solving the damped harmonic oscillator
3. Solving the driven harmonic oscillator
4. Some other set up

Note:
* Correct Answer: is likely B

</section>

<section data-markdown>

With the proposed solution, $\widetilde{\mathbf{E}} = \widetilde{\mathbf{E}}_0 e^{i(kz-\omega t)}$, what equation does $k$ satisfy?

Think about the wave equation: $\nabla^2 \mathbf{E} = \mu \sigma \dfrac{\partial \mathbf{E}}{\partial t}+\mu \varepsilon \dfrac{\partial^2 \mathbf{E}}{\partial t^2}$

1. $k^2 = i \omega \mu \sigma + \omega^2 \sigma \varepsilon$
2. $k^2 = \omega \mu \sigma + i \omega^2 \sigma \varepsilon$
3. $k = \omega \mu \sigma + i \omega^2 \sigma \varepsilon$
4. $k = i \omega \mu \sigma + \omega^2 \sigma \varepsilon$
5. Something else

Note:
* Correct Answer: A

</section>
