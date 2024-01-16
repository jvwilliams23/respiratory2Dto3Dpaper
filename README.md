# respiratory2Dto3Dpaper

[![DOI](https://zenodo.org/badge/593775812.svg)](https://zenodo.org/badge/latestdoi/593775812)

This repository contains links to relevant software from our paper.

Our paper proposes a new approach for reconstructing patient-specific lung and airway geometries from a 2D X-ray image. This relies on a statistical shape and appearance model (SSAM) from a set of 3D lung shapes and digitally reconstructed radiographs (based on the CT data). We have released a package [`pyssam`](https://github.com/jvwilliams23/pyssam) to facilitate other SSAM studies.

## 2D-3D SSAM reconstruction code

We have provided the code for our 2D-3D shape reconstruction algorithm [here](https://github.com/jvwilliams23/respiratorySSAMpy) or at [doi: 10.5281/zenodo.10518240](https://doi.org/10.5281/zenodo.10518240). We provide a static version of the code in this DOI. The linked repository also contains a version which relies on our `pyssam` package, which is available [here](https://github.com/jvwilliams23/pyssam). Note that `pyssam` is under active development.

## CNN pytorch code

We have provided code and pre-trained models for lung and airway segmentations from CT images [here](https://github.com/jvwilliams23/respiratoryCNN-toolkit) or at [doi: 10.5281/zenodo.10512412](https://doi.org/10.5281/zenodo.10512412).

## CFD solver source code

Our 3D-0D OpenFOAM solver for flow in patient airways is given [here](https://github.com/jvwilliams23/deepLungFoam) or at [doi: 10.5281/zenodo.7448214](https://doi.org/10.5281/zenodo.7448214).

