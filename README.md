# PinhoLab - WingBox

![Exploded rendered view of the wing-box model inspired on the Airbus A350](./graphics/exploded.png)

:bulb: This is very large wing-box finite element model inspired on the Airbus A350XWB. It was built from publicly availble materials and is intended for research purposes only. The model was built as a test bed for our [high performance material modelling framework based on Abaqus user subroutines.](https://github.com/ImperialCollegeLondon/hpmscmmf)

## Repository organisation

- *Model L1 - full wing* - contains the Abaqus input files for the full wing model (***15M DoFs, 2.7M elements***);

![The wingbox model](./graphics/wing_transparent.png)

- *Model L2 - intermediate assembly* - contains the Abaqus input files for the intermediate assembly model of the critical region of the wingbox;

![The intermediate assembly model](./graphics/wsa_transparent.png)

- *Model L3 - stringer run out detail* - contains the Abaqus input files for the stringer run out detail model;

![](./graphics/wsro_transparent.png)

- *Model L4 - stringer web detail* - contains the Abaqus input files for the stringer web detail model;

![](./graphics/wweb_transparent.png)

- *damage initiation input files* - example files for the damage initiation analysis using [this codebase](https://github.com/ImperialCollegeLondon/hpmscmmf)
- *damage evolution input files* - example files for the damage evolution analysis using [this codebase](https://github.com/ImperialCollegeLondon/hpmscmmf)


## Requirements

- Abaqus 2019+
- [HPMSCMMF user subroutines](https://github.com/ImperialCollegeLondon/hpmscmmf) (for damage initiation and evolution analysis)


## Citation and licensing

The models are free to use within the scope of the [licence](LICENCE) and with proper citation.

You should be able to download the corresponding citation file from the sidebar under `Cite this repository` below the About section.

All citation informatin is also available in the `CITATION.cff` file.

This model was used in these publications (please consult them for more information and consider citing them if you use this model):

- [S. T. Pinho, M. Matos, R.O.S.S. da Costa, A. Ibbotson, M. Ostergaard. Enabling multiscale analysis of very large composite structures. COMPOSITES 2021, 22-24 September 2021, Göteborg, Sweden](https://doi.org/10.23967/composites.2021.123)

- [S. T. Pinho, R.O.S.S. da Costa, M. Matos, A. Ibbotson, M. Ostergaard. Multiscale analysis of an aircraft wingbox . ECCM20. 26-30 June, 2022, Lausanne, Switzerland](https://doi.org/10.5075/epfl-298799_978-2-9701614-0-0)

- [R.O.S.S. da Costa. Finite element methodologies for structural design and optimisation. PhD Thesis, Imperial College London, 2023](https://doi.org/10.25560/105865)

## Contributors

[Rui Costa](https://github.com/rorlandoc) ([email](mailto:r.costa18@imperial.ac.uk)) | [Silvestre Pinho](https://github.com/silvestretpinho) ([email](mailto:silvestre.pinho@imperial.ac.uk))
