# svSocket

[![Linux & OSX Build Status](https://travis-ci.org/SciViews/svSocket.svg )](https://travis-ci.org/SciViews/svSocket)
[![Win Build Status](https://ci.appveyor.com/api/projects/status/github/SciViews/svSocket?branch=master&svg=true)](http://ci.appveyor.com/project/phgrosjean/svSocket)
[![Coverage Status](https://img.shields.io/codecov/c/github/SciViews/svSocket/master.svg)
](https://codecov.io/github/SciViews/svSocket?branch=master)
[![CRAN Status](http://www.r-pkg.org/badges/version/svSocket)](http://cran.r-project.org/package=svSocket)
[![License](https://img.shields.io/badge/license-GPL-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)

SciViews R socket server.

The [R-Forge version](https://r-forge.r-project.org/projects/sciviews/)) is moved to Github on 2016-03-16 (SVN version 569). **Please, do not use R-forge anymore for SciViews development, use this github repository instead.**


## Installation

### Latest stable version

The latest stable version of **svSocket** can simply be installed from [CRAN](http://cran.r-project.org):

```r
install.packages("svSocket")
```


### Development version

Make sure you have the **devtools** R package installed:

```r
install.packages("devtools")
```

Use `install_github()` to install the **svSocket** package from Github (master branch):

```r
devtools::install_github("SciViews/svSocket")
```

R should install all required dependencies automatically, and then it should compile and install **svSocket**.

Latest devel version in source and Windows binaires formats also available from [appveyor](https://ci.appveyor.com/project/phgrosjean/svSocket/build/artifacts).


## Usage

Make the **svSocket** package available in your R session:

```r
library("svSocket")
```

Get help about this package:

```r
library(help = "svSocket")
help("svSocket-package")
```
