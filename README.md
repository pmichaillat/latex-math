# LaTeX Commands to Write Math

This repository contains a [LaTeX](https://github.com/latex3/latex2e) style file that defines commands to simplify writing mathematical expressions while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/e/.

## Usage

1. Add the file `math.sty` to the directory containing your LaTeX document.
2. Add `\usepackage{math}` to the preamble of your document.
3. Use the [commands](https://pascalmichaillat.org/e/) defined in `math.sty`.

Standard LaTeX commands remain functional, with a few exceptions: some rarely used text symbols (`\oe`, `\o`, `\P`) have been redefined to insert frequently used mathematical symbols. These changes aim to enhance mathematical typesetting in scientific documents.

## Software

+ The commands were developed using TeX Live 2023 on MacOS. 
+ Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-math/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).