Reproducible Research Project Template
====================

A boilerplate for reproducible science and research in biomedical imaging. 

This boilerplate is inspired by [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.* and based on Mario Krapp's [adaption](https://github.com/mkrapp/cookiecutter-reproducible-science). 

Requirements
------------
Install `cookiecutter` via the command line using conda: 
`conda install -c conda-forge cookiecutter`
or pip:
`pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:stfnr/cookiecutter-reproducible-research-project`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── bin                <- Compiled code (if tracked, use git-lfs)
├── config             <- Configuration files, e.g., for doxygen or for your model if needed
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
├── docs               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── logs               <- Logging files, logging output from all the processing steps
├── notebooks          <- Ipython or R notebooks
├── reports            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── src                <- Source code for this project
    ├── data           <- scripts and programs to process data
    ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
    ├── models         <- Source code for your own model
    ├── tools          <- Any helper scripts go here
    └── visualization  <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.
```

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
