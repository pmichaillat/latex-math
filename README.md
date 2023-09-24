# Minimalist LaTeX Commands to Write Math

This repository contains a collection of minimalist commands to easily write mathematical expressions with [LaTeX](https://github.com/latex3/latex2e)—while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/d3/.

## Features

The commands introduce the following functionalities:

+ Easily insert brackets that scale automatically
+ Easily list arguments of operators (expectation, probability, min, max, exponential, log, and so on), with surrounding brackets that scale automatically
+ Easily write derivatives and elasticities, in display and text
+ Easily type statistical commands (independent and identically distributed variables, almost sure convergence)
+ Easily type key blackboard letters
+ Easily type uppercase calligraphic letters
+ Easily type Greek letters
+ Easily insert accents that scale automatically

## Usage

+ Add the LaTeX style file `math.sty` to the folder with your LaTeX document.
+ Insert `\usepackage{math}` in the preamble of your LaTeX document.
+ Use the [commands](https://pascalmichaillat.org/d3/) defined in `math.sty`.
+ Existing LaTeX commands continue to work as usual, with the exception of a few text commands that do not produce their usual output (such as `\oe`, `\o`, `\P`). These commands used to insert text symbols that are rarely used in scientific writing, and now insert common mathematical symbols, so hopefully the modification is not problematic. 

## Software

These commands were developed on a Mac with the MacTeX-2021 distribution, and they continue to work with the MacTeX-2023 distribution. Hopefully, they should also work on other machines and with other distributions.

## License

The content of this repository is licensed under the terms of the MIT License.
