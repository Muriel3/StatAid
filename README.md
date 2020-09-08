
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Welcome to StatAid

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

`StatAid` is a free open-source software provided as an R package
allowing clinicians and researchers to perform statistic analysis
through an intuitive graphical interface. It has been developed with the
R software, using the [Shiny package](https://shiny.rstudio.com/).
[Golem](https://github.com/ThinkR-open/golem) has been used for package
compilation and deployment.

The software guide the users through the steps of a good data analysis,
including multiple features:

<ul>

<li>

Exploratory data analysis: distribution, count, missing-values and
outliers check

</li>

<li>

Descriptive analysis, simple comparative analysis and publication ready
‘table 1’ output

</li>

<li>

Publication-ready graph customization

</li>

<li>

Paired data analysis (case-control studies, repetead measures)

</li>

<li>

Univariate analysis and models for continuous and categorical outcome:
Correlation, linear and logistic regression

</li>

<li>

Univariate analysis and models for time-dependant outcome: Kaplan-Meier
curves and cox regression

</li>

<li>

Multivariate analysis and models for continuous, categorical and
time-dependant outcomes

</li>

</ul>

# Getting started

## Online version

StatAid has a ready-to-use online version available at
<https://vincentalcazer.shinyapps.io/StatAid/>.

## Local version

You can install the development version from
[GitHub](https://github.com/VincentAlcazer/StatAid) else by cloning the
repository or directly by downloading the package in R:

``` r

# install.packages("remotes")
#remotes::install_github("VincentAlcazer/StatAid")

#StatAid::run_app()
```

# Troubleshooting and contribution

All troubleshooting and contributions can be found on the [Github
page.](https://github.com/VincentAlcazer/StatAid/issues)

## Bug report

If you encounter any problem with the software or find a bug, please
report it on GitHub:

  - Create a [new
    issue](https://github.com/VincentAlcazer/StatAid/issues) on the
    Github page
  - Try to describe the problem/bug with reproductible steps

## Feature request

To ask for new feature implementation/current feature enhancemenet:

  - Create a [new
    issue](https://github.com/VincentAlcazer/StatAid/issues) on the
    Github page
  - Briefly describe the research question you want to answer and the
    type of data you have
  - If possible: provide pictures of the graph you would like to make or
    references from the paper you saw the analysis in.

## Contribution proposal

Contributions to new features or code enhancement are welcomed by
creating a new [pull
request.](https://github.com/VincentAlcazer/StatAid/pulls)
