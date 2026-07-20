This repository is a personal project of mine for the collection of material parameter files for use with the SCAPS-1D solar-cell simulation program.

Each new material entry may include the following:
  1) A saved SCAPS-1D material or layer file.
  2) A spreadsheet listing the parameters.
  3) The literature source used.
  4) Notes about missing, assumed, or default parameters.

This library will feature a variety of materials consisting of ETLs, HTLs, absorbers, etc. all of which will be classified as such.

!!IMPORTANT NOTICE!!

1) The files in this repository are based on literature simulation presets. They should therefore NOT be interpreted as definitive or universal experimental properties of the materials.

Material parameters can vary greatly depending on synthesis method, crystal structure, composition, temperature, measurement method, etc.

Users should inspect the cited source and verify that the parameters are suitable for their own simulations and work.

2) Some information, such as bulk and interfacial defect densities and thicknesses, are not always provided in the sources and citations. 

So, it is left up to the users to fill these parameters with their desired values. A good start for bulk and interfacial densities would be 1 x 10^15 cm^-3 and 1 x 10^14 cm^-2, respectively. 

For the thickness, it largely depends on the layer role. For example, a larger thickness for absorber layers would yield better results. 

Sweep the parameters, extract the data, and find the optimal values for your chosen layers which provide the best readings.
