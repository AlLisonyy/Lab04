Lab 04 - Visualizing spatial data
================
Allison
02052025

### Load packages and data

``` r
##install.packages("devtools")
##devtools::install_github("rstudio-education/dsbox")
library(tidyverse)
library(dsbox)
```

``` r
states <- read_csv("data/states.csv")
```

### Exercise 1

``` r
print(dennys)
```

    ## # A tibble: 1,643 × 6
    ##    address                        city            state zip   longitude latitude
    ##    <chr>                          <chr>           <chr> <chr>     <dbl>    <dbl>
    ##  1 2900 Denali                    Anchorage       AK    99503    -150.      61.2
    ##  2 3850 Debarr Road               Anchorage       AK    99508    -150.      61.2
    ##  3 1929 Airport Way               Fairbanks       AK    99701    -148.      64.8
    ##  4 230 Connector Dr               Auburn          AL    36849     -85.5     32.6
    ##  5 224 Daniel Payne Drive N       Birmingham      AL    35207     -86.8     33.6
    ##  6 900 16th St S, Commons on Gree Birmingham      AL    35294     -86.8     33.5
    ##  7 5931 Alabama Highway, #157     Cullman         AL    35056     -86.9     34.2
    ##  8 2190 Ross Clark Circle         Dothan          AL    36301     -85.4     31.2
    ##  9 900 Tyson Rd                   Hope Hull (Tys… AL    36043     -86.4     32.2
    ## 10 4874 University Drive          Huntsville      AL    35816     -86.7     34.7
    ## # ℹ 1,633 more rows

There are 1643 observations and 6 variables in the dataset. Each row in
the dennys dataset represents a store at different places. Each column
represents one type of information about the location of the store,
including the state, the city, the store specific location, ZIP code,
the longitude, and latitude.

### Exercise 2

``` r
print(laquinta)
```

    ## # A tibble: 909 × 6
    ##    address                          city          state zip   longitude latitude
    ##    <chr>                            <chr>         <chr> <chr>     <dbl>    <dbl>
    ##  1 793 W. Bel Air Avenue            "\nAberdeen"  MD    21001     -76.2     39.5
    ##  2 3018 CatClaw Dr                  "\nAbilene"   TX    79606     -99.8     32.4
    ##  3 3501 West Lake Rd                "\nAbilene"   TX    79601     -99.7     32.5
    ##  4 184 North Point Way              "\nAcworth"   GA    30102     -84.7     34.1
    ##  5 2828 East Arlington Street       "\nAda"       OK    74820     -96.6     34.8
    ##  6 14925 Landmark Blvd              "\nAddison"   TX    75254     -96.8     33.0
    ##  7 Carretera Panamericana Sur KM 12 "\nAguascali… AG    20345    -102.      21.8
    ##  8 909 East Frontage Rd             "\nAlamo"     TX    78516     -98.1     26.2
    ##  9 2116 Yale Blvd Southeast         "\nAlbuquerq… NM    87106    -107.      35.1
    ## 10 7439 Pan American Fwy Northeast  "\nAlbuquerq… NM    87109    -107.      35.2
    ## # ℹ 899 more rows

There are 909 observations and 6 variables in this dataset. Each row in
the La Quinta’s dataset represents a store at different places. Each
column represents one type of information about the location of the
store, including the state, the city, the store specific location, ZIP
code, the longitude, and latitude.

### Exercise 3

…

### Exercise 4

…

### Exercise 5

…

### Exercise 6

…

Add exercise headings as needed.
