
koweps
======

한국복지패널 데이터 패키지
--------------------------

-   2017년 12차 머지 데이터(가구용, 가구원용, 장애인설문용 데이터 통합본)입니다.

Installation
------------

``` r
# install.packages("remotes")
remotes::install_github("youngwoos/koweps")
```

Example
-------

``` r
library(koweps)
str(welfare, list.len = 10)
#> Classes 'tbl_df', 'tbl' and 'data.frame':    15422 obs. of  1193 variables:
#>  $ h12_id          : num  1 2 3 4 4 6 6 6 6 6 ...
#>  $ h12_ind         : num  1 1 1 1 1 1 1 1 1 1 ...
#>  $ h12_sn          : num  1 1 1 1 1 1 1 1 1 1 ...
#>  $ h12_merkey      : num  10101 20101 30101 40101 40101 ...
#>  $ h_new           : num  0 0 0 0 0 0 0 0 0 0 ...
#>  $ h12_cobf        : num  NA NA NA NA NA NA NA NA NA NA ...
#>  $ p12_wgl         : num  953 1239 1282 1066 1391 ...
#>  $ p12_wsl         : num  0.287 0.373 0.386 0.321 0.418 ...
#>  $ p12_wgc         : num  948 1239 1282 1066 1383 ...
#>  $ p12_wsc         : num  0.285 0.373 0.386 0.321 0.416 ...
#>   [list output truncated]

welfare[1:10, 1:5]
#>    h12_id h12_ind h12_sn h12_merkey h_new
#> 1       1       1      1      10101     0
#> 2       2       1      1      20101     0
#> 3       3       1      1      30101     0
#> 4       4       1      1      40101     0
#> 5       4       1      1      40101     0
#> 6       6       1      1      60101     0
#> 7       6       1      1      60101     0
#> 8       6       1      1      60101     0
#> 9       6       1      1      60101     0
#> 10      6       1      1      60101     0
```
