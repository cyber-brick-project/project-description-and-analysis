# project-description-and-analysis
Document for Cyber Brick Project description and analysis. Technology details included.

## Branches
 - `master` - Repo description
 - `doc` - Documentation in LaTeX

## Check submodule's READMEs
Some submodules may contain requirements for successful running

## doc - how to run

Requirements:
 - https://www.tug.org/mactex/
 - http://www.tug.org/fonts/getnonfreefonts/

Command to build documentation:
```
pdflatex -synctex=1 -interaction=nonstopmode Documentation.tex
```
