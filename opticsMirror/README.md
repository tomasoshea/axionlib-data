The following directory contains data files with X-ray reflectivity pre-downloaded data from the [https://henke.lbl.gov/](https://henke.lbl.gov/) database. These files will be generated by the [TRestAxionOpticsMirror](https://sultan.unizar.es/rest/classTRestAxionOpticsMirror.html) metadata class. The files will be used by that class to quickly load reflectivity data in memory, in case the requested optics properties are already available a this database.

See [TRestAxionOpticsMirror](https://sultan.unizar.es/rest/classTRestAxionOpticsMirror.html) documentation for further details on how to generate or load these datasets.

The file is basically a table with 501 rows, each row corresponding to an energy, starting at 30eV in increments of 30eV. The last row corresponds with 15keV. The number of columns is 901, describing the data as a function of the angle of incidence in the range between 0 and 9 degrees with 0.01 degree precision.
