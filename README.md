# sdi_memory


para compilar:
```bash
./latexdockercmd.sh pdflatex main.tex
./latexdockercmd.sh bibtex main
./latexdockercmd.sh pdflatex main.tex
./latexdockercmd.sh pdflatex main.tex
```

or install
```bash
sudo apt install texlive-lang-spanish texlive-science 
sudo apt install texlive-bibtex-extra biber
sudo apt install texlive texlive-fonts-recommended
sudo apt install texlive-latex-extra
```
and texmaker or pdflatex and bibtex separetlly
and run:
```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```


 o comitear y esperar que corra el pipeline

 o correr con docker:
 ```bash
 https://hub.docker.com/r/blang/latex/#!
 ```