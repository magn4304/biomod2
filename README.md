[![Cran Version](https://www.r-pkg.org/badges/version/biomod2?color=yellow)](https://cran.r-project.org/package=biomod2)
[![Github Version](https://img.shields.io/badge/devel%20version-4.1-3-blue.svg)](https://github.com/biomodhub/biomod2)
[![Last Commit](https://img.shields.io/github/last-commit/biomodhub/biomod2.svg)](https://github.com/biomodhub/biomod2/commits/master)
[![R build status](https://github.com/biomodhub/biomod2/workflows/R-CMD-check/badge.svg)](https://github.com/biomodhub/biomod2/actions)

<!-- [![Download](http://cranlogs.r-pkg.org/badges/grand-total/biomod2?color=yellow)](https://cran.r-project.org/package=segclust2d) -->
<!-- 
badge for github version :
badger::badge_github_version("biomodhub/biomod2", "blue") 
-->

<div style="text-align:center;">
**------------------------------------------------------------** <br/>
**Species distribution modeling, <br/>
calibration and evaluation, <br/>
ensemble modeling** <br/>
**------------------------------------------------------------**

https://biomodhub.github.io/biomod2/
</div>


### <i class="fas fa-tools"></i> Installation

<br/>

- **Stable version** (4.1-2) from [cran](https://CRAN.R-project.org/package=biomod2) :

```R
install.packages("biomod2", dependencies = TRUE)
```

<br/>

- **Development version** (4.1-3) from [biomodhub](https://github.com/biomodhub/biomod2) :

```R
library(devtools)
devtools::install_github("biomodhub/biomod2", dependencies = TRUE)
```

<br/><br/>


### <i class="fas fa-envelope-open-text"></i> Breaking news

**! `biomod2 4.1` is now available !**

`/!\` Package fresh start... meaning some changes in function names and parameters. We apologize for the trouble `>{o.o}<` <br/>
Sorry for the inconvenience, and please **feel free to indicate if you notice some strange new behaviors** !


#### <i class="fas fa-exchange-alt"></i> What is changed ?

- all code functions have been cleaned, and old / unused functions have been removed
- function names have been standardized (`BIOMOD_` for main functions, `bm_` for secundary functions)
- parameter names have been standardized (same typo, same names for similar parameters across functions)
- all documentation and examples have been cleaned up

#### <i class="fas fa-plus-square"></i> What is new ?

- plot functions have been re-written with `ggplot2`
- [`biomod2` website](https://biomodhub.github.io/biomod2/) has been created, with proper `roxygen2` documentation and help vignettes

#### <i class="fas fa-question-circle"></i> But... why ?

- “*For every minute spent on organizing, an hour is earned.*” — Benjamin Franklin
  - better documentation, better formation, better help provided
  - new improvements to come (update of single models, implementation of abundance models, etc)

<br/><br/>



<style>
.zoom p {
width:600px;
margin-left: auto;
margin-right: auto;
}
.zoom p:hover {
width:1200px;
position: relative;
z-index: 10;
}
</style>

<div class="zoom">
<p><img src="articles/pictures/SCHEMA_BIOMOD2_WORKFLOW_functions.png" alt="Main workflow"></img></p>
</div>



