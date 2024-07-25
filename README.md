# NYC Motor Vehicle Crash Analysis

## Table of Contents

- [Overview](#overview)
- [Project Proposal](#project-proposal)
- [Features](#features)
- [Data Pipeline](#data-pipeline)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Overview

This project aims to analyze motor vehicle crash data in New York City using a PySpark-based data pipeline. We processed and analyzed 1.3 million data points to uncover critical patterns through numerical and geospatial exploratory data analysis (EDA). Missing Borough details were imputed using a Logistic Regression method. The findings were synthesized into an interactive Plotly dashboard to illustrate the factors affecting crashes.

## Project Proposal

Please refer to the [Project Proposal](./Project_Proposal.pdf) for a detailed description of the problem statement, objectives, data source, and proposed technologies.

## Features

- **Data Processing:** Utilized PySpark for efficient data processing.
- **Geospatial and Numerical EDA:** Conducted exploratory data analysis to uncover critical patterns.
- **Imputation:** Filled missing Borough details using a Logistic Regression method.
- **Interactive Dashboard:** Synthesized findings into an interactive Plotly dashboard for visualization.

## Data Pipeline

The data pipeline involves the following steps:

1. **Data Ingestion:** Load the raw data from the NYC Open Data portal.
2. **Data Cleaning:** Handle missing values, filter out irrelevant data, and preprocess the dataset.
3. **Feature Engineering:** Create new features relevant to the analysis.
4. **Imputation:** Use Logistic Regression to fill missing Borough details.
5. **Exploratory Data Analysis (EDA):** Perform numerical and geospatial EDA to uncover patterns.
6. **Visualization:** Create an interactive dashboard using Plotly to present the findings.

## Technologies Used

- **Python**
- **PySpark**
- **Plotly**
- **Jupyter Lab**

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/nyc-motor-vehicle-crash-analysis.git
    cd nyc-motor-vehicle-crash-analysis
    ```

2. **Set up a virtual environment:**
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. **Install the dependencies:**
    ```bash
    pip install pyspark plotly jupyterlab
    ```

4. **Launch Jupyter Lab:**
    ```bash
    jupyter lab
    ```

## Usage

1. **Run the data processing notebook:**
    Open and execute the Jupyter Notebook `jupyter-notebook.ipynb` to process the data and generate the EDA results.

2. **Generate visualizations:**
    Use the Plotly dashboard to interact with the visualizations and explore the factors affecting crashes.

## Results

The analysis uncovered several critical insights:

- Time of day and location significantly affect the likelihood of crashes.
- Certain contributing factors, such as distracted driving, are more prevalent in specific boroughs.
- Seasonal variations and holidays also impact crash frequency.

## Contributors

- Yogesh Sharma
- Preeyonuj Boruah
- Prateek Srivastava

## License

This project is licensed under the MIT License.
