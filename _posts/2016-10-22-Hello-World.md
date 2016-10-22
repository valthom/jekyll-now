---
layout: post
title: "Hey there! First post with mathjax support (hopefully)"
use_math: true
---
<script type="text/javascript"
src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

    {% if page.use_math %}
          {% include mathjax_support %}
              {% endif %}

This is my first post
$a^2 + b^2 = c^2$

$$a^2 + b^2 = c^2$$

\\[ \mathbf{X} = \mathbf{Z} \mathbf{P^\mathsf{T}} \\]

* First
	- Second
	- second
* Secundo
	- hey

\begin{equation}
	e^{\pi i} + 1 = 0
\end{equation}

Let's test some inline math $x$, $y$, $x_1$, \\$y_1 \\$.

Now a inline math with special character: $|\psi\rangle$, $x'$, $x^\*$.

Test a display math:
$$
\psi_1\rangle = a|0\rangle + b|1\rangle
$$

it O.K.?

t a display math with equation number:
\begin{equation}
|\psi_1\rangle = a|0\rangle + b|1\rangle
\end{equation}
Is it O.K.?

Test a display math with equation number:
$$
\begin{align}
|\psi_1\rangle &= a|0\rangle + b|1\rangle \\\\
|\psi_2\rangle &= c|0\rangle + d|1\rangle
\end{align}
$$
Is it O.K.?

And test a display math without equaltion number:
$$
\begin{align\*}
|\psi_1\rangle &= a|0\rangle + b|1\rangle \\\\
|\psi_2\rangle &= c|0\rangle + d|1\rangle
\end{align\*}
$$
Is it O.K.?

Test a display math with equation number:
\begin{align}
|\psi_1\rangle &= a|0\rangle + b|1\rangle \\\\
|\psi_2\rangle &= c|0\rangle + d|1\rangle
\end{align}
Is it O.K.?

And test a display math without equaltion
number:
\begin{align\*}
|\psi_1\rangle &= a|0\rangle +
b|1\rangle \\\\
|\psi_2\rangle &= c|0\rangle +
d|1\rangle
\end{align\*}
Is it O.K.?
