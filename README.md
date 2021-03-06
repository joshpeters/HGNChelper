[![R build status](https://github.com/waldronlab/HGNChelper/workflows/R-CMD-check/badge.svg)](https://github.com/waldronlab/HGNChelper/actions)
[![](https://cranlogs.r-pkg.org/badges/HGNChelper)](https://cran.r-project.org/package=HGNChelper)
[![Coverage Status](https://codecov.io/github/waldronlab/HGNChelper/coverage.svg?branch=master)](https://codecov.io/github/waldronlab/HGNChelper?branch=master)
[![Travis-CI Build Status](https://travis-ci.org/waldronlab/HGNChelper.svg?branch=master)](https://travis-ci.org/waldronlab/HGNChelper)


# HGNChelper: Identify and correct invalid gene symbols

## Updating

To update the symbols maps for human and mouse yourself, download this repository and run:

`./update.sh`

from its root directory. Note that this script uses the "roxygen2" 
R library to update the documentation.

Alternatively, you can use updated maps without updating the package, see `?getCurrentMaps`.

## Updating gh-pages

Note to self - when updating the vignette, update the gh-pages website 
(https://waldronlab.io/HGNChelper/) like this:

```
# pip install ghp-import
R -e "pkgdown::build_site()"
ghp-import docs/
git push
```
