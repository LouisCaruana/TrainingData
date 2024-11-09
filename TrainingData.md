TrainingData
================

``` r
BenchmarkData <- gsheet2tbl('https://docs.google.com/spreadsheets/d/1r-oelVOoCSLaieIQstDTetCJqJgULjz6Z1y-2NS5sbU/edit?usp=sharing')
```

    ## No encoding supplied: defaulting to UTF-8.

``` r
head(BenchmarkData)
```

    ##   Benchmark Percentile      Men    Women
    ## 1    Run 5K       99th 00:18:00 00:20:01
    ## 2    Run 5K       95th 00:19:36 00:22:21
    ## 3    Run 5K       90th 00:20:25 00:23:36
    ## 4    Run 5K       80th 00:21:40 00:25:00
    ## 5    Run 5K      75th  00:22:09 00:25:43
    ## 6    Run 5K       60th 00:22:36 00:27:30
