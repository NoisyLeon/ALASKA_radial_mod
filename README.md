# ALASKA_radial_mod
This repository provides 3D shear wave velocity model with radial anisotropy beneath Alaska. 

Reference:
Feng, L., and M.H.Ritzwoller, 2019. A 3-D shear velocity model of the crust and uppermost mantle
  beneath Alaska including apparent radial anisotropy, J. Geophys. Res. Solid Earth, submitted
  
# Vsv_mod includes files with Vsv and uncertainties

For example, there is file 202.0_66.5_vsv.mod, for (lon, lat) = (202., 66.5). The first few kms look as follows:

Depth from Surface(km) Vs(km/sec) Uncertainty of Vs(km/sec)

0 1.55083 0.780514

0.1 1.55083 0.780514

0.2 3.08091 0.857384

0.3 3.08635 0.697823

0.4 3.09178 0.129166

0.5 3.09721 0.126227

0.6 3.10265 0.123294

0.7 3.10808 0.12037

0.8 3.11352 0.117454

0.9 3.11895 0.114547

1 3.12439 0.111653

1.1 3.12982 0.108794

1.2 3.13526 0.106005

# gamma_mod includes files with gamma and uncertainties

For example, there is file 192.0_63.0_gamma.mod, for (lon, lat) = (192., 63.). The contents of the file look as follows:

0 0

3.16417 1.02841

1.63701 1.5751


The first row are gamma and uncertainty of gamma for sediments, and the second and third rows are gamma and uncertainty of gamma for crystalline crust and mantle. 

For the grid point located in Colville Basin, e.g., 210.0_69.0_gamma.mod

The contents of the file look as follows:

22.7717 1.70872

0 0

4.23877 1.03837


Indicating that we turn on sedimentary anisotropy but no radial anisotropy in the crystalline crust.


