# Welcome to Stats NZ's R Repository

A collection of R packages and code produced by Stats NZ and contributors.

## Simplevis visualisation package

[**`simplevis`**](https://github.com/statisticsnz/simplevis) is an `R` package that enables high quality graphs and maps to be made with ease for use in analysis, reports or `shiny` apps. The package is based on a series of `ggplot2` and `leaflet` wrapper functions, and template/example shiny apps that work with these. To install this package, run ```r devtools::install_github("statisticsnz/simplevis")```. We intend to post this package to CRAN shortly.

## Packages for Demographic Estimation and Forecasting

+ [**`dembase`**](https://github.com/StatisticsNZ/dembase) General-purpose tools for demographic analysis, broadly defined.  Includes facilities for data manipulation, multistate models, projections, and plotting.  Uses S4 classes and methods.
+ [**`demdata`**](https://github.com/StatisticsNZ/demdata) Example datasets for demography.
+ [**`demest`**](https://github.com/StatisticsNZ/demest) Estimating and forecasting demographic rates and counts, using Bayesian methods.
+ [**`demlife`**](https://github.com/StatisticsNZ/demlife) Functions and data structures for working with life tables.
+ [**`demfam`**](https://github.com/StatisticsNZ/demfam) Functions and data structures for forecasting households and families.
+ [**`nzreg`**](https://github.com/StatisticsNZ/nzreg) Example datasets for New Zealand regions. 

All these packages are still under development. In particular, the user interface changes from time to time. If you are using these packages, please visit this site regularly to get the most recent version.  We will post the packages on CRAN when they are sufficiently stable and mature.

The New Zealand data in packages **dembase** and **nzreg** are for methodological and software development, and not for statistical analysis. The data are not necessarily up-to-date, and contain imputed or perturbed values.  For statistics on New Zealand, please see the [Stats NZ website](http://www.stats.govt.nz).

To install the packages run:

```r
library(devtools)
install_github("statisticsnz/dembase")
install_github("statisticsnz/demdata")
install_github("statisticsnz/demest")
install_github("statisticsnz/demlife")
install_github("statisticsnz/demfam")
install_github("statisticsnz/nzreg")
```

## Example Code

+ [**`nz_reg_proj`**](https://github.com/StatisticsNZ/nz_reg_proj) Experimental population forecasts for New Zealand regions. These are not official forecasts, and are for illustration only!
+ [**`lifetables_workflow`**](https://github.com/StatisticsNZ/lifetables_workflow) Code for estimating mortality rates and using them to produce life tables (including, for example, life expectancies).
+ [**`makefile_example`**](https://github.com/StatisticsNZ/makefile_example) Example of using a Makefile to control a workflow, and hence make the workflow safer and more reproducible.

-----

__Copyright and Licensing__

The package is Crown copyright (c) 2016, Statistics New Zealand on behalf of the New Zealand Government, and is licensed under the MIT License (see LICENSE file).

<br /><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This document is Crown copyright (c) 2016, Statistics New Zealand on behalf of the New Zealand Government, and is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
