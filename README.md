# MITgcm_dischplume

New Setup Directions: Download MITgcm from mitgcm.org as usual and copy the iceplume folder into the "pkg" folder. Note that
the main difference between this version and that from Cowton et al., 2015 is that the discharge plume is resolved and the iceplume package
has been modified to only specify the volumetric flow at the source of discharge location instead of parameterizing the vertical plume entrainment (as discussed 
in the SI of Zhao et al. 2023, GRL) within iceplume_calc.f.

A test case can be set up by executing gendata.m in the input folder.
