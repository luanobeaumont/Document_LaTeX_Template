## Academic Document LaTeX Template

A LaTeX template for creating academic purposes documents or more.

## Title Page Formatting

Only modify the `details.tex` file to modify the document title and its contents. It will automatically create the title page for you. This is done to avoid sloppy errors.

## Dependencies

### Linux Debian

Installation & Compiling LuaLaTeX compiler:

```bash
sudo apt update
sudo apt install -y texlive-luatex latexmk
```

Make sure to navigate to current working directory.

```bash
cd /your_path/your_project_folder/
```

Compile main.tex(main/center latex file) using LuaLaTeX.

```bash
latexmk -lualatex main.tex
```


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



