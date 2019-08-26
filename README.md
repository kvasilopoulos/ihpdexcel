
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ihpdexcel

<!-- badges: start -->

<!-- badges: end -->

The goal of {ihpdexcel} is to provide excel-reports for the exubernace
indicators, for the International Housing Observatory. It sources an
excel template from the `template` dir and store the output to
`versions` dir. It utilizes the api from `{ihpdr}`, to download and tidy
data, so there is no need to fetch data manually. You simply need to
source the `create-excel.R` file.

``` r
source("create-excel.R")
#> Saving `hpta1901.xlsx` to `versions/hpta1901.xlsx`
```

# Download

You can download the whole repo, doing the following:

``` r
# install.packages("usethis")
usethis::use_course("kvasilopoulos/excel-iho")
```
