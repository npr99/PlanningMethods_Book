# Planning Methods Jupyter Book
Jupyter Book with Planning Methods examples.

## Organization of Book (and file name logic)
Project mnemonic PLAN (Planning Methods) is used to name files.

### Sections:
1. 00 - Administrative - overview, topics like how to setup computer, what is Google Colab, what is python, how to use python for statistics. Maybe section on AICP code of ethics (motivation for project).
2. 01 - Public Data Sets and Census Geography
3. 02 - Statistics Foundations
4. 03 - Demographic Methods
5. 04 - Economic Methods
6. 05 - Other methods Overview (like GIS, land use, transportation, etc.)
7. Skip sections for other method sections
8. 90 - References
9. 91 - Appendix - miscellaneous notebooks
10. 92 - Supporting Code Files - functions developed in notebooks moved to .py files

### Subsections:
1. a - first subsection overview maybe a .md file
2. b - Overview of Data Sources and Census Geography options
3. c - z - notebooks with example methods




Will be moving Jupyter Notebooks from the GitHub repository [npr99/PlanningMethods](https://github.com/npr99/PlanningMethods) to create a Jupyter Book.

Learning how to make a Jupyter Book:
1. Qiusheng Wu 2022 Creating an open-source book with Jupyter Book and Jupytext https://www.youtube.com/watch?v=jUdXs4OPR84&t=1912s
2. https://jupyterbook.org/en/stable/start/overview.html
3. https://jupyterbook.org/en/stable/start/publish.html

Executable Books Community. (2020). Jupyter Book (v0.10). Zenodo. https://doi.org/10.5281/zenodo.4539666

Helpful examples:
22dylan. (2022). 22dylan/pyincore_seaside_jb: Seaside Jupyter book with demonstrative notebooks (v1.0). Zenodo. https://doi.org/10.5281/zenodo.6998352
https://github.com/22dylan/pyincore_seaside_jb 

Steps from Dylan:
1. setup a github repository
2. run all of the notebooks (make sure the _config.yml file has execute_notebooks: 'off')
3. save the notebooks so the output shows/isn’t cleared
4. build the jupyter book
5. push the book to the github repository
6. follow the steps to publish to github.io

Acknowledgements:
Cooper Goodman
Dylan Sanderson
