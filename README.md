## Description

This is a custom, more feature-rich GRASS GIS 7 PKGBUILD for Arch Linux. Main differences compared to `grass' from the AUR:

- LIDAR support via liblas,
- OpenMP paralelism enabled where applicable (see http://grasswiki.osgeo.org/wiki/OpenMP),
- ODBC and Postgres support,
- LAPACK and BLAS support (needed for e.g. the v.kriging add-on),
- installed with other GRASS versions co-existence in mind.

