# ADSS-SI
Data tables and plotting code for BiVO4 and NiSb2O6 libraries measured using (ADSS) in (DOI+link)

## Notebook environment setup 
### Requirements:
git (2.42.0 tested)
conda (23.7.4 tested)
### Instructions:
1. Install conda from any of the following sources:
- [miniforge](https://github.com/conda-forge/miniforge) (recommended)
- [miniconda](https://docs.conda.io/projects/miniconda/en/latest/)
- [Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)
2. Clone the ADSS-SI code repository: ```git clone https://github.com/High-Throughput-Experimentation/ADSS-SI.git```
3. Enter the local repo directory: ```cd ADSS-SI```
4. Install the notebook environment: ```conda env create -f conda_env.yml```
5. Start a local notebook server: ```jupyter lab```

## Files
| filename | description |
| -------- | ----------- |
| ADSS_BiVO4.svg | composite figure produced by ADSS_BiVO4_local.ipynb |
| ADSS_BiVO4_eche_data.pickle | dataframe of electrochemistry measurements from BiVO4 run |
| ADSS_BiVO4_icpms_data.pickle | dataframe of ICP-MS measurements of liquid aliquots from BiVO4 run |
| ADSS_BiVO4_inject_data.pickle | dataframe of solution injection times from BiVO4 run |
| ADSS_BiVO4_local.ipynb | Jupyter notebook for plotting BiVO4 data |
| ADSS_NiSb2O6.svg | composite figure produced by ADSS_NiSb2O6_local.ipynb |
| ADSS_NiSb2O6_eche_data.pickle | dataframe of electrochemistry measurements from NiSb2O6 run |
| ADSS_NiSb2O6_icpms_data.pickle | dataframe of ICP-MS measurements of liquid aliquots from NiSb2O6 run |
| ADSS_NiSb2O6_inject_data.pickle | dataframe of solution injection times from NiSb2O6 run |
| ADSS_NiSb2O6_local.ipynb | Jupyter notebook for plotting NiSb2O6 data |