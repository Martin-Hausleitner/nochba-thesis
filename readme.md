# Nochba Diploma Thesis

This is the repository for my diploma thesis. 

# cmd to build tex
    
    ```bash
    pdflatex -synctex=1 -interaction=nonstopmode -file-line-error -shell-escape -output-directory=build thesis.tex
    ```
    
    ```bash 
    biber build/thesis
    ```
   