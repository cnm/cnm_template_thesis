Master of Science Dissertation template
=======================================

Template for the Master Thesis according to the regulations
published by the Scientific Council at IST.

For up-to-date regulations, please refer to:

::

    http://cd.ist.utl.pt/files/publico/academicos/guia_dissertacao.pdf
    http://da.ist.utl.pt/dissertacao-de-mestrado/


This template was highly based from the work done by:

::

    Andre C. Marta
    Area Cientifica de Mecanica Aplicada e Aeroespacial
    Departamento de Engenharia Mecanica

    URL: https://fenix.ist.utl.pt/homepage/ist31052/documentos-para-elaboracao-da-tese

We cannot thank him enough for his work and by the publishing of this template. Thanks!

Instructions
------------

    * Just do  "make" and check if thesis.pdf is created
        - If any problem check the Recommended latex packages section)
    * Then fill the preamble.tex file with the properties of your thesis.
    * Alter the remaining .tex files (see structure section)

Structure
---------

::

    .
    ├── abstract.tex         -->
    ├── acknowledgements.tex -->
    ├── acronyms.tex         -->
    ├── appendix.tex         -->
    ├── architecture.tex     -->
    ├── conclusions.tex      -->
    ├── evaluation.tex       -->
    ├── Figures              -->
    │   ├── frontImage.png   -->
    │   └── logoCNM.png      -->
    ├── frontCover.tex       -->
    ├── implementation.tex   -->
    ├── introduction.tex     -->
    ├── Logo.pdf             -->
    ├── Makefile             -->
    ├── preamble.tex         -->
    ├── README.rst           -->
    ├── references.bib       -->
    ├── relatedwork.tex      -->
    ├── resumo.tex           -->
    ├── splncs.bst           -->
    ├── thesis.pdf           -->
    └── thesis.tex           -->

4 directories, 64 files


Recommended latex packages
--------------------------

::

    texlive-latex-extra
    texlive-latex-science
    texlive-lang-portuguese
