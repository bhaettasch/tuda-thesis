# tuda-thesis
Stencil for writing a thesis in the corporate design of TU Darmstadt

## Compile

    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
    biber.exe %
    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
    pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex