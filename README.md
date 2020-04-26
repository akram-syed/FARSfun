
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis build
status](https://travis-ci.com/akram-syed/FARSfun.svg?branch=master)](https://travis-ci.com/akram-syed/FARSfun)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/akram-syed/FARSfun?branch=master&svg=true)](https://ci.appveyor.com/project/akram-syed/FARSfun)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

# BUILDING AN R PACKAGE

An exercise in creating, writing, documenting, and testing an R package.

## Overview

This exercise involves building a package that contains R functions to
read data from the US National Highway Traffic Safety Administration’s
(NHTSA) [Fatality Analysis Reporting System
(FARS)](http://www.nhtsa.gov/Data/Fatality-Analysis-Reporting-System-\(FARS\)).

1.  Write R functions using `roxygen2` style comments
2.  Write a `vignette` to include in the package using `knitr` and R
    Markdown (`Rmd`)
3.  Write tests written using `testthat`
4.  Put package on GitHub
5.  Set up the repository so that the package can be checked and built
    on [Travis](https://travis-ci.com/) and
    [AppVeyor](https://ci.appveyor.com/)

# Assessment

The R package build will be a success if:

  - The package contain the correct R file(s) under the [`/R`
    directory](https://github.com/akram-syed/FARSfun/tree/master/R)
  - The package contain a [`/man`
    directory](https://github.com/akram-syed/FARSfun/tree/master/man)
    with corresponding documentation files
  - The package contain a
    [vignette](https://github.com/akram-syed/FARSfun/tree/master/vignettes)
    which provides a meaningful description of the package and how it
    should be used
  - The package have tests included in the [`/tests`
    directory](https://github.com/akram-syed/FARSfun/tree/master/tests)
  - The package has a [NAMESPACE
    file](https://github.com/akram-syed/FARSfun/blob/master/NAMESPACE)
  - The [`README.md`
    file](https://github.com/akram-syed/FARSfun/blob/master/README.md)
    appropriate badges
  - The build of this package passing on
    [Travis](https://travis-ci.com/github/akram-syed/FARSfun) and
    [AppVeyor](https://ci.appveyor.com/project/akram-syed/farsfun)
  - The build logs for this package on Travis and AppVeyor are free of
    any errors, warnings, or notes
