# CS-PHOC

This repository contains script to transform data files of [CS-PHOC](https://github.com/us-amlr/cs-phoc/) into Darwin Core compliant tables.

## Repo structure 

```
.
├── README.md
├── cs-phoc.Rproj         : R project file
├── data                  : directory to store data
│   ├── generated
│   └── raw
├── renv                  : renv files for dependencies
│   ├── activate.R
│   ├── library
│   ├── settings.json
│   └── staging
├── renv.lock
└── src                   
    ├── to-dwc-table.Rmd  : Rmarkdown file of the code
    └── to-dwc-table.html : HTML of knitted Rmd files 
```

## Getting started

This project uses [renv](https://rstudio.github.io/renv/) to manage the virtual environment. If dependencies are not automatically installed by `renv` when you open `humboldt.Rproj`, please try the following command.

```
renv::restore()
```
