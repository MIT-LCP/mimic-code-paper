# Paper describing the MIMIC Code Repository

This repository contains the content  used to create the official citation for the *MIMIC Code Repository*. The citation is:

> *Forthcoming*

Researchers using MIMIC database should also cite the following paper:

> MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data 3:160035 doi: 10.1038/sdata.2016.35 (2016). http://www.nature.com/articles/sdata201635

For more information on MIMIC-III, see: http://mimic.physionet.org/

## Generate the PDF

```
pandoc "main.md" -o "main.pdf" --bibliography="references.bib" --csl="vancouver.csl" -V fontsize=12pt -V papersize=a4paper -V documentclass:article -N --latex-engine=xelatex
```

## Acknowledgements

We based our markdown on [this markdown template for PhD theses](https://github.com/tompollard/phd_thesis_markdown),
and also took a look at a [JAMIA markdown template](https://github.com/erictleung/jamia-markdown-template)
to adapt our markdown file to fit JAMIA.

The Vancouver reference style language (CSL) file (`vancouver.csl`) was downloaded from the [Zotero Style Repository][zotero] (2016-06-19 21:20:29).

[zotero]: https://www.zotero.org/styles?q=vancouver
