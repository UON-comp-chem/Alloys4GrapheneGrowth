# Alloys4GrapheneGrowth

#
The repository contains the datasets for the manuscript on alloys for graphene growth.
# Manifest

* `structures_in_table1/` contains the structure files (*.cif and *.traj) for carbon, benzene, and graphene adsorption on 15 catalysts listed in Table 1.
*  `datasets/` contains the carbon, benzene, and graphene datasets generated in this study. The carbon and benzene data points were calculated using RPBE-D3, while the graphene data points were calculated using SCAN-rVV10.
* `gaspymongo.py` is a Python code that contains functions to read structures in the datasets folder. This code was copied from https://github.com/ulissigroup/GASpy. Credit goes to the GASpy developers and the original author, Prof. John Kitchin.
* `view.ipynb` is a Jupyter notebook script that demonstrates how to open the datasets using `gaspymongo.py`