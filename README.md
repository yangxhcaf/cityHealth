<!-- README.md is generated from README.Rmd. Please edit that file -->
cityHealth <img src="https://slu-dss.github.io/img/gisLogoSm.png" align="right" />
==================================================================================

[![lifecycle\_badge](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://github.com/slu-openGIS/cityHealth) [![CRAN\_status\_badge](http://www.r-pkg.org/badges/version/cityHealth)](https://cran.r-project.org/package=cityHealth)

The goal of `cityHealth` is to provide easy access to the [CDC's 500 Cities Project](https://www.cdc.gov/500cities/). The original 2017 data are in the public domain and easily accessed. However, they are contained in a single data table that is not "tidy" and is approximately 225MB in size. `cityHealth` provides "tidy" versions of the CDC's data in a format readily accessible to `R` at a fraction of the footprint. One way this is acheived is by removing metadata from each observation that is more economically stored in an alternate format. Thus the tables available in `cityHealth` are not identical to the [raw data](https://chronicdata.cdc.gov/500-Cities/500-Cities-Local-Data-for-Better-Health-2017-relea/6vp6-wxuq) available from the CDC.
