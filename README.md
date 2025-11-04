# Booking Data Analysis

## Project Overview

This repository contains an Exploratory Data Analysis (EDA) of booking and contact data, likely from a hospitality platform. The goal of this project is to clean, analyze, and visualize the dataset to uncover key trends and insights into user and host behavior, focusing primarily on the rate of accepted bookings.
 
The analysis is performed within a Jupyter Notebook using Python and popular data science libraries.

## Key Analysis and Findings

The analysis in `Project 01.ipynb` covers several key areas:

* **Data Cleaning and Transformation:** Initial steps to prepare the raw data for analysis.
* **Feature Engineering:** Creating new metrics, such as the `acceptance_rate`.
* **Geographic Analysis:** Calculating and visualizing booking/contact acceptance rates broken down by the `origin_country`.
* **Metric Deep Dive:** Analyzing the factors that contribute to high or low acceptance rates across different groups.
* **Data Visualization:** Using `Matplotlib` and `Seaborn` (inferred) to illustrate findings, such as acceptance rate distribution.

One specific metric calculated is the **acceptance rate by country**, which helps identify geographic patterns in host acceptance behavior.

## Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `Project 01.ipynb` | The main Jupyter Notebook containing all the data cleaning, exploration, and analysis code. |
| `README.md` | The file you are currently reading. |

## Technologies and Libraries

The project is built entirely in Python and uses the following core libraries:

* **Python 3.x**
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib:** For creating static, interactive, and animated visualizations.
* **Jupyter Notebook:** The environment used for the analysis.

## Setup and Installation

To replicate this analysis on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/AsutoshaNanda/booking-data-analysis.git](https://github.com/AsutoshaNanda/booking-data-analysis.git)
    cd booking-data-analysis
    ```

2.  **Create a Virtual Environment** (Recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: .\venv\Scripts\activate
    ```

3.  **Install Dependencies:**
    You will need to install the required libraries. If you create a `requirements.txt` file, you would run:
    ```bash
    pip install -r requirements.txt
    # If you don't have a requirements.txt, manually install:
    pip install pandas numpy matplotlib
    ```

4.  **Obtain Data:**
    Place your raw data file(s) into a `data/` folder, or modify the notebook to load your data from its current location.

5.  **Run the Notebook:**
    ```bash
    jupyter notebook
    ```
    This will open the Jupyter interface in your browser. Click on `Project 01.ipynb` to view and run the analysis.

## Contact

* **GitHub:** [@AsutoshaNanda](https://github.com/AsutoshaNanda)
