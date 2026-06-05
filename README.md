<!-- badges: start -->
[![R-CMD-check](https://github.com/Breeding-Insight/popreviewR/workflows/R-CMD-check/badge.svg)](https://github.com/Breeding-Insight/popreviewR/actions)
![GitHub Release](https://img.shields.io/github/v/release/Breeding-Insight/popreviewR)
[![Development Status](https://img.shields.io/badge/development-active-blue.svg)](https://img.shields.io/badge/development-active-blue.svg)
[![CRAN Status Badge](https://www.r-pkg.org/badges/version/popreviewR)](https://cran.r-project.org/package=popreviewR)
![GitHub License](https://img.shields.io/github/license/Breeding-Insight/popreviewR)
[![codecov](https://app.codecov.io/gh/Breeding-Insight/popreviewR/graph/badge.svg?token=PJUZMRN1NF)](https://app.codecov.io/gh/Breeding-Insight/popreviewR)
<!-- badges: end -->

### Pedigree Validation and Breed/Line Composition Estimation for Diploid and Polyploid Species
</div>

popreviewR is an R package developed by [Breeding Insight](https://breedinginsight.org/) that provides tools for pedigree quality control and genomic breed/line composition estimation in diploid and polyploid breeding populations. It is designed to help researchers and breeders identify pedigree errors, assign parentage from SNP genotype data, and estimate genome-wide breed or line composition.

## Installation

The stable version of popreviewR is now available on CRAN. To install from the R terminal:

```R
install.packages("popreviewR")
install.packages("remotes")
remotes::install_github("Breeding-Insight/popreviewR", dependencies = TRUE)
library(popreviewR)
```

Note: This GitHub version of popreviewR is in development. So, there could be bugs present, and the stable version of popreviewR on CRAN should be viewed as more reliable.

Funding
popreviewR development is supported by Breeding Insight, a USDA-funded initiative based at the University of Florida - IFAS.

Citation
If you use popreviewR in your research, please cite as:

Chinchilla-Vargas, Josue, and Breeding Insight Team. 2025. "popreviewR: Pedigree Validation and Breed/Line Composition Estimation for Diploid and Polyploid Species." https://github.com/Breeding-Insight/popreviewR.