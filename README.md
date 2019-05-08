# qvcalc

[![Travis-CI Build Status](https://travis-ci.org/DavidFirth/qvcalc.svg?branch=master)](https://travis-ci.org/DavidFirth/qvcalc)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/qvcalc)](https://cran.r-project.org/package=qvcalc)

Full package documentation, including version history, is at https://davidfirth.github.io/qvcalc .

The **qvcalc** package provides _R_ functions to compute and display *quasi-variances* that often allow a more economical 
summary of the variance-covariance matrix for parameters in a statistical model.

For more details on the statistical method, see the references below. 

The web page at http://warwick.ac.uk/qvcalc gives information 
also about an online calculator implemented in _JavaScript_, for those who do not use *R*.

The package version at GitHub is the development version, snapshots of which are published periodically on CRAN. 

If you want to install the development version in *R*, then you can for example use:
```
library(devtools)
install_github(DavidFirth/qvcalc)
```
For the released version on CRAN:
```
install.packages("qvcalc")
```

## References

* Firth, D. and Menezes, R. X. de (2004). Quasi-variances. *Biometrika* **91**, 65–80.  http://dx.doi.org/10.1093/biomet/91.1.65

* Firth, D. (2003). Overcoming the reference category problem in the presentation of statistical models. *Sociological Methodology* **33**, 1–18.  http://dx.doi.org/10.1111/j.0081-1750.2003.t01-1-00125.x
  
