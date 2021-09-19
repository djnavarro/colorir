
<!-- README.md is generated from README.Rmd. Please edit that file -->

# colorir

<!-- badges: start -->
<!-- badges: end -->

The goal of colorir is to provide a collection of colour palettes
suitable for generative art.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("djnavarro/colorir")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
colorir::colores
#> # A tibble: 600 × 6
#>    palette_name       colour_name   colour  palette_index colour_index url      
#>    <chr>              <chr>         <chr>           <int>        <int> <chr>    
#>  1 rosettes-and-cream Rosewater     #d8a7b1             1            1 https://…
#>  2 rosettes-and-cream Spearmint     #b6e2d3             1            2 https://…
#>  3 rosettes-and-cream Cream         #fae8e0             1            3 https://…
#>  4 rosettes-and-cream Hot Pink      #ef7c8e             1            4 https://…
#>  5 pastel-blonde      Purple        #887bb0             2            1 https://…
#>  6 pastel-blonde      Spearmint     #85d2d0             2            2 https://…
#>  7 pastel-blonde      Rose Quartz   #f4b9b8             2            3 https://…
#>  8 pastel-blonde      Yellow        #fff4bd             2            4 https://…
#>  9 deep-merlot        Midnight Blue #1b2e3c             3            1 https://…
#> 10 deep-merlot        Dark Blue     #0c0c1e             3            2 https://…
#> # … with 590 more rows
```
