# geo-roux

Packages to install (a requirements.txt file is given, but some packages have been installed manually)

Packages installed with pip:
 - numpy
 - matplotlib
 - shapefile
 - proj
 - geos

Package installed manually:
 - basemap
(to install, first install matplotlib, proj and geos and only then
go to https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap and download the ad hoc version
--3.9 for me-- then run pip install name-of-file.whl. This should look like basemap-1.2.2-cp39-cp39-win_amd64.whl)

Required files:
 - directory ne_10m_admin_0_countries which contains the file ne_10m_admin_0_countries.shp 
(this file contains the polygons from different countries and can also be downloaded here:
https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/)