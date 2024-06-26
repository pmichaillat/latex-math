# LaTeX Commands to Write Math

This repository contains a collection of commands to easily write mathematical expressions with [LaTeX](https://github.com/latex3/latex2e)—while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/d3/.

## Usage

+ Add the LaTeX style file `math.sty` to the folder with your LaTeX document.
+ Insert `\usepackage{math}` in the preamble of your LaTeX document.
+ Use the [commands](https://pascalmichaillat.org/d3/) defined in `math.sty`.
+ Existing LaTeX commands continue to work as usual, with the exception of a few text commands that do not produce their usual output (such as `\oe`, `\o`, `\P`). These commands used to insert text symbols that are rarely used in scientific writing, and now insert common mathematical symbols, so hopefully the modification is not problematic. 

## Software

The commands were tested and validated on a Mac with the MacTeX-2023 distribution. While they should also work on other operating systems and with other LaTeX distributions, compatibility cannot be guaranteed. Users on Windows or Linux systems, or those using different LaTeX distributions, may need to make minor adjustments. Please report any compatibility issues or bugs you encounter to help improve cross-platform support.

## License

The content of this repository is licensed under the terms of the MIT License.