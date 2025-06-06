# saveCDC2
Code for downloading, filtering, and making maps from CosmoDC2 data

Requires:
* [urllib](https://docs.python.org/3/library/urllib.html), [requests](https://pypi.org/project/requests/), [beautifulsoup4](https://pypi.org/project/beautifulsoup4/) (downloading CosmoDC2 data)
* [GCRCatalogs](https://github.com/LSSTDESC/gcr-catalogs) (filtering and extracting CosmoDC2 data from the downloaded files)

This notebook is adapted from [LSSTDESC tutorial](https://github.com/LSSTDESC/gcr-catalogs/blob/master/examples/GCRCatalogs%20Demo.ipynb) to work without server access.

I used Python 3.8.12, requests v2.27.1, bs4 v4.10.0, GCRCatalogs v1.3.5, but it should be consistent with other Python and package versions
