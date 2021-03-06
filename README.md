
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BBN

<!-- badges: start -->

<!-- badges: end -->

The goal of BBN is to infer Gaussian Boolean networks by Markov Chain
Monte Carlo algorithm.

## Installation

You can install the released version of BBN from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("BBN")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("han16/BBN")
```

In case people have installation problem, try this

    remove.packages(c("curl","httr"))
    install.packages(c("curl", "httr"))
    Sys.setenv(CURL_CA_BUNDLE="/usr/lib64/microsoft-r/3.4/lib64/R/lib/microsoft-r-cacert.pem")
    devtools::install_git("https://github.com/han16/BBN")

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(BBN)
## basic example code
```
