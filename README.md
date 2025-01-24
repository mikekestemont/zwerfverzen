[![DOI](https://zenodo.org/badge/595561943.svg)](https://doi.org/10.5281/zenodo.14732465)

This repository documents the code and data supporting the following publication:

> Mike Kestemont, "Zwerfverzen. De computationele detectie van intertekstualiteit in de Middelnederlandse epiek". *Tijdschrift voor Nederlandse Taal- en Letterkunde* (2025).

The contents of this repository are as follows:
- `/data`: the annotated data used in this project, in particular:
     - `intertexts.xlsx`: an overview of the intertexts which were annotated in the XML
     - `xml/*.xml`: the enriched (POS + lemma) XML files, in which the intertexts were annotated at the verse level
     - `metadata_corrected.xlsx`: the metadata which were assigned to works

- `/figures`: the automatically generated plots and tables which were included in the analysis
- `/notebooks`: the Python notebooks used. (Please note that I don't advise to re-run the preprocessing notebook, as it will overwrite the manual annotations that were applied to the XML files.) Some additional analysis are reported for the sake of future references, even though they weren't detailed in the paper.

The Python version used was 3.12.7. The precise dependencies can be installed from `notebooks/requirements.txt`.

## Persistent archiving
Releases of this repository are sustainably mirrored on [Zenodo](https://zenodo.org/), ensuring long-term archival access to this material. Please consider citing the accompanying paper if you re-use this code for academic purposes.

## License
[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
