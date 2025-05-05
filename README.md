# LaTeX Commands to Write Math

This repository contains a collection of commands to easily write mathematical expressions with [LaTeX](https://github.com/latex3/latex2e)—while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/e/.

## Usage

+ Add the LaTeX style file `math.sty` to the folder with your LaTeX document.
+ Insert `\usepackage{math}` in the preamble of your LaTeX document.
+ Use the [commands](https://pascalmichaillat.org/e/) defined in `math.sty`.
+ Existing LaTeX commands continue to work as usual, with the exception of a few text commands that do not produce their usual output (such as `\oe`, `\o`, `\P`). These commands used to insert text symbols that are rarely used in scientific writing, and now insert common mathematical symbols, so hopefully the modification is not problematic. 

## Software

The commands were developed and validated with TeX Live 2023 on MacOS. 

Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-math/issues) to help improve compatibility

## License

This repository is licensed under the [MIT License](LICENSE.md).