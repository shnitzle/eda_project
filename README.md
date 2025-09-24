[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)
# EDA project for neuefische data science bootcamp

This repository contains files for the EDA project of the neuefische "Data Science" bootcamp performed by __Maryam J. Rutner__ and __Tim Dannenfeld__. The data was retrieved from PostgreSQL as described in [Fetching_the_data_eda.ipynb](./Fetching_the_data_eda.ipynb). The data contains information about house sales and details in King County, WA, USA from May 2014 to May 2015.

# Files

- data cleaning process: [data_cleaning.ipynb](./tim_folder/data_cleaning.ipynb)
- resulting csv-file: [eda_clean.csv](./tim_folder/eda_clean.csv)
- hypotheses for project including python code used for testing: [hypotheses_tests.ipynb](./tim_folder/hypotheses_tests.ipynb)
- creation of plots: [visualization.ipynb](./tim_folder/visualization.ipynb)
- power point presentation of results: [Presentation_Properties_Erin_Robinson.pdf](./Presentation_Properties_Erin_Robinson.pdf).

# The task

- define three hypotheses that can be tested with the data
- test hypotheses using python libraries
- develop useful recommendations for an imaginary client based on tested hypotheses
- present results with a power point presentation to coaches and other students

#

__Imaginary Client: Erin Robinson__

__Role__: Buyer

__Characteristics:__
- Investor in poor neighborhoods
- Goal: buy, resell, cover costs + small profit
- Wants to be socially responsible

# Requirements

- pyenv
- python==3.11.3
- pandas==2.3.2
- folium==0.20.0
- matplotlib==3.10.6
- seaborn==0.13.2

# Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```


### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
 
