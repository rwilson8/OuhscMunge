| [GitHub](https://github.com/OuhscBbmc/OuhscMunge) | [Travis-CI](https://travis-ci.org/OuhscBbmc/OuhscMunge/builds) | [CodeCov](https://app.codecov.io/gh/OuhscBbmc/OuhscMunge/) |
| :----- | :---------------------------: | :-------: |
| [Main](https://github.com/OuhscBbmc/OuhscMunge/tree/main) | [![R-CMD-check](https://github.com/OuhscBbmc/OuhscMunge/actions/workflows/check-release.yaml/badge.svg)](https://github.com/OuhscBbmc/OuhscMunge/actions/workflows/check-release.yaml) | [![codecov](https://codecov.io/gh/OuhscBbmc/OuhscMunge/branch/main/graph/badge.svg?token=O1mkr31GRw)](https://codecov.io/gh/OuhscBbmc/OuhscMunge) |
| [Dev](https://github.com/OuhscBbmc/OuhscMunge/tree/dev) | [![R-CMD-check](https://github.com/OuhscBbmc/OuhscMunge/actions/workflows/check-release.yaml/badge.svg?branch=dev)](https://github.com/OuhscBbmc/OuhscMunge/actions/workflows/check-release.yaml) | [![codecov](https://codecov.io/gh/OuhscBbmc/OuhscMunge/branch/dev/graph/badge.svg?token=O1mkr31GRw)](https://app.codecov.io/gh/OuhscBbmc/OuhscMunge/branch/dev)
 | 

OuhscMunge
==========
Data manipulation operations commonly used by the [Biomedical and Behavioral Methodology Core](http://www.ouhsc.edu/bbmc/) within the [Department of Pediatrics](http://www.oumedicine.com/pediatrics) of the [University of Oklahoma Health Sciences Center](http://ouhsc.edu/).

### Download and Installation Instructions
<!--
The *release* version of OuhscMunge can be installed from [CRAN](http://cran.r-project.org/web/packages/OuhscMunge/).
```r
install.packages("OuhscMunge")
```
-->

The *development* version of `OuhscMunge` can be installed from [GitHub](https://github.com/OuhscBbmc/OuhscMunge) after installing the `remotes` package.  (The *release* version will be available on [CRAN](https://cran.r-project.org/) later.)
```r
install.packages("remotes")                     # If it's not already installed.
remotes::install_github("OuhscBbmc/OuhscMunge")
```

### Collaborative Development
We encourage input and collaboration from the overall community.  If you're familiar with GitHub and R packages, feel free to submit a [pull request](https://github.com/OuhscBbmc/OuhscMunge/pulls).  If you'd like to report a bug or make a suggestion, please create a GitHub [issue](https://github.com/OuhscBbmc/OuhscMunge/issues); issues are a usually a good place to ask public questions too.  However, feel free to email Will (<wibeasley@hotmail.com>).  Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

### Thanks to Funders
*OUHSC CCAN Independent Evaluation of the State of Oklahoma Competitive Maternal, Infant, and Early Childhood Home Visiting ([MIECHV](http://mchb.hrsa.gov/programs/homevisiting/)) Project.*: Evaluates MIECHV expansion and enhancement of Evidence-based Home Visitation programs in four Oklahoma counties. [HRSA/ACF D89MC23154](https://perf-data.hrsa.gov/mchb/DGISReports/Abstract/AbstractDetails.aspx?Source=TVIS&GrantNo=D89MC23154&FY=2012).  

(So far) the primary developers of OuhscMunge are the external evaluators for [Oklahoma's MIECHV](http://www.ok.gov/health/Child_and_Family_Health/Family_Support_and_Prevention_Service/MIECHV_Program_-_Federal_Home_Visiting_Grant/MIECHV_Program_Resources/index.html) program.

### Code Coverage Over Time

Main Branch:

![codecov.io](http://codecov.io/github/OuhscBbmc/OuhscMunge/branch.svg?branch=main)

Dev Branch:

![codecov.io](http://codecov.io/github/OuhscBbmc/OuhscMunge/branch.svg?branch=dev)
