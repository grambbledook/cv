## CV

This is my CV as code. <br> 

For recruiters who have made it to this point, here is the link to my up-to-date cv: 
- [latest-bs.pdf](cv-bs.pdf)  - My latest CV with a touch of BS (Business Specifics).
- [latest.pdf](cv.pdf) - Lean CV with just essentials for those who are not interested in BS. 

### Generate PDF


To install LaTeX (`texlive-fonts-extra` carries XCharter, Fira Sans and Font
Awesome, which `cvstyle.sty` sets the whole CV in):
```sh
apt install texlive-latex-base texlive-latex-recommended texlive-latex-extra \
            texlive-fonts-recommended texlive-fonts-extra
```

To generate PDF (twice, so the page-count in the footer settles):
```bash
pdflatex cv.tex && pdflatex cv.tex
```
