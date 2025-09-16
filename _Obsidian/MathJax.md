> [Гайд по MathJax](https://www.bearnok.com/grva/it/knowledge/software/mathjax)

# ОГЛАВЛЕНИЕ
1. [[MathJax#Symbols|Символы]]
	1. [[MathJax#[Unscaled parentheses]|Скобки]]
	2. [[MathJax#[Scaled parentheses]|Скобки]]
	3. [[MathJax#[Scaled parentheses]|Скобки]]
2. [[MathJax#Logical symbols|Логические символы]]
3. [[MathJax#Operators|Математические операторы]]
5. [[MathJax#Arrows|Стрелки]]
6. [[MathJax#Special symbols|Дополнительные символы]]
7. [[MathJax#Trigonometry|Тригонометрические функции]]
9. [[MathJax#Greek letters|Греческий алфавит]]
10. [[MathJax#Fonts|Шрифты и буквоподобные символы]]
11. [[MathJax#Spaces|Пробелы]]
12. [[MathJax#Accents and marks|Модификаторы букв и прочие диакритические знаки]]

---
## Symbols

- Inline formulas enclose \ ( ... \ )
- Displayed formulas \ [ ... \ ]
- Curly braces {} to group pieces of formulas
- Superscripts ( ^ ) and subscripts ( _ ) : $x_1^e$
- Fractions:
	- $\frac{a}{b}$ \\frac{a}{b}
	- ${x}\over{y}$ {x}\\over{y}

## Parentheses

### Unscaled parentheses

| Symbol                | Code                |
| --------------------- | ------------------- |
| $(...)$               | (...)               |
| $[...]$               | [...]               |
| ${ ... }$             | { ... }             |
| $\vert ... \vert$     | \vert ... \vert     |
| $\Vert ... \Vert$     | \Vert ... \Vert     |
| $\langle ... \rangle$ | \langle ... \rangle |
| $\lceil ... \rceil$   | \lceil ... \rceil   |
| $\lfloor ... \rfloor$ | \lfloor ... \rfloor |

### Scaled parentheses

| Symbol                           | Code                           |
| -------------------------------- | ------------------------------ |
| $\left( ... \right)$             | \left( ... \right)             |
| $\left[ ... \right]$             | \left[ ... \right]             |
| $\left{...\right}$               | \left{ ... \right}             |
| $\left\vert ... \right\vert$     | \left\vert ... \right\vert     |
| $\left\Vert ... \right\Vert$     | \left\Vert ... \right\Vert     |
| $\left\langle ... \right\rangle$ | \left\langle ... \right\rangle |
| $\left\lceil ... \right\rceil$   | \left\lceil ... \right\rceil   |
| $\left\lfloor ... \right\rfloor$ | \left\lfloor ... \right\rfloor |

### Hidden parentheses

| Symbol               | Code               |
| -------------------- | ------------------ |
| $\left{ ... \right.$ | \left{ ... \right. |
| $\left. ... \right]$ | \left. ... \right] |

- manual adjustment: $\Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)$ \Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)

---
## Logical symbols

| Symbol | Code      |
| ------ | --------- |
| <      | \lt       |
| >      | \gt       |
| ≤      | \le       |
| ≤      | \leq      |
| ≦      | \leqq     |
| ⩽      | \leqslant |
| ≥      | \ge       |
| ≥      | \geq      |
| ≧      | \geqq     |
| ⩾      | \geqslant |
| ≠      | \neq      |
| ∧      | \land     |
| ∨      | \lor      |
| ¬      | \lnot     |
| ∀      | \forall   |
| ∃      | \exists   |
| ∄      | \nexists  |
| ⊤      | \top      |
| ⊥      | \bot      |
| ⊢      | \vdash    |
| ⊨      | \vDash    |
| ≈      | \approx   |
| ∼      | \sim      |
| ≃      | \simeq    |
| ≅      | \cong     |
| ≡      | \equiv    |
| ≺      | \prec     |
| ⊲      | \lhd      |
| ∴      | \refore   |

---
## Operators

| Symbol | Code    |
| ------ | ------- |
| ×      | \times  |
| ÷      | \div    |
| ±      | \pm     |
| ∓      | \mp     |
| ⋅      | \cdot   |
| ⋆      | \star   |
| ∗      | \ast    |
| ⊕      | \oplus  |
| ∘      | \circ   |
| ∙      | \bullet |
### Functional symbols

| Symbol                             | Code                             |
| ---------------------------------- | -------------------------------- |
| $\sqrt{x^3}$                       | \sqrt{x^3}                       |
| $\sqrt[3]{\frac xy}$               | \sqrt[3]{\frac xy}               |
| $\ln(x)$                           | \ln(x)                           |
| $\log_{2}(x)$                      | \log_{2}(x)                      |
| $\sum_{n=1} ^{N} n$                | \sum_{n=1} ^{N} n                |
| $\prod_{n=1} ^{N} n$               | \prod_{n=1} ^{N} n               |
| $\int_{0} ^{\infty} x dx$          | \int_{0} ^{\infty} x dx          |
| $\iint_{0} ^{\infty} x dx$         | \iint_{0} ^{\infty} x dx         |
| $\iiint_{0} ^{\infty} x dx$        | \iiint_{0} ^{\infty} x dx        |
| $\lim_{x \to \infty} {1 \over x }$ | \lim_{x \to \infty} {1 \over x } |
| $\max(1,2,3)$                      | \max(1,2,3)                      |
| $\min(3,4,5)$                      | \min(3,4,5)                      |
| ${n+1 \choose 2k}$                 | {n+1 \choose 2k}                 |
| $\binom{n+1}{2k} (n+12k)$          | \binom{n+1}{2k} (n+12k)          |

### Set symbols

| Symbol | Code        |
| ------ | ----------- |
| ∪      | \cup        |
| ∩      | \cap        |
| ∖      | \setminus   |
| ⊂      | \subset     |
| ⊆      | \subseteq   |
| ⊊      | \subsetneq  |
| ⊃      | \supset     |
| ∈      | \in         |
| ∉      | \notin      |
| ∅      | \emptyset   |
| ∅      | \varnothing |

---
## Arrows

| Symbol | Code            |
| ------ | --------------- |
| →      | \to             |
| →      | \rightarrow     |
| ←      | \leftarrow      |
| ⇒      | \Rightarrow     |
| ⇐      | \Leftarrow      |
| ⇔      | \Leftrightarrow |
| ↦      | \mapsto         |

---
## Special symbols

| Symbol | Code     |
| ------ | -------- |
| ∞      | \infty   |
| ∇      | \nabla   |
| ∂      | \partial |
| ℑ      | \Im      |
| ℜ      | \Re      |
| …      | \ldots   |
| ⋯      | \cdots   |
| ℓ      | \ell     |

---
## Trigonometry

| Symbol      | Code      |
| ----------- | --------- |
| $\sin x$    | \sin x    |
| $\cos x$    | \cos x    |
| $\tan x$    | \tan x    |
| $\cot x$    | \cot x    |
| $\sec x$    | \sec x    |
| $\csc x$    | \csc x    |
| $\arcsin x$ | \arcsin x |
| $\arccos x$ | \arccos x |
| $\arctan x$ | \arctan x |

---
## Greek letters

### Lowercase

| Symbol | Code        |
| ------ | ----------- |
| α      | \alpha      |
| β      | \beta       |
| γ      | \gamma      |
| δ      | \delta      |
| ϵ      | \epsilon    |
| ε      | \varepsilon |
| ζ      | \zeta       |
| η      | \eta        |
| θ      | \theta      |
| ϑ      | \vartheta   |
| ι      | \iota       |
| κ      | \kappa      |
| λ      | \lambda     |
| μ      | \mu         |
| ν      | \nu         |
| ξ      | \xi         |
| ο      | \omicron    |
| π      | \pi         |
| ϖ      | \varpi      |
| ρ      | \rho        |
| ϱ      | \varrho     |
| σ      | \sigma      |
| ς      | \varsigma   |
| τ      | \tau        |
| υ      | \upsilon    |
| ϕ      | \phi        |
| φ      | \varphi     |
| χ      | \chi        |
| ψ      | \psi        |
| ω      | \omega      |

### Uppercase

| Symbol | Code     |
| ------ | -------- |
| Γ      | \Gamma   |
| Δ      | \Delta   |
| Θ      | \Theta   |
| Λ      | \Lambda  |
| Ξ      | \Xi      |
| Π      | \Pi      |
| Σ      | \Sigma   |
| Υ      | \Upsilon |
| Ψ      | \Psi     |
| Ω      | \Omega   |

>Note: other greek uppercase lettere are the same as Roman letter.

---
## Fonts

| Symbol                                          | Code                                          |
| ----------------------------------------------- | --------------------------------------------- |
| $\mathbb{N}$                                    | \mathbb{N}                                    |
| $\mathbb{Z}$                                    | \mathbb{Z}                                    |
| $\mathbb{Q}$                                    | \mathbb{Q}                                    |
| $\mathbb{I}$                                    | \mathbb{I}                                    |
| $\mathbb{R}$                                    | \mathbb{R}                                    |
| $\mathbb{C}$                                    | \mathbb{C}                                    |
| $\text{ is an even number}$                     | \text{ is an even number}                     |
| $\Bbb{blackboard bold}$                         | \Bbb{blackboard bold}                         |
| $\mathbf{boldface}$                             | \mathbf{boldface}                             |
| $\mathit{italics}$                              | \mathit{italics}                              |
| $\pmb{boldfaced italics}$                       | \pmb{boldfaced italics}                       |
| $\mathtt{ for typewriter}$                      | \mathtt{ for typewriter}                      |
| $\mathrm{roman font}$                           | \mathrm{roman font}                           |
| $\mathsf{sans-serif font}$                      | \mathsf{sans-serif font}                      |
| $\mathcal{calligraphic letters}$                | \mathcal{calligraphic letters}                |
| $\mathscr{script letters}$                      | \mathscr{script letters}                      |
| $\mathfrak{Fraktur (old German style) letters}$ | \mathfrak{Fraktur (old German style) letters} |

---
## Spaces

| Symbol                | Code                |
| --------------------- | ------------------- |
| $Thin \ space$        | Thin \ space        |
| $Normal \; space$     | Normal \; space     |
| $Big \quad space$     | Big \quad space     |
| $Bigger \qquad space$ | Bigger \qquad space |

---
## Accents and marks

| Symbol                    | Code                    |
| ------------------------- | ----------------------- |
| $\hat{x}$                 | \hat{x}                 |
| $\overline{xyz}$          | \overline{xyz}          |
| $\vec{x}$                 | \vec{x}                 |
| $\widehat{xy}$            | \widehat{xy}            |
| $\bar{x}$                 | \bar{x}                 |
| $\overrightarrow{xy}$     | \overrightarrow{xy}     |
| $\overleftrightarrow{xy}$ | \overleftrightarrow{xy} |
| $\dot{x}$                 | \dot{x}                 |
| $\ddot{x}$                | \ddot{x}                |
