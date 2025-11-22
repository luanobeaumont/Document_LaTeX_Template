## Academic Document LaTeX Template

A LaTeX template for creating academic purposes documents or more.

## Title Page Formatting

Only modify the `details.tex` file to modify the document title and its contents. It will automatically create the title page for you. This is done to avoid sloppy errors.

## How to compile (Linux)

Prefer use of `pdflatex` since I made this template in the pdflatex environment.

Follow these steps to generate a pdf output:

- Check if on the correct working directory (Where the main.tex files are located).

```bash
pwd
```
*MacOS, Windows, and Linux use the same command*

- Run this pdflatex recipe pdflatex->pdflatex->pdflatex (Run 3 times).

```bash
pdflatex main.tex
```



