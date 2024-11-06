# QDM magnetic microscopy dataset of a speleothem from Morocco - MAT-file

This dataset presents a high-resolution magnetic map of a stalagmite sample from Wintimdouine Cave, Morocco, created using Quantum Diamond Microscope (QDM) measurements at Harvard University. The data were collected to explore the magnetic remanence properties of hematite and magnetite within the sample, providing insight into past geomagnetic field variations recorded in cave deposits.

### Methodology

- **Measurement Equipment**: Quantum Diamond Microscope (QDM)
- **Sample Dimensions**: 1410 μm x 2256 μm
- **Grid Spacing**: 2.35 μm
- **Sensor-Sample Distance**: ~5 μm
- **Total Data Points**: ~576,000
- **Magnetic Measurement Mode**: Projected Magnetic Microscopy (PMM)  
- **Data Conversion**: Magnetic field values converted to the vertical component, \( b_z \), across the grid.

### Sample Characteristics

The stalagmite sample carries magnetic remanence dominated by hematite and magnetite grains:
- **IRM Pulse Fields Applied**: Two isothermal remanent magnetization (IRM) pulse fields were applied:
  - 2.7 T in the +Y direction (high coercivity, aligning hematite grains).
  - 0.3 T in the -Y direction (low coercivity, aligning magnetite grains).

### Usage Notes

This dataset can be used for detailed analysis of spatial variations in magnetic remanence, aiding studies in:
- Paleomagnetic research
- Environmental magnetism
- Cave sediment studies

| | Summary |
|--:|:--|
| File | `Bz_uc0.mat` |
| Size | 10.2 Mb |
| Version | [v1](https://github.com/fatiando-data/CHANGEME/releases/latest) |
| DOI | [10.6084/m9.figshare.22965200.v1](https://doi.org/10.6084/m9.figshare.22965200.v1) |
| License | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) |
| MD5 | `md5:115a15a3aa78542b17ad321a7f0c8edb` |
| SHA256 | `sha256:c9dd6a43d12d2b75f271e831265e36290e6cd22fbcd747233ef756bef0b69888` |
| Source | [10.6084/m9.figshare.22965200.v1](https://doi.org/10.6084/m9.figshare.22965200.v1) |
| Original license |  [CC0](https://creativecommons.org/publicdomain/zero/1.0/)  |
| Processing code | [`prepare.ipynb`](https://nbviewer.org/github/fatiando-data/CHANGEME/blob/main/prepare.ipynb) |

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
