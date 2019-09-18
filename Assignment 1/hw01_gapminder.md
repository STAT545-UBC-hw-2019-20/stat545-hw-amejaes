Assignment 1: Gapminder
================

## Gapminder

We are going to explore Gapminder, a dataset. What information is
present in the dataset? Below are Gapminder’s column headings:

``` r
columns <- names(gapminder)
columns
```

    ## [1] "country"   "continent" "year"      "lifeExp"   "pop"       "gdpPercap"

## Smallest population Part 1

Which country in the world has the smallest population size?

    ## # A tibble: 1 x 5
    ##   country               continent  year lifeExp   pop
    ##   <fct>                 <fct>     <int>   <dbl> <int>
    ## 1 Sao Tome and Principe Africa     1952    46.5 60011

## Smallest population Part 2

The smallest population size in Gapminder is from a country in 1952.
Does the same country currently have the smallest population size in the
world? *Current = 2007, the most recent year available in Gapminder*

    ## # A tibble: 1 x 5
    ##   country               continent  year lifeExp    pop
    ##   <fct>                 <fct>     <int>   <dbl>  <int>
    ## 1 Sao Tome and Principe Africa     2007    65.5 199579

## Population range

Globally, what is the range in population sizes (circa 2007)?

    ## [1]     199579 1318683096
