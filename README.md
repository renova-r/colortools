# colortools

Tools to select and work with color schemes in a hue-saturation-value (HSV) color model.

Compatibility updates by Renova.

Version 0.1.5.9001: `NAMESPACE` now imports the `grDevices` and `graphics` functions the package calls (`col2rgb`, `hsv`, `rgb2hsv`, `par`, `polygon`, `text`, and others), and the DESCRIPTION title case, Description full stop and stale `Date` field are updated.

## Install

```r
install.packages("colortools", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/colortools) for builds and installation. This release is tagged on GitHub as `renova-0.1.5.9001`:

```r
remotes::install_github("renova-r/colortools@renova-0.1.5.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

colortools is by Gaston Sanchez; the original CRAN package is at <https://CRAN.R-project.org/package=colortools>. License: GPL-3; see [COPYING](COPYING).

Original author credits: Gaston Sanchez

Author metadata is formatted consistently with Authors@R; original authors and maintainer roles are retained.

### Metadata compatibility

Added structured author metadata using the existing author and maintainer details.
