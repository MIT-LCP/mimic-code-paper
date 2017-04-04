# Paper describing the MIMIC Code Repository

This repository contains the content  used to create the official citation for the *MIMIC Code Repository*. The citation is:

> *Forthcoming*

Researchers using MIMIC database should also cite the following paper:

> MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data 3:160035 doi: 10.1038/sdata.2016.35 (2016). http://www.nature.com/articles/sdata201635

For more information on MIMIC-III, see: http://mimic.physionet.org/

## Generate the PDF

pandoc "main.md" -o "main.pdf" --bibliography="references.bib" --csl="ref_format.csl" -V fontsize=12pt -V papersize=a4paper -V documentclass:article -N --latex-engine=xelatex 
