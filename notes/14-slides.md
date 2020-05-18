---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

A capacitor ($C$) and an inductor ($L$) are in parallel. What is the effective impedance, $Z_{eff}$ across these elements?

1. $C + L$
2. $i\omega C + i\omega L$
3. $1/(i\omega C + i\omega L)$
4. $1/i\omega C + i\omega L$
5. Something else?

Note:

</section>




<section data-markdown>

AC voltage $V$ and current $I$ vs time $t$ are as shown:

<img src="./images/IV_graphs.png" align="center" style="width: 600px";/>

The graph shows that..

1. $I$ leads $V$  ( $I$ peaks before $V$ peaks )
2. $I$ lags $V$    ( $I$ peaks after $V$ peaks )
3. Neither

Note:
* Correct Answer: B

</section>

<section data-markdown>

Consider an RC circuit attached to a sinusoidally driven voltage source. If at $t=0$ we turn on the source, $I(t=0)=\frac{V_0}{R}$. Then the current follows this solution,

$$I(t) = \dfrac{V_0}{\sqrt{R^2+\frac{1}{\omega^2C^2}}}\cos(\omega t + \phi) - \left(\dfrac{V_0}{R}-\dfrac{V_0\cos\phi}{\sqrt{R^2+\frac{1}{\omega^2C^2}}}\right)e^{-t/RC}$$

What happens to the long term current as $\omega \rightarrow 0$?

1. goes to zero
2. goes to $\dfrac{V_0}{R}$
3. goes to infinity
4. Something else

Note:
* Correct answer: A


</section>

<section data-markdown>

Consider an RC circuit attached to a sinusoidally driven voltage source. If at $t=0$ we turn on the source, $I(t=0)=\frac{V_0}{R}$. Then the current follows this solution,

$$I(t) = \dfrac{V_0}{\sqrt{R^2+\frac{1}{\omega^2C^2}}}\cos(\omega t + \phi) - \left(\dfrac{V_0}{R}-\dfrac{V_0\cos\phi}{\sqrt{R^2+\frac{1}{\omega^2C^2}}}\right)e^{-t/RC}$$

What happens to the long term current as $\omega \rightarrow \infty$?

1. goes to zero
2. goes to $\dfrac{V_0}{R}$
3. goes to infinity
4. Something else

Note:
* Correct answer: B


</section>
