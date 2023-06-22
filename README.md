SEAHORS
================

# [<img src="https://raw.githubusercontent.com/AurelienRoyer/SEAHORS/main/inst/www/logo1.png" height="60em" align="center"/>](https://github.com/AurelienRoyer/SEAHORS) Spatial Exploration of ArcHaeological Objects in R Shiny

[![DOI](https://zenodo.org/badge/581203118.svg)](https://zenodo.org/badge/latestdoi/581203118)
[![CRAN
Version](http://www.r-pkg.org/badges/version/SEAHORS)](https://cran.r-project.org/package=SEAHORS)
[![CRAN
Downloads](http://cranlogs.r-pkg.org/badges/SEAHORS)](https://cran.r-project.org/package=SEAHORS)

  - [**Presentation**](#presentation)
  - [**Installation**](#installation)
  - [**Demonstration and tutorial**](#demonstration-and-tutorial)
  - [**Example data set**](#example-data-set)
  - [**Interoperability**](#interoperability)
  - [**References**](#references)

## Presentation

`SEAHORS` is a R Shiny free open-source application that makes the
exploration of the spatial distribution of archaeological objects fast
and easy. Its main goal is to make the two and three-dimensional spatial
analysis of archaeological data as user-friendly as possible. This is
intended to lower the barrier for users who are not familiar with GIS
and R.

`SEAHORS` has an easily accessible interface and uses text and Excel
files (CSV and XLS respectively). The application includes functions to
merge several databases, for example when spatial data and analysis data
are stored in separate files.

The application is [demonstrated online
here](https://aurelienroyer.shinyapps.io/Seahors).

It can generate five types of plots:

1.  3D plots
2.  2D plots
3.  2D density plots
4.  plots generated by slicing the points cloud
5.  plots generated by modifying the angle of projection to explore
    spatial organisation without constraint of the grid orientation.

`SEAHORS` has visualization tools with several sorting and formatting
keys (colours) applicable to coordinates and all possible analysis
variables (i.e. levels, splits, analytical attributes).

## Installation

  - Install [R](https://www.r-project.org) and optionally [Rstudio
    Desktop](https://posit.co/download/rstudio-desktop/) to have a more
    comfortable R environment.
  - Install SEAHORS from CRAN:

<!-- end list -->

``` r
install.packages("SEAHORS")
```

or

  - Install the `SEAHORS` development version from github:

<!-- end list -->

``` r
# install.packages("devtools")
devtools::install_github("AurelienRoyer/SEAHORS")
```

Load the package and launch the `SEAHORS` application:

``` r
library(SEAHORS)
SEAHORS()
```

## Demonstration and tutorial

  - An demonstration instance of the `SEAHORS` application is deployed
    and available [online](https://aurelienroyer.shinyapps.io/Seahors).
  - An overview of the functionalities is published in the [**Royer et
    al. 2023**](https://doi.org/10.5281/zenodo.7674699).
  - A tutorial video of `SEAHORS` is available [in
    English](https://nakala.fr/10.34847/nkl.3fdd6h8j) and [in
    French](https://nakala.fr/10.34847/nkl.65bf1h72).

## Example data set: the Cassenade Palaeolithic site

The `SEAHORS` comes with an embedded example data set, from the
Cassenade Palaeolithic site (France).

  - Spatial data: <https://nakala.fr/10.34847/nkl.e30aie2u>
  - Refit: <https://nakala.fr/10.34847/nkl.fe27j10z>
  - Orthophoto: <https://nakala.fr/10.34847/nkl.7ea78e6u>

## Interoperability

To improve the interoperability between archaeological software,
`SEAHORS` can export data to the format required by the
`[archeoViz](https://analytics.huma-num.fr/archeoviz/en/)` application.
Two options are available in the `Table` tab, `archeoViz exports`
sub-tab:

  - “Export your data in archeoViz format”: to download your data as a
    CSV to upload in the `archeoViz` application.
  - “Directly send your SEAHORS data to archeoViz”: this opens a new
    window, launches the `archeoViz` application, and immediately load
    your data.

## References

  - Royer, A., Discamps, E., Plutniak, S., Thomas, M. 2023. “SEAHORS:
    Spatial Exploration of ArcHaeological Objects in R Shiny”. [*PCI
    Archaeology #320*](https://archaeo.peercommunityin.org/articles/rec?id=320), DOI:
    [10.5281/zenodo.7674699](https://doi.org/10.5281/zenodo.7674699).
  - Royer, A., Discamps, E., Plutniak, S., Thomas, M. 2023. “SEAHORS.
    Spatial Exploration of ArcHaeological Objects in R Shiny”, R
    package, DOI:
    [10.5281/zenodo.7664191](https://doi.org/10.5281/zenodo.7664191),
    <https://cran.r-project.org/package=SEAHORS>
   - Royer, A., Discamps, E., Plutniak, S., Thomas, M. 2023. “SEAHORS:
    Spatial Exploration of ArcHaeological Objects in R Shiny”. [*Peer Community Journal, 3, n°e55*](https://peercommunityjournal.org/articles/10.24072/pcjournal.289/), DOI:
    10.24072/pcjournal.289.
    
