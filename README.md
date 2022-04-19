# proteker2016-event


This repository contains short code to transform raw data of dataset `Stable isotope ratios and elemental contents of C, N and S in benthic organisms sampled during the PROTEKER 5 summer campaign in Kerguelen Islands (2016)`

## Dataset

Full version of dataset is published in the portals below. 

portal | link
:-- | :--
IPT | https://ipt.biodiversity.aq/resource?r=proteker2016-event
GBIF | https://www.gbif.org/dataset/28120c52-2b34-4db4-b348-812ee1eaf958
OBIS | https://obis.org/dataset/cc62b9e8-dd4a-4638-8061-b72721568e33

## Repo structure

```
.
├── README.md 			: description of this repository
├── proteker2016.Rproj	        : R Project
├── data			: directory to store data
│   └── processed		: directory to store processed data
├── html			: HTML of knitted Rmd files
│   └── transform-data.html	
├── renv 			: renv files for dependencies
├── renv.lock			: describe the state of project's library
└── transform-data.Rmd	        : Rmarkdown file of the code
```

Knitted Rmarkdown can be rendered at https://raw.githack.com/biodiversity-aq/proteker-2016/master/html/transform-data.html

## Getting started

If dependencies are not automatically installed by `renv` when you open `proteker2016.Rproj`, try the following command.

```{r}
renv::restore()
```
You can run chunks of R code in `transform-data.Rmd` or knit them into html.
