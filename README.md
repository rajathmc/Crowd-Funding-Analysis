# Crowd-Funding-Analysis

Crowd-Funding Loan analysis performed on the Kiva dataset.

## Requirements

- Python 3.8 or later
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- squarify
- basemap

## Getting the data

1. Create a Kaggle account and install the Kaggle API (`pip install kaggle`).
2. Configure your `kaggle.json` API token under `~/.kaggle/`.
3. In the project root, create an `input/` directory.
4. Download and unzip the following Kaggle datasets into `input/`:
   - **Data Science for Good: Kiva Crowdfunding**
   - **Additional Kiva Snapshot**
   - **Multidimensional Poverty Measures**

   After downloading, the repository structure should look like:

```
Crowd-Funding-Analysis/
├── Kiva-Crowd-Funding-Analysis.ipynb
├── README.md
└── input/
    ├── data-science-for-good-kiva-crowdfunding/
    ├── additional-kiva-snapshot/
    └── multidimensional-poverty-measures/
```

## Running the notebook

1. Install the required libraries listed above.
2. Launch Jupyter:

```
jupyter notebook
```

3. Open `Kiva-Crowd-Funding-Analysis.ipynb`.
4. Run the cells sequentially to reproduce the analysis.
