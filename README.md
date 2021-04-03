package calculum
================
carol medeiros
03/04/2021

Simple package for the R language class (how to create a package and
upload to github).  
There are only two functions -&gt; **sum** and **subtract**.

------------------------------------------------------------------------

## **Installation**

To install, enter the command below:

``` r
devtools::install_github("mecarolme/calculum")
```

Don’t forget to run the package.

``` r
library(calculum)
```

------------------------------------------------------------------------

## **Use**

Example:  
This function sum two parameters.

``` r
sum(2, 3)
```

    ## [1] 5

And that function subtract two parameters.

``` r
subtract(2, 3)
```

    ## [1] -1

Parameters are defined by the user.
