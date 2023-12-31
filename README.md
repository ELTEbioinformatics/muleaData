
<!-- README.md is generated from README.Rmd. Please edit that file -->

# muleaData

<!-- badges: start -->

[![GitHub
issues](https://img.shields.io/github/issues/ELTEbioinformatics/muleaData)](https://github.com/ELTEbioinformatics/muleaData/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/ELTEbioinformatics/muleaData)](https://github.com/ELTEbioinformatics/muleaData/pulls)

<!-- badges: end -->

`muleaData` is an ExperimentHubData Bioconductor package for the `mulea`
R package. `mulea` is a comprehensive overrepresentation and functional
enrichment analyser R package. Here we provide ontologies (gene and
protein sets) in a standardised *GMT* (Gene Matrix Transposed) format
for 27 different model organisms, ranging from *Escherichia coli* to
human, all acquired from publicly available data sources. The *GMT*
files are provided with multiple gene and protein identifiers.

List of species `muleaData` covers:

- Arabidopsis thaliana
- Bacillus subtilis
- Bacteroides thetaiotaomicron
- Bifidobacterium longum
- Bos taurus
- Caenorhabditis elegans
- Chlamydomonas reinhardtii
- Danio rerio
- Daphnia pulex
- Dictyostelium discoideum
- Drosophila melanogaster
- Drosophila simulans
- Escherichia coli
- Gallus gallus
- Homo sapiens
- Macaca mulatta
- Mus musculus
- Mycobacterium tubercolosis
- Neurospora crassa
- Pan troglodytes
- Rattus norvegicus
- Saccharomyces cerevisiae
- Salmonella enterica
- Schizosaccharomyces pombe
- Tetrahymena thermophila
- Xenopus tropicalis
- Zea mays

Type, name, link and citation of the databases `muleaData` covers:

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `muleaData` from
[Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("muleaData")
```

And the development version from
[GitHub](https://github.com/ELTEbioinformatics/muleaData) with:

``` r
BiocManager::install("ELTEbioinformatics/muleaData")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("muleaData")
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub!

## Citation

Below is the citation output from using `citation('muleaData')` in R.
Please run this yourself to check for any updates on how to cite
**muleaData**.

``` r
print(citation('muleaData'), bibtex = TRUE)
#> To cite package 'muleaData' in publications use:
#> 
#>   Ari E, Ölbei M, Gul L, Bohár B (2023). _muleaData: ExperimentalData
#>   Bioconductor Package for the mulea R Package, Contains Genes Sets for
#>   Functional Enrichment Analysis in GMT File Format_. R package version
#>   0.99.0, <https://github.com/ELTEbioinformatics/muleaData>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {muleaData: ExperimentalData Bioconductor Package for the mulea R Package, Contains Genes Sets for Functional Enrichment Analysis in GMT File Format},
#>     author = {Eszter Ari and Márton Ölbei and Lejla Gul and Balázs Bohár},
#>     year = {2023},
#>     note = {R package version 0.99.0},
#>     url = {https://github.com/ELTEbioinformatics/muleaData},
#>   }
```

Please note that the `muleaData` was only made possible thanks to many
other R and bioinformatics software authors, which are cited either in
the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the `muleaData` project is released with a [Contributor
Code of Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

- Continuous code testing is possible thanks to [GitHub
  actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
  through *[usethis](https://CRAN.R-project.org/package=usethis)*,
  *[remotes](https://CRAN.R-project.org/package=remotes)*, and
  *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)* customized
  to use [Bioconductor’s docker
  containers](https://www.bioconductor.org/help/docker/) and
  *[BiocCheck](https://bioconductor.org/packages/3.18/BiocCheck)*.
- Code coverage assessment is possible thanks to
  [codecov](https://codecov.io/gh) and
  *[covr](https://CRAN.R-project.org/package=covr)*.
- The [documentation
  website](http://ELTEbioinformatics.github.io/muleaData) is
  automatically updated thanks to
  *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
- The code is styled automatically thanks to
  *[styler](https://CRAN.R-project.org/package=styler)*.
- The documentation is formatted thanks to
  *[devtools](https://CRAN.R-project.org/package=devtools)* and
  *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.18/biocthis)*.
