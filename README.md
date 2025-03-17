# Data Analysis Project
### Project Overview
This project is focused on analyzing a dataset to gain insights through data visualization, statistics, and machine learning predictions. The project also includes weekly meeting minutes to track the progress of the project.

### File Structure
- data/: Contains the original dataset file:
    - dataset.csv: The raw data used for analysis.

- docs/: Contains documentation and meeting minutes:
    - Weekly meeting minutes.
    - Project-related reports.

- src/: Python scripts used for the project including:
    - 01_generate-data.py: generate raw data
    - 02_visualize-data.py: generates data visualizations.
    - 03_plot-predictions: builds and evaluates machine learning models to predict.

- images/: Visualizations generated during the analysis:
    - dataset-image.png: dataset visualizations.
    - predictions.png: Model prediction visualizations.

- reports/: Contains the Jupyter notebook:
    - Report.ipynb: Main analysis notebook containing the data processing, visualizations, and machine learning predictions.

- environment.yaml: File for setting up the Conda environment with all the required dependencies.

### How to Run the Analysis

1. Install necessary libraries by creating the environment using the `environment.yaml` file in terminal:

`conda env create -f environment.yaml`

2. Activate the environment:

`conda activate project-env`

3. Launch JupyterLab
4. Open and run the `Report.ipynb` notebook from the `reports/` folder 