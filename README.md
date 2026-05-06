#  Master's Thesis
> This repository is a work in progress while my master's thesis is being finalized.
 

## About
This repository contains reproducible Jupyter notebooks developed as part of my master's thesis at the University of Oslo.
The project focuses on a experimental high-energy physics analysis using ATLAS Open Data for education, with an emphasis on dark matter searches in a supersymmetric framework with accompanying statistical analysis. The notebooks are designed to be self-contained and reproducible, enabling users to explore the analysis workflows from data handling to final results. 

## Thesis
- **Title:** Dark matter searches in two-lepton final states with missing transverse energy using ATLAS open data 
- **Author:** Emily Puchala
- **Institution:** University of Oslo, Faculty of Mathematics and Natural Sciences
- **Year:** 2026

---
## Repository Structure
- `statistics_analysis.ipynb`: statistical analysis and interpretation of results
- `supersymmetry_analysis_local.ipynb`: analysis using locally stored datasets
- `supersymmetry_analysis_2025beta_release.ipynb`: analysis using ATLAS Open Data (via atlasopenmagic)
- `supersymmetry_analysis_test.ipynb`: test version using atlasopenmagic for all datasets
- `environment.yml`: environment configuration

---
## Notebooks
This repository includes multiple versions of the supersymmetry analysis notebook. These versions differ in how the datasets are loaded, the analysis content itself is identical. 
- `statistics_analysis.ipynb`  
  - Performs statistical analysis and interpretation of results.
- `supersymmetry_analysis_local.ipynb`  
  - Uses locally downloaded datasets
  - Includes data, background Monte Carlo (MC), and signal MC samples
- `supersymmetry_analysis_2025beta_release.ipynb`  
  - Uses 2025-beta release of ATLAS Open Data for education via atlasopenmagic
  - Includes data, background MC samples (no signal MC samples)
  - Recommended skim: "2to4lep"
- `supersymmetry_analysis_test.ipynb`
  - Test version using atlasopenmagic
  - Includes data, background MC, and signal MC samples

These notebooks represent the core computational components used to produce the results presented in the thesis.

---
## Running the Notebooks Online
### Run Online
**Binder** </br>
- Launch an interactive environment directly in your browser with [Binder](https://mybinder.org/v2/gh/emilypuchala/MasterThesis.git/HEAD)


**Google Collab** 

> Work in Progress

- [statistics_analysis](https://colab.research.google.com/github/emilypuchala/MasterThesis/blob/main/statistics_analyis.ipynb)
- [supersymmetry_analysis_2025beta_release](https://colab.research.google.com/github/emilypuchala/MasterThesis/blob/main/supersymmetry_analysis_2025beta_release.ipynb)


### Run Locally
To run the notebooks locally, ensure you have installed a way to run python with a Jupyter notebook.

1. Download the notebooks from this repository. Clicking [this link](https://github.com/emilypuchala/MasterThesis/archive/refs/heads/main.zip) will download a .zip file with all files in this repository. 
2. Navigate to downloads and unzip the file.
3. To open the Jupyter notebook interface in your browser, run the following in the command line:
```jupyter notebook```
4. In the browser interface, navigate to where the unzipped file is located.
5. Open and run the analysis notebook.



#### Requirements
- Python 3.10 or above
- Jupyter Notebook
- Dependencies listed in `environment.yml`

---

