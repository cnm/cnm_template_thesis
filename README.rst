Master of Science Dissertation template
=======================================

Template for the Master Thesis according to the regulations
published by the Scientific Council at IST.

For up-to-date regulations, please refer to:
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

    * Just do  "make" and check if Thesis.pdf is created
      - If any problem check the Recommended latex packages section)
    * Then fill the Thesis_Preamble.tex file with the properties of your thesis.
    * Alter the remaining Thesis_*.tex files (see structure section)

Structure
---------

::

.
├── Thesis_Abstract.tex         -
├── Thesis_Acknowledgements.tex -
├── Thesis_Appendix.tex         -
├── Thesis_bib_DB.bib           -
├── Thesis_Conclusions.tex      -
├── Thesis_Dedication.tex       -
├── Thesis_FrontCover.tex       -
├── Thesis_Glossary.tex         -
├── Thesis_Introduction.tex     -
├── Thesis_Nomenclature.tex     -
├── Thesis.pdf                  -
├── Thesis_Preamble.tex         -
├── Thesis_Results.tex          -
├── Thesis_Resumo.tex           -
└── Thesis.tex                  -


Recommended latex packages
--------------------------

::

    texlive-latex-extra
    texlive-latex-science
    texlive-lang-portuguese
