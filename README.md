[//]: # (Copyright &#40;c&#41; European Space Agency, 2024.)
[//]: # ()
[//]: # (This file is subject to the terms and conditions defined in file 'LICENCE.txt', which)
[//]: # (is part of this source code package. No part of the package, including)
[//]: # (this file, may be copied, modified, propagated, or distributed except according to)
[//]: # (the terms contained in the file ‘LICENCE.txt’.)
[![License: ESA permissive](https://img.shields.io/badge/ESA%20Public%20License-Permissive-blue.svg)](https://github.com/esa/gaia-bhthree/blob/main/LICENSE.txt)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/esa/gaia-bhthree/1.0.0?labpath=Gaia_BH3_fit_astrometric_orbit.ipynb)

# Analysis of Gaia measurement timeseries that led to the discovery of the black hole Gaia BH3 
A jupyter notebook for fitting the orbit of Gaia BH3 and determining the black hole's mass.  
To execute it online, please click on the `binder` badge above or navigate to https://mybinder.org/v2/gh/esa/gaia-bhthree/1.0.0?labpath=Gaia_BH3_fit_astrometric_orbit.ipynb 

## This notebook was prepared by the Gaia collaboration. If you find it useful for your research or otherwise, please reference the discovery paper (Gaia Collaboration, Panuzzo, et. al. 2024 "Discovery of a dormant 33 solar-mass black hole in pre-release Gaia astrometry") and the DOI associated with this notebook repository.

## Content of this repository
- 2 data files; one contains the Gaia astrometric timseries, the other contains the Gaia radial-velocity timeseries 
These are the same as available at the CDS [insert link]. The applicable description file (CDS readme) is [insert link]  
- 1 notebook
- 1 environment.yml file
- 1 license file
- 1 readme file

## The notebook demonstrates the following steps:
- Load the timeseries data of the Gaia astrometric instrument. The data are identical to the ones published with the paper and available at the CDS.
- Fit an orbit to the astrometric data and determine the black hole's mass.
- Load the timeseries data of the Gaia radial-velocity instrument. The data are identical to the ones published with the paper and available at the CDS.
- Fit an orbit to the combination of astrometric and radial-velocity data and determine the black hole's mass.

## Environment installation
- This notebook is most easily executed within the associated `binder` environment in a web browser, where no software installation is needed.
- For local execution, one can use the environment.yml file included in this repository to create a python environment using conda with the necessary dependencies for code execution:  
`conda env create --file gaia-bhthree/environment.yml`

##