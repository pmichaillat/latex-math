# LaTeX Commands to Write Math

This repository contains a [LaTeX](https://github.com/latex3/latex2e) style file that defines commands to simplify writing mathematical expressions while automatically respecting the rules of mathematical typography.

## Documentation

The commands are documented at https://pascalmichaillat.org/e/.

## Usage

1. Add the file `math.sty` to the directory containing your LaTeX document.
2. Add `\usepackage{math}` to the preamble of your document.
3. Use the [commands](https://pascalmichaillat.org/e/) defined in `math.sty`.

## Smoke test

Compile `smoketest.tex` (for example with `pdflatex smoketest.tex`) to verify that all commands in `math.sty` work on your system. The compiled file should look like `smoketest.pdf`.

The file `math.sty` is self-contained and loads required packages (`amsmath`, `amssymb`, `xparse`, `accents`, and `dsfont`). If your project also loads other math and font packages, conflicts can occur—even if the smoke test works. If needed, remove overlapping package loads or adapt `math.sty` locally to match your existing setup. For instance, if you use the templates [latex-paper](https://github.com/pmichaillat/latex-paper) or [latex-book](https://github.com/pmichaillat/latex-book) or [latex-presentation](https://github.com/pmichaillat/latex-presentation) for your paper, book, or presentation, then only `xparse` and  `accents` are required here. Those templates load other packages that provide overlapping math and font functionality, so loading `amsmath`, `amssymb`, or `dsfont` again may be unnecessary or may create conflicts.

## Software

+ The commands are currently operational with TeX Live 2025 on macOS.
+ Other LaTeX distributions and operating systems may require minor adjustments. Please [report any issues](https://github.com/pmichaillat/latex-math/issues) to help improve compatibility.

## License

This repository is licensed under the [MIT License](LICENSE.md).