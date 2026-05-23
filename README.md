# projectTPE

<!-- badges: start -->
[![R-CMD-check](https://github.com/hdmeasure/projectTPE/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/hdmeasure/projectTPE/actions/workflows/R-CMD-check.yaml)
[![CRAN status](https://www.r-pkg.org/badges/version/projectTPE)](https://CRAN.R-project.org/package=projectTPE)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
<!-- badges: end -->

## A Shiny Application for Latent Factor Analysis of Non-Formal Teacher Performance

**projectTPE** provides an integrated platform for longitudinal latent factor
analysis of composite-score teacher performance data — designed for
non-formal equivalency schools (*Paket C*, *PPS Ulya*, PKBM, SKB) in
the Indonesian National Assessment (*Asesmen Nasional*) Rapor Pendidikan.

## Installation

```r
# From CRAN
install.packages("projectTPE")

# Development version
remotes::install_github("hdmeasure/projectTPE")
```

## Quick Start

```r
library(projectTPE)
run_app()   # launches Shiny dashboard
```

## Features

- **EFA** — parallel analysis, KMO, Bartlett, oblimin rotation
- **CFA** — MLR + FIML, modification indices
- **Measurement Invariance** — configural → metric → scalar (4 waves)
- **LPA** — factor-score profiles, BIC selection
- **Built-in simulated dataset** — 4-wave Rapor Pendidikan structure
- **Export** — multi-sheet Excel workbook

## Web App

https://hdmeasurement.shinyapps.io/projectTPE

## Citation

> Indriani H Ismail. (2025). projectTPE: A Shiny Application for Latent Factor
> Analysis of Non-Formal Teacher Performance.
> Applied Psychological Measurement.

## License

GPL (>= 3)
