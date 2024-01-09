
# rg2

<!-- badges: start -->
![R-CMD-check](https://github.com/glfeng318/rg2/workflows/R-CMD-check/badge.svg)
[![CRAN status](https://www.r-pkg.org/badges/version/rg2)](https://CRAN.R-project.org/package=rg2)
[![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)
<!-- badges: end -->

rg2 is a wrapper of [G2Plot](https://g2plot.antv.antgroup.com/) for R.

## Installation

You can install the development version of rg2 like so:

```r
pak::pkg_install("glfeng318/rg2")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(rg2)
data(mpg, package = 'ggplot2')
g2(mpg,'scatter', list(xField='displ',yField='hwy',colorField = 'class', shape='circle'))
```
![](./demo.png)
