# Airbnb Data Analysis

This project analyzes a dataset from Airbnb. It includes a structured Python package and Jupyter Notebooks to perform various data analysis tasks including data summary, exploratory data analysis (EDA), and inference.

## Project Structure

The project is organized as follows:

- `airbnb_analysis/`: This directory contains the Python package for this project.
    - `__init__.py`: Initializes the Python package.
    - `data_summary/`: Contains modules for summarizing data.
        - `__init__.py`: Initializes the `data_summary` sub-package.
        - `summary.py`: Contains the `DataSummary` class for summarizing data.
    - `exploratory_data_analysis/`: Contains modules for exploratory data analysis.
        - `__init__.py`: Initializes the `exploratory_data_analysis` sub-package.
        - `analysis.py`: Contains the `ExploratoryDataAnalysis` class for performing EDA.
    - `inference/`: Contains modules for performing inference.
        - `__init__.py`: Initializes the `inference` sub-package.
        - `inference.py`: Contains the `Inference` class for performing inference.
    - `tests/`: Contains test modules.
        - `__init__.py`: Initializes the `tests` sub-package.
        - `test_functions.py`: Contains test functions.

- `data/`: This directory contains the dataset used for this project.
    - `listings.csv`: The Airbnb listings data.

- `notebooks/`: This directory contains Jupyter Notebooks.
    - `mapalol_project1.ipynb`: Contains a step-by-step analysis using the `airbnb_analysis` package.

- `README.md`: This file, which provides an overview of the project and instructions for running the code.

## Getting Started

1. Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/your-repository.git
