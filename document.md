Intro to R Markdown
================

Markdown Basic
--------------

What can I *do* with Markdown?

-   headers or titles
-   list
-   code
-   quotations
-   links
-   mathematics
-   horizontal rules
-   emphasize text

What do people use Markdown for?

1.  R Markdown/Notebooks
2.  Jupyter, Beaker
3.  READMEs (GitHub, GitLab, BitBucket)
4.  [Pandoc](www.pandoc.org)

What does R Markdown add to this?

Mathematics:
$$
\\frac{-b \\pm \\sqrt{b^2 - 4ac}}{2a}
$$

Where does R come into all of this?

``` r
x = 1:3
mean(x)
```

    ## [1] 2

``` r
library(ggplot2)

ggplot(diamonds, aes(carat, price)) + geom_point(aes(color = cut))
```

![](document_files/figure-markdown_github/unnamed-chunk-3-1.png)

The random mean is -0.0150584.

``` python
import sys

print(sys.version)
print("Hello world!")
```

    ## 3.5.2 (default, Nov  7 2016, 11:31:36) 
    ## [GCC 6.2.1 20160830]
    ## Hello world!

``` bash
ls
```

    ## 2016-rtg-rmarkdown.Rproj
    ## document.docx
    ## document_files
    ## document.html
    ## document.nb.html
    ## document.pdf
    ## document.Rmd
