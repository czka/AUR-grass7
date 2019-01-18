## Description

This is a custom, more feature-rich GRASS GIS 7 PKGBUILD for Arch Linux. Main differences compared to `grass' from the AUR:

- ~~LIDAR support via liblas,~~ *(not until liblas is buildable on Arch back again - some info on https://aur.archlinux.org/packages/liblas/)*
- OpenMP parallelism enabled where applicable (see http://grasswiki.osgeo.org/wiki/OpenMP),
- support bzip2 data compression in libraster,
- ODBC support,
- LAPACK and BLAS support (needed for e.g. the v.kriging add-on).
