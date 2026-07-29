![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21599356.svg)

## Citation
If you use this database, please cite:
Mostafa E. Abd El-salam, D. of N. and T. (2026). SCAPS-1D Parameter Database for Photovoltaic Materials: Absorbers, Buffers, ETLs, TCOs, and HTLs. [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.21599357

This repository is a personal project of mine for the collection of material parameter files for use with the SCAPS-1D solar-cell simulation program.

Each new material entry may include the following:
  1) A saved SCAPS-1D material or layer file.
  2) A spreadsheet listing the parameters.
  3) The literature source used.
  4) Notes about missing, assumed, or default parameters.

## Catalogue of Curated Materials (85 Total)

* Absorber Layers (26): AgBiS2 (Silver Bismuth Sulfide), BaZrS3 (Barium Zirconium Sulfide), CdTe (Cadmium Telluride), CH3NH3SnBr3 (Methylammonium Tin Bromide), CH3NH3SnI3 (Methylammonium Tin Iodide), CMTS (Copper Manganese Tin Sulfide), Cs2AgBiBr6 (Cesium Silver Bismuth Bromide), Cs2PdBr6 (Cesium Palladium Bromide), Cs2PtI6 (Cesium Platinum Iodide), Cs2TiBr6 (Cesium Titanium Bromide), Cs2TiI6 (Cesium Titanium Iodide), Cs3Bi2I9 (Cesium Bismuth Iodide), CsPbI3 (Cesium Lead Iodide), CsSnBr3 (Cesium Tin Bromide), CsSnI3 (Cesium Tin Iodide), CuBi2O4 (Copper Bismuth Oxide), CuSbS2 (Copper Antimony Sulfide), CZTSSe (Copper Zinc Tin Sulfur Selenide), Eu2NiMnO6 (Europium Nickel Manganese Oxide), FASnBr3 (Formamidinium Tin Bromide), FASnI3 (Formamidinium Tin Iodide), MAPbI3 (Methylammonium Lead Iodide), MASnI3 (Methylammonium Tin Iodide), Sb2Se3 (Antimony Selenide), SrSbI3 (Strontium Antimony Iodide), WS2 (Tungsten Disulfide)

* Hole Transport Layers (HTL) (24): AlSb (Aluminum Antimonide), CFTS (Copper Iron Tin Sulfide), Cu2O (Copper(I) Oxide), Cu2Te (Copper(I) Telluride), CuGaSe2 (Copper Gallium Selenide), CuI (Copper(I) Iodide), CuO (Copper(II) Oxide), CuS (Copper(II) Sulfide), CuSCN (Copper(I) Thiocyanate), CZTS (Copper Zinc Tin Sulfide), MoO3 (Molybdenum Trioxide), MoS2 (Molybdenum Disulfide), NiOx (Nickel Oxide), P3HT (Poly(3-hexylthiophene-2,5-diyl)), Sb2(S,Se)3 (Antimony Sulfo-Selenide), SbS3 (Antimony Trisulfide), SnS (Tin(II) Sulfide), SnSe (Tin(II) Selenide), SnTe (Tin Telluride), SWCNT (Single-Walled Carbon Nanotubes), V2O5 (Vanadium(V) Oxide), WSe2 (Tungsten Diselenide), ZnTe (Zinc Telluride), Zr3P2 (Zirconium Phosphide)

* Electron Transport Layers (ETL) (16): Al-ZnO (Aluminum-doped Zinc Oxide), AZO (Aluminum-doped Zinc Oxide), C60 (Fullerene C60), CdS (Cadmium Sulfide), CdZnS (Cadmium Zinc Sulfide), CeO2 (Cerium Oxide / Ceria), In2S3 (Indium(III) Sulfide), SnO2 (Tin(IV) Oxide), SnS2 (Tin Disulfide), TiO2 (Titanium Dioxide), WO3 (Tungsten Trioxide), ZnMnO (Zinc Manganese Oxide), ZnO (Zinc Oxide), ZnS (Zinc Sulfide), ZnSe (Zinc Selenide), ZrS2 (Zirconium Disulfide)

* Buffer Layers (12): Bi2S3 (Bismuth Sulfide), C60 (Fullerene C60), CdS (Cadmium Sulfide), Ga2O3 (Gallium Oxide), IGZO (Indium Gallium Zinc Oxide), MoS2 (Molybdenum Disulfide), PCBM ([6,6]-Phenyl-C61-butyric acid methyl ester), TiO2 (Titanium Dioxide), WS2 (Tungsten Disulfide), ZnO (Zinc Oxide), ZnS (Zinc Sulfide), ZnSe (Zinc Selenide)

* Transparent Conducting Oxides (TCO) (7): AZO (Aluminum-doped Zinc Oxide), BZO (Boron-doped Zinc Oxide), CTO (Cadmium Tin Oxide), FTO (Fluorine-doped Tin Oxide), IGZO (Indium Gallium Zinc Oxide), ITO (Indium Tin Oxide), IZO (Indium Zinc Oxide)

!!IMPORTANT NOTICE!!

1) The files in this repository are based on literature simulation presets. They should therefore NOT be interpreted as definitive or universal experimental properties of the materials.
Material parameters can vary greatly depending on synthesis method, crystal structure, composition, temperature, measurement method, etc.
Users should inspect the cited source and verify that the parameters are suitable for their own simulations and work.

2) Some information, such as bulk and interfacial defect densities and thicknesses, are not always provided in the sources and citations. 
So, it is left up to the users to fill these parameters with their desired values. A good start for bulk and interfacial densities would be 1 x 10^15 cm^-3 and 1 x 10^14 cm^-2, respectively. 
For the thickness, it largely depends on the layer role. For example, a larger thickness for absorber layers would yield better results. 
Sweep the parameters, extract the data, and find the optimal values for your chosen layers which provide the best readings.
