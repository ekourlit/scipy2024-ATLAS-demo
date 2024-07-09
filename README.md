# How the Scientific Python ecosystem helps answering fundamental questions of the Universe

**Abstract**

The ATLAS experiment at CERN explores vast amounts of physics data to answer the most fundamental questions of the Universe. The prevalence of Python in scientific computing motivated ATLAS to adopt it for its data analysis workflows while enhancing users' experience. This talk will describe to a broad audience how a large scientific collaboration leverages the power of the Scientific Python ecosystem to tackle domain-specific challenges and advance our understanding of the Cosmos. Through a simplified example of the renowned Higgs boson discovery, attendees will gain insights into the utilization of Python libraries to discriminate a signal in immersive noise, through tasks such as data cleaning, feature engineering, statistical interpretation and visualization at scale.

## Data access
The data used in this demonstrator are part of the 2024 Open Data for Research release from the ATLAS experiment and can be found at DOI:[10.7483/OPENDATA.ATLAS.9HK7.P5SI](http://doi.org/10.7483/OPENDATA.ATLAS.9HK7.P5SI).

## Running the notebooks on your personal computer

If you have some version of conda/mamba/Anaconda/Miniconda/Miniforge, you can install the [requirements.txt](requirements.txt) as a new environment, then activate that environment and run the notebook in e.g. JupyterLab.

```bash
conda env create -f requirements.txt   # can replace "conda" with "mamba"
conda activate coffea_latest
```