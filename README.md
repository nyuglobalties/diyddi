
<!-- README.md is generated from README.Rmd. Please edit that file -->

# DIYDDICurator

## Description

DIYDDICurator is a graphic user interface to the `rddi` package. It is a
shiny app designed to streamline metadata generation for research data
sharing. It allows the user to input project metadata and generate a
valid [Data Documentation Initiative Codebook (DDI
2.5)](https://ddialliance.org/Specification/DDI-Codebook/2.5/) to
describe the study and data collected.

DDI elements and their attributes are listed in various tabs and
described using `handsontable` (<https://handsontable.com/>). By right
clicking on the table users can add or delete rows. A human readable
README, the DDI Codebook and the data is available for export in the
Export navigation menu.

## Installation

It is recommended to use the development version of rddi from Github

``` r
# install.packages("devtools")
devtools::install_github("nyuglobalties/rddi")
```

DIYDDICurator installation

``` r
devtools::install_github("nyuglobalties/DIYDDICurator")
```

## Launch DIY DDI Curator

``` r
library(DIYDDICurator)
curator()

# or
DIYDDICurator:curator()
```
