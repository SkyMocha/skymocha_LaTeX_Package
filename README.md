# skymocha_LaTeX_Package

For Calculus Classes &amp; Other Stuff I Guess? (figure out description later)

## Requirnments

- amsmath
- amssymb

<!-- $\usepackage{amsmath}$
$\usepackage{amssymb}$ -->

## Commands

### Header

`\header` $\to$ replacement for `\maketitle`

`\header{Class}{Teacher/Section}{Name}{Week #}{Start Date}{End Date}`

`\header{Math 111}{Perkinson F02}{Skye Kycnenthal}{3}{9/12}{9/15}`

### XER

`\xer` $\to$ returns x is an element in the set of all real numbers:

$$
x \in \mathbb{R} :
$$

### Limdef

`\limdef` $\to$ formal definition of a limit

`\limdef{c}{f(x)}{L}` returns:

$$
\forall \epsilon > 0 \;\;
\exists \delta > 0 \;\; \textrm{ such that }
\;\; \textrm{if } 0 < \mid x - c \mid < \delta,
\;\; \textrm{then}
\;\; \mid f(x) - L \mid < \epsilon
$$

### Limlim

`\limlim` $\to$ replacement for $\lim$

`\limlim{x}{k}{k x}` equals:

$$
\lim_{x \to k}{k x}
$$

### Picewise

`\picewise` $\to$ short-hand for picewise functions

`\picewise{f(x)}{expression 1}{expression 2}`

$$
\begin{equation}
    f(x) =
    \lbrace
    \begin{array}{lr}
        expression 1\\
        expression 2
    \end{array}
\end{equation}
$$

### Misc

`\meow` $\to$ returns nya

## Discliamer

I'm tired. I will fix this later.

## Lisence

UHHH CC I guess. Just credit me.
