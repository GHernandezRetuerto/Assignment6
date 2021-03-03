Presentation Example - Stat2Data
========================================================
author: Guillermo Hernandez
date: 24-02-2021
autosize: true
font-family: Helvetica
css: style.css
transition: fade

Stat2Data
========================================================
navigation: section
incremental: true

Stat2Data is a package containing a huge amount of datasets extracted from the textbook Stat2: Modeling with Regression and ANOVA.

More information can be found in [CRAN website](https://cran.r-project.org/web/packages/Stat2Data/index.html8) and in the [reference PDF](https://cran.r-project.org/web/packages/Stat2Data/Stat2Data.pdf).

Some of these datasets include:

1. ~~CO2SouthPole~~ (the one we are going to use)
<li class='fragment fade-out'>Airlines</li>
<li class='fragment fade-out'>AppleStock</li>

The Dataset
========================================================

`CO2SouthPole` contains CO2 concentration measurements (in ppm) in a scientific settlement in Antarctica. 


```r
library(Stat2Data)

data(CO2SouthPole)
head(CO2SouthPole)
```

```
  Year Month    CO2 t
1 1988     1 348.10 1
2 1988     2 348.54 2
3 1988     3 349.40 3
4 1988     4 349.70 4
5 1988     5 349.65 5
6 1988     6 349.80 6
```

For the sake of the example, let's take the monthly data of 1988 and 1989 (only the month and the CO2 value). 

