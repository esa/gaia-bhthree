[//]: # (Copyright &#40;c&#41; European Space Agency, 2026.)
[//]: # ()
[//]: # (This file is subject to the terms and conditions defined in file 'LICENCE.txt', which)
[//]: # (is part of this source code package. No part of the package, including)
[//]: # (this file, may be copied, modified, propagated, or distributed except according to)
[//]: # (the terms contained in the file ‘LICENCE.txt’.)
[![License: ESA permissive](https://img.shields.io/badge/ESA%20Public%20License-Permissive-blue.svg)](https://github.com/esa/gaia-bhthree/blob/main/LICENSE.txt)

# Analysis of Gaia DR4 astrometric timeseries of the black hole Gaia BH3 
A jupyter notebook for fitting the orbit of Gaia BH3 and determining the black hole's mass.  

## ## This notebook was prepared by the Gaia collaboration. If you find it useful for your research or otherwise, please follow these acknowledgement and citation instructions: https://gea.esac.esa.int/archive/documentation/GDR3/Miscellaneous/sec_credit_and_citation_instructions/

## Content of this repository
- 1 notebook
- 1 environment.yml file
- 1 license file
- 1 readme file

## The notebook demonstrates the following steps:
- Load the timeseries data of the Gaia astrometric instrument. The data are part of the Gaia DR4 pre-release, see https://www.cosmos.esa.int/web/gaia/dr4-prerelease - Fit an orbit to the astrometric data and determine the black hole's mass.
- Fit an orbit to the astrometric data and determine the black hole's mass.

## Environment installation
- For local execution, one can use the environment.yml file included in this repository to create a python environment using conda with the necessary dependencies for code execution:  
`conda env create --file gaia-bhthree/environment.yml`

##