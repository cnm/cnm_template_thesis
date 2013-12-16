Master of Science Dissertation template
=======================================

Template for the Master Thesis according to the regulations
published by the Scientific Council at IST.

For up-to-date regulations, please refer to:

::

    http://da.ist.utl.pt/files/sites/33/TeseMstGuiaEstilo.pdf
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
    ├── abstract.tex         --> Tex for you to insert the abstract
    ├── acknowledgements.tex --> Tex for you to insert the acknowledgements
    ├── acronyms.tex         --> Tex for you to insert the acronyms (you can put all you want, only used will be shown)
    ├── appendix.tex         --> Tex for you to insert the appendix (optional)
    ├── architecture.tex     --> Tex for you to insert the architecture chapter
    ├── conclusions.tex      --> Tex for you to insert the conclusion chapter
    ├── evaluation.tex       --> Tex for you to insert the evaluation chapter
    ├── Figures              --> Figures Folder. Insert your images here
    │   ├── frontImage.png   --> Image to show on the front cover (optional use but change to what you want)
    │   └── logoCNM.png      --> Example image
    ├── frontCover.tex       --> Tex for you to define the front cover
    ├── implementation.tex   --> Tex for you to insert the implementation chapter
    ├── introduction.tex     --> Tex for you to insert the introduction chapter
    ├── Logo.pdf             --> Ist new logo image (do not change)
    ├── Makefile             -->
    ├── preamble.tex         --> Tex for you to insert the preamble configuration (probably do not need to change)
    ├── README.rst           -->
    ├── references.bib       --> Insert the bibtex references here
    ├── relatedwork.tex      --> Tex for you to insert the relatex work chapter
    ├── resumo.tex           --> Tex for you to insert the abstract in portuguese
    ├── splncs.bst           --> splncs reference style
    └── thesis.tex           --> Main .tex file. Includes (\input) all other .tex files

4 directories, 64 files


Recommended latex packages
--------------------------

::

    texlive-latex-extra
    texlive-latex-science
    texlive-lang-portuguese

Recommendations
---------------

An easy way to do tables for the latex newbie is to use this site:

    * http://truben.no/latex/table/
