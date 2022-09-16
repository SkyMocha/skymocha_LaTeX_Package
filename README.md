# skymocha_LaTeX_Package

For Calculus Classes &amp; Other Stuff I Guess? (figure out description later)

- [Requirements](#requirements)
- [Documentation](#documentation)
  - [Header](#header)
  - [Comment](#comment)
  - [XER](#xer)
  - [Limdef](#limdef)
  - [Limlim](#limlim)
  - [Picewise](#picewise)
  - [Misc](#misc)
- [Disclaimer](#discliamers)

## Requirements

- amsmath
- amssymb

<!-- $\usepackage{amsmath}$
$\usepackage{amssymb}$ -->

## Documentation

### Header

`\header` $\to$ replacement for `\maketitle`

`\header{Class}{Teacher/Section}{Name}{Week #}{Start Date}{End Date}`

`\header{Math 111}{Perkinson F02}{Skye Kycnenthal}{3}{9/12}{9/15}`

### Comment

`comment{aaa}` returns:

$$

    \hspace*{0.125in}\to\hspace*{0.175in} \textrm{aaa}


$$

Example:

`(1, 3) \comment{given}`

`f(x) = 2x + b \comment{given}`

`b = f(x) - 2x \comment {subtraction}`

`b = 3 - 2 \comment {substitution}`

`b = 1 \comment {subtraction}`

$$
    (1, 3) \hspace*{0.125in}\to\hspace*{0.175in} \textrm{given}\\
    f(x) = 2x + b \hspace*{0.125in}\to\hspace*{0.175in} \textrm{given}\\
    b = f(x) - 2x \hspace*{0.125in}\to\hspace*{0.175in} \textrm{subtraction}\\
    b = 3 - 2 \hspace*{0.125in}\to\hspace*{0.175in} \textrm{substitution}\\
    b = 1 \hspace*{0.125in}\to\hspace*{0.175in} \textrm{subtraction}
$$

### XER

`\xer` $\to$ returns x is an element in the set of all real numbers:

$$
x \in \mathbb{R} :
$$

### Limdef

`\limdef` $\to$ formal definition of a limit

`\limdef{c}{f(x)}{L}` returns:

$$
\forall \epsilon > 0 \hspace*{0.125in}
\exists \delta > 0 \hspace*{0.0625in} \textrm{  such that  }
\hspace*{0.0625in} \textrm{if  } 0 < \mid x - #1 \mid < \delta,
\hspace*{0.125} \textrm{then}
\hspace*{0.625} \mid #2 - #3 \mid < \epsilon
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
