
# mason.rpkg

> A generic R package template for [Mason](https://github.com/gaborcsardi/mason).

## Installation

You can install this package from GitHub, using the `devtools` package:

```r
devtools::install_github("gaborcsardi/mason.rpkg")
```

## Usage

Call Mason from an empty directory:

```r
dir.create("mypackage")
setwd("mypackage")
library(mason)
mason("rpkg")
```

## License

MIT © [Gábor Csárdi](https://github.com/gaborcsardi)
