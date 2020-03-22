## News
I'm no lonegr maintaining this actively. Use AUR [`grass`](https://aur.archlinux.org/packages/grass/) package instead.

## Description

This is a custom, more feature-rich GRASS GIS 7 PKGBUILD for Arch Linux. Main differences compared to `grass' from the AUR:

- ~~LIDAR support via liblas,~~ *(not until liblas is buildable on Arch back again - some info on https://aur.archlinux.org/packages/liblas/)*. BTW, replacement `v.in.pdal` and `r.in.pdal` have been there since GRASS 7.2.0 and 7.4.2. 
- OpenMP parallelism enabled where applicable (see http://grasswiki.osgeo.org/wiki/OpenMP),
- support bzip2 data compression in libraster,
- ODBC support,
- LAPACK and BLAS support (needed for e.g. the v.kriging add-on).
