# QDM magnetic microscopy dataset of a speleothem from Morocco

High-resolution magnetic map of a stalagmite sample from Wintimdouine Cave,
Morocco, created using Quantum Diamond Microscope (QDM) measurements at Harvard
University. The data were collected to explore the magnetic remanence
properties of hematite and magnetite within the sample, providing insight into
past geomagnetic field variations recorded in cave deposits.

Available as both a compressed netCDF file as well as the original Matlab file
(`.mat`) in the Harvard format.

| | Summary |
|--:|:--|
| File | `morroco-speleothem-qdm.mat` |
| Size | 10.2 Mb |
| MD5 | `md5:268bd3af5e350188d239ff8bd0a88227` |
| SHA256 | `sha256:2f2fbb4dfb645e27af09c76199ebcdd42c0fa137588072d3748eaf3be61fa0a6` |
| File | `morroco-speleothem-qdm.nc` |
| Size | 1.9 Mb |
| MD5 | `md5:fc2f5eafaa06cf32961bedbc737c58f5` |
| SHA256 | `sha256:c2e1855b5870b5397593c6c8d177e7a983d4a0e0ea0494a57888bab6e58b0887` |
| Version | [v1](https://github.com/fatiando-data/CHANGEME/releases/latest) |
| DOI | [10.5281/zenodo.14884823](https://doi.org/10.5281/zenodo.14884823) |
| License | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) |
| Source | [10.6084/m9.figshare.22965200.v1](https://doi.org/10.6084/m9.figshare.22965200.v1) |
| Original license |  [CC0](https://creativecommons.org/publicdomain/zero/1.0/)  |
| Processing code | [`prepare.ipynb`](https://nbviewer.org/github/fatiando-data/CHANGEME/blob/main/prepare.ipynb) |

## Changes made

> These are the changes made to the original dataset.

Version 1:

* Convert from Matlab format to compressed NetCDF.
* Add metadata to the NetCDF file.
* Rename the original Matlab file.

## About this repository

This is a place to format and prepare the original dataset for use in our
tutorials and documentation.

We include the source code that prepares the datasets for redistribution by
filtering, standardizing, converting coordinates, compressing, etc.
The goal is to make loading the data as easy as possible (e.g., a single call
to `pandas.read_csv` or `xarray.load_dataset`).
Whenever possible, the code also downloads the original data (otherwise the
original data are included in this repository).

> 💡 **Tip:** The easiest way to download this dataset is using
> [Pooch](https://www.fatiando.org/pooch), particularly to download straight
> from the DOI of a release.

## Contributing

See our [Contributing Guidelines][contrib] for information on proposing new
datasets and making changes to this repository.

## License

All Python source code is made available under the BSD 3-clause license. You
can freely use and modify the code, without warranty, so long as you provide
attribution to the authors.

Unless otherwise specified, all data files and figures created by the code are
available under the Creative Commons Attribution 4.0 License (CC-BY).

See [`LICENSE.txt`](LICENSE.txt) for the full text of each license.

The license for the original data is specified in this `README.md` file.


[contrib]: https://github.com/fatiando-data/.github/blob/main/CONTRIBUTING.md
