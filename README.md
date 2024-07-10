# How the Scientific Python ecosystem helps answering fundamental questions of the Universe

**Abstract**

The ATLAS experiment at CERN explores vast amounts of physics data to answer the most fundamental questions of the Universe. The prevalence of Python in scientific computing motivated ATLAS to adopt it for its data analysis workflows while enhancing users' experience. This talk will describe to a broad audience how a large scientific collaboration leverages the power of the Scientific Python ecosystem to tackle domain-specific challenges and advance our understanding of the Cosmos. Through a simplified example of the renowned Higgs boson discovery, attendees will gain insights into the utilization of Python libraries to discriminate a signal in immersive noise, through tasks such as data cleaning, feature engineering, statistical interpretation and visualization at scale.

**Disclaimer**

This is partially a presentation, partially a demonstration. The aim is to showcase how libraries of the Scientific Python ecosystem are used in fundamental particle physics research.

ATLAS has recently released a significant amount of open data for research. We hope scientists, and especially computer scientists, explore them and embrase on a constuctive dialogue with us. This notebook demonstrates a simplified analysis of those data.

## Data access
The data used in this demonstrator are part of the 2024 ppen data for research release from the ATLAS experiment and can be found at DOI:[10.7483/OPENDATA.ATLAS.9HK7.P5SI](http://doi.org/10.7483/OPENDATA.ATLAS.9HK7.P5SI).

More information about the data can be found [here](https://opendata.atlas.cern/docs/documentation/overview_data/data_research_2024).

## Running the notebooks on your personal computer

If you have some version of conda/mamba/Anaconda/Miniconda/Miniforge, you can create and activate a Python environment, install the [`requirements.lock`](requirements.lock) built from the high level [`requirements.txt`](requirements.txt),  and run the notebook in e.g. JupyterLab.

```console
conda env create --name scipy2024-atlas-demo --yes python=3.9   # can replace "conda" with "mamba"
conda activate scipy2024-atlas-demo
python -m pip install --upgrade --no-deps --require-hashes --requirement requirements.lock
```

## Acknowledgements

Matthew Feickert, Alexander Held, and Gordon Watts are supported by the U.S. National Science Foundation (NSF) under Cooperative Agreement [OAC-1836650](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1836650) and [PHY-2323298](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2323298) (IRIS-HEP).
Evangelos Kourlitis is supported by the Excellence Cluster ORIGINS, which is funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under Germany's Excellence Strategy - EXC-2094-390783311 and by the German Federal Ministry of Education and Research Project 05H2021 (ErUM-FSP T02) - "Run 3 von ATLAS am LHC: Analysis Infrastructure for the ATLAS Detektor at the LHC".
