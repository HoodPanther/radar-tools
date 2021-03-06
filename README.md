# radar-tools
Extends the functionality of Py-ART and csu-radar-tools to allow:
 - simplified download of NEXRAD II volume scans from AWS
 - calculation of rainfall estimates from these volume scans
 - gridding of rainfall products
 - extraction of rainfall products at series of points (rain gages)
 - extraction of basin averaged rain rate (under shapefile)
 - extraction of DSD parameters at a point (for comparison with disdrometer data)

 ## Run example notebooks
```engine='bash'
$ git clone https://github.com/jsignell/radar-tools.git
$ cd radar-tools
$ conda env create
$ source activate radar-tools
$ jupyter notebook
```
