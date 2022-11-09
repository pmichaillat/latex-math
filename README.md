# latex-math

LaTeX commands that make math easy to type and easy to read.

## Goal

The commands in `math.sty` are designed to make it easy to typeset math in LaTeX. They include most of the items that I use repeatedly. Of course many LaTeX editors provide functionalities to make typesetting easier. An additional advantage of these commands, however, is that they are designed so the formulas in LaTeX look as much as possible like the formulas on paper. So it is easier to check the math or write proofs directly in LaTeX.

## How to use

- Add `math.sty` to the folder with your LaTeX files
- Insert `\usepackage{math}` in the preamble of your document
- Use the commands defined in `math.sty` 
– Standard math commands should not be affected so you can continue to use those too

## Some useful commands

### Statistical operators

- Expectation operator:
 
    * `\E` produces $\mathbb{E}$
    * `\E[X]` produces $\mathbb{E}_X$
    * `\E{Y}` produces $\mathbb{E}[Y]$
    * `\E[X]{Y}` produces $\mathbb{E}_X[Y]$

- Probability operator:

    * `\P` produces $\mathbb{P}$
    * `\P[X]` produces $\mathbb{P}_X$
    * `\P{Y}` produces $\mathbb{P}[Y]$
    * `\P[X]{Y}` produces $\mathbb{P}_X[Y]$

### Greek letters

- Lower-case Greek letters are reduced to one character: `\a` gives $\alpha$ and so on
- Upper-case Greek letters are reduced to one character: `\L` gives $\Lambda$ and so on

### Calligraphic letters

- Calligraphic letters are reduced to two characters: `\Ac` gives $\mathcal{A}$ and so on

### Brackets

- `\bp{x}` gives $(x)$ with appropriately scaling parenthesis
- `\bs{x}` gives $[x]$ with appropriately scaling square brackets
- `\bc{x}` gives ${x}$ with appropriately scaling curly brackets
- `\abs{x}` gives $|x|$ with appropriately scaling straight brackets

### Derivatives

- `\pd{x}{y}` gives the partial derivative of $x$ with respect to $y$: $\frac{\partial x}{\partial y}$
- `\pdx{x}{y}` gives the same partial derivative in text mode: $\partial x/\partial y$
- `\pdl{x}{y}` gives the partial elasticity of $x$ with respect to $y$: $\frac{\partial\ln x}{\partial\ln y}$
- `\od{x}{y}` gives the ordinary derivative of $x$ with respect to $y$: $\frac{d x}{d y}$
- `\odx{x}{y}` gives the same ordinary derivative in text mode: $d x/d y$
- `\odl{x}{y}` gives the ordinary elasticity of $x$ with respect to $y$: $\frac{d\ln x}{d\ln y}$

### Other commands

There are many other commands to be discovered in the file `math.sty`. What they produce is hopefully self-explanatory.
