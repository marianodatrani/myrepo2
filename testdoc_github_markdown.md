Test doc for github-markdown
================
2022-08-11

``` r
data("mtcars")

library(ggplot2)

ggplot2::ggplot(mtcars, aes(wt, mpg))+
  geom_point()+
  geom_smooth(method = "lm", se=F)
```

    ## `geom_smooth()` using formula 'y ~ x'

![](testdoc_github_markdown_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->
