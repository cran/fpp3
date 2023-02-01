
<!-- README.md is generated from README.Rmd. Please edit that file -->

# fpp3

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/fpp3)](https://cran.r-project.org/package=fpp3)
[![R build
status](https://github.com/robjhyndman/fpp3package/workflows/R-CMD-check/badge.svg)](https://github.com/robjhyndman/fpp3package/actions)
[![Downloads](https://cranlogs.r-pkg.org/badges/fpp3)](https://cran.r-project.org/package=fpp3)
<!-- badges: end -->

## Overview

The fpp3 package contains data used in the book [*Forecasting:
Principles and Practice* (3rd edition)](https://OTexts.com/fpp3/) by Rob
J Hyndman and George Athanasopoulos. It also loads several packages
needed to do the analysis described in the book. These packages work
with the [tidyverse](https://www.tidyverse.org/) set of packages,
sharing common data representations and API design.

## Installation

You can install the **stable** version from
[CRAN](https://cran.r-project.org/package=fpp3).

``` r
install.packages('fpp3', dependencies = TRUE)
```

You can install the **development** version from
[Github](https://github.com/robjhyndman/fpp3package)

``` r
# install.packages("remotes")
remotes::install_github("robjhyndman/fpp3package")
```

## Usage

`library(fpp3)` will load the following packages:

- [tibble](https://tibble.tidyverse.org), for tibbles, a modern
  re-imagining of data frames.
- [dplyr](https://dplyr.tidyverse.org), for data manipulation.
- [tidyr](https://tidyr.tidyverse.org), to easily tidy data using
  `spread()` and `gather()`.
- [lubridate](https://lubridate.tidyverse.org), for date/times.
- [ggplot2](https://ggplot2.tidyverse.org), for data visualisation.
- [tsibble](https://tsibble.tidyverts.org), for tsibbles, a time series
  version of a tibble.
- [tsibbledata](https://tsibbledata.tidyverts.org), various time series
  data sets in the form of tsibbles.
- [feasts](https://feasts.tidyverts.org), for features and statistics of
  time series.
- [fable](https://fable.tidyverts.org), for fitting models and producing
  forecasts.

You also get a condensed summary of conflicts with other packages you
have loaded:

``` r
library(fpp3)
#> ── Attaching packages ────────────────────────────────────────────── fpp3 0.5 ──
#> ✔ tibble      3.1.8     ✔ tsibble     1.1.3
#> ✔ dplyr       1.1.0     ✔ tsibbledata 0.4.1
#> ✔ tidyr       1.3.0     ✔ feasts      0.3.0
#> ✔ lubridate   1.9.1     ✔ fable       0.3.2
#> ✔ ggplot2     3.4.0     ✔ fabletools  0.3.2
#> ── Conflicts ───────────────────────────────────────────────── fpp3_conflicts ──
#> ✖ lubridate::date()    masks base::date()
#> ✖ dplyr::filter()      masks stats::filter()
#> ✖ tsibble::intersect() masks base::intersect()
#> ✖ tsibble::interval()  masks lubridate::interval()
#> ✖ dplyr::lag()         masks stats::lag()
#> ✖ tsibble::setdiff()   masks base::setdiff()
#> ✖ tsibble::union()     masks base::union()
```
