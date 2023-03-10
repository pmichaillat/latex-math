# Minimalist LaTeX Commands to Write Math

This repository contains a collection of minimalist commands to easily write mathematical expressions with LaTeX—while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/d3/.

## Features

The commands are tailored to write math in economics and other social sciences, although they might also be helpful to write math in other fields. The commands introduce the following functionalities:

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
+ Use the commands defined in `math.sty`.
+ Existing math commands continue to work as usual. 
+ A few text commands are modified (such as `\oe`, `\o`, `\b`, `\P`) and do not produce their usual output. These commands used to insert text symbols that are rarely used in scientific writing, and now insert common mathematical symbols, so hopefully the modification is not problematic. 

## License

The content of this repository is licensed under the terms of the MIT License.
