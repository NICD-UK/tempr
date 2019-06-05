# `tempr` Package

## Introduction

The `tempr` package provides a data science template for R projects. This template is designed to be consistent with [R Packages](http://r-pkgs.had.co.nz/) and [R for Data Science](https://r4ds.had.co.nz/) by Hadley Wickham. The workflow stages proposed in R for Data Science consists of **import**, **tidy**, **explore** (transform and visualise), **model** and **communicate**. The `tempr` package includes a directory named **notebooks** for `R notebook` files. This directory has five subdirectories that correspond to the five workflow stages. The `tempr` package also includes a directory named **data** for `data` files. This directory is ignored in the `.gitignore` file.

![](https://d33wubrfki0l68.cloudfront.net/795c039ba2520455d833b4034befc8cf360a70ba/558a5/diagrams/data-science-explore.png)

## Directory Structure

- `config.yml`
- **data**
- `DESCRIPTION`
- `LICENSE.md`
- **man**
- `NAMESPACE`
- **notebooks**
    - 1\_import
    - 2\_tidy
    - 3\_explore
    - 4\_model
    - 5\_communicate
- **R**
- `README.md`
- `template.Rproj`

## Other

- **Git**: We reccomend local and remote git repositories for collaborative projects. To set up a local git repository use the `usethis::use_git` function. To set up a remote git repository use the `usethis::use_github` function. Note: you will need to set up a [github](github.com) account to set up a remote respository. The [usethis](https://usethis.r-lib.org/) website provides details about using these functions.
- **Style**: We recommend adhering to the tidyverse [style guide](style.tidyverse.org).

## Import

## Tidy

## Explore

## Model

## Communicate
