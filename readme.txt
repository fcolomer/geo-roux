Packages à installer (un fichier requirements.txt suit, mais certains packages j'ai dû les installer manuellement)

-numpy
-matplotlib
-shapefile
-proj
-geos
-basemap (---> installer matplotlib, puis proj et geos, et seulement ensuite,
				aller sur ce site https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap 
				et télécharger la version ad hoc [3.6 pour toi I guess] puis pip install nom-du-fichier.whl)

fichiers à avoir:
- dossier ne_10m_admin_0_countries qui contient notamment le fichier ne_10m_admin_0_countries.shp 
				(le fichier qui contient les polygones des différents pays)