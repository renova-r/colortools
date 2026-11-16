# colortools 0.1.5.9001

Renova release, based on CRAN colortools 0.1.5 (archived on CRAN 2022-06-23).

- `NAMESPACE`: 14 `importFrom()` directives added for `grDevices` (`col2rgb`, `dev.flush`, `dev.hold`, `hsv`, `rgb2hsv`) and `graphics` (`lines`, `mtext`, `par`, `plot.new`, `plot.window`, `polygon`, `rect`, `text`, `title`).
- `DESCRIPTION`: `Title` in title case and a full stop added to `Description` (metadata only).
- `DESCRIPTION`: stale optional `Date` field removed (metadata only).
- No R function bodies or documentation changed.

Release preparation:

- `DESCRIPTION`: `Version` set to `0.1.5.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 3 text) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added and is excluded from the R build.

Original author credits: Gaston Sanchez

Author metadata is formatted consistently with Authors@R; original authors and maintainer roles are retained.

### Metadata compatibility

Added structured author metadata using the existing author and maintainer details.
