# Welcome to Statistics New Zealand's R Repository

A collection of R packages produced by Statistics New Zealand and contributors.


## Demographic Estimation and Forecasting

A set of packages for demographic estimation and forecasting consisting of:

+ [**`classconc`**](https://github.com/StatisticsNZ/classconc) - Functions and data structures for working with concordances between statistical classifications, e.g. concordances between  occupational codes or geographical units. Under development.
+ [**`dembase`**](https://github.com/StatisticsNZ/dembase) General-purpose tools for demographic analysis, broadly defined.  Includes facilities for data manipulation, multistate models, projections, and plotting.  Uses S4 classes and methods. Under development.
+ [**`demdata`**](https://github.com/StatisticsNZ/demdata) - Example datasets for demography.
+ [**`demest`**](https://github.com/StatisticsNZ/demest) - Estimating and forecasting demographic rates and counts, using Bayesian methods.  Under development.
+ `demlife` - Functions and data structures for working with life tables.  Code to be uploaded in October 2016!

To install all available packages:

```r
devtools::install_github("StatisticsNZ/classconc")
devtools::install_github("StatisticsNZ/dembase")
devtools::install_github("StatisticsNZ/demdata")
devtools::install_github("StatisticsNZ/demest")
```

-----

__Copyright and Licensing__

Unless otherwise stated all R packages are Crown copyright (c) 2016, Statistics New Zealand on behalf of the New Zealand Government, and are licensed under a MIT license.
