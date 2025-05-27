# Knowledge Independence Breeds Disruption but Limits Recognition

https://doi.org/10.48550/arXiv.2504.09589

This repository contains data and code required to reproduce the findings in paper "Knowledge Independence Breeds Disruption but Limits Recognition". This repository is organized in the following way:

- A data file is anonymized if it contains identifiers that could reveal the identity of papers/authors/editors; all analyzed data can be found in the `data\` directory.
- Notebooks and code related to the data anonymization process can be found in the `0_anonymization` repository; code used for analysis and visualization can be found in the `1_underrepresentation`, `2_acceptance_delay`, and `3_citation_well` directories.
- `figures/` contains the visualization of the main results.


The project was created and executed on the the High Performance Computing Center from Southwest University and New York University Abu Dhabi. The code in this repo can run on any commercial laptop with Python 3 installed.

Python libraries:

pandas 1.2.0
numpy 1.19.2
scipy 1.7.4
matplotlib 3.3.2
scikit-learn 0.24.2
pycountry 20.7.3
fuzzywuzzy 0.18.0
beautifulsoup4 4.9.3
Unidecode 1.3.1
Each Jupyter Notebook is self-contained and can be executed using a Notebook Server. The expected outputs are in the Jupyter Notebooks themselves, as well as contained in the figures/ directory.
