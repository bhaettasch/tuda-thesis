# [DEPRECATED] tuda-thesis

It is now officially recommended to use the latex package from https://github.com/tudace/tuda_latex_templates which can be installed from CTAN. Please do not use the old design for future theses.

Stencil for writing a thesis in the corporate design of TU Darmstadt

## Compile

    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
    biber.exe %
    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
