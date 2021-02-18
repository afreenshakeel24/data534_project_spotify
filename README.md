
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rspotify

<!-- badges: start -->

<!-- badges: end -->

The purpose of this package is to provide an API wrapper in R for
gathering data from Spotify and visualizing that data in plots.

## Installation

You can install the released version of rspotify from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("rspotify")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("cfbanks/data534_project_spotify")
```

## Example

This is a basic example which shows you how to complete a certain task:

``` r
library(rspotify)
#> Loading required package: tidyverse
#> -- Attaching packages --------------------------------------------------------------------------------------------------------------- tidyverse 1.3.0 --
#> v ggplot2 3.3.2     v purrr   0.3.4
#> v tibble  3.0.3     v dplyr   1.0.2
#> v tidyr   1.1.2     v stringr 1.4.0
#> v readr   1.3.1     v forcats 0.5.0
#> -- Conflicts ------------------------------------------------------------------------------------------------------------------ tidyverse_conflicts() --
#> x dplyr::filter() masks stats::filter()
#> x dplyr::lag()    masks stats::lag()
## basic example code
example_add(4, 10)
#> [1] 14
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/master/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
