## Academic Document LaTeX Template

A LaTeX template for creating academic purposes documents or more.

## Title Page Formatting

Only modify the `details.tex` file to modify the document title and its contents. It will automatically create the title page for you. This is done to avoid sloppy errors.

## Dependencies

> We use LuaLaTeX as the main latex compiler to address the color rendering issue persistent in multiple pdf viewers in Windows/Linux. 

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

> Omitted pdflatex compiling instructions since its obsolette.


