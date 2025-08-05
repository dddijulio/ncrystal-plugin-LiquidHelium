ncrystal-plugin-LiquidHeliumData
================================================

Plugin for NCrystal, which provides the user with extra NCMAT data files for Liquid Helium at specific temperatures.

After installation, use for instance nctool --browse to see the provided file names. For instance, to use the material at 1.3K, one would use a cfg-string like "plugins::LiquidHeliumData/LiquidHelium_T1.3K.ncmat".

Available temperatures are listed below.

1.3 K: This NCMAT file was generated using the approach described in [1] and the model used includes both single-phonon and multi-phonon extications. 

NCMAT files based on an effective model are included at temperatures of 0.8 K, 1.0 K, and 1.3 K. These were generated following the approach described in [1], however the Lorentzian profile for the single-phonon component was replaced with a Gaussian profile. 

[1] J.R. Granada, D.D. DiJulio, J.I. Marquez Damian, G. Muhrer, Nuclear Inst. and Methods in Physics Research, A 1053 (2023) 168284, https://doi.org/10.1016/j.nima.2023.168284
