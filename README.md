# Supreme-Court-Decision-Making-CART-Model-
# Predicting Supreme Court Outcomes: CART Analysis of Judge Stevens' Rulings

This repository contains an analysis of Judge Stevens' Supreme Court rulings, focusing on predicting case reversals using Classification and Regression Tree (CART) analysis. The analysis leverages historical case data to understand the factors influencing judicial decision-making.

## Project Description

Our study explores the patterns behind Judge Stevens' rulings, particularly focusing on the factors leading to case reversals. By utilizing a CART model in Python, we analyze case data—examining the roles of various parties, issues, and lower court decisions. This approach allows us to predict outcomes based on historical data and provides insights into the dynamics of judicial decision-making.

## Dataset

The dataset `stevens.csv` contains the following columns:

* **Docket:** The docket number of the case.
* **Term:** The term of the court.
* **Circuit:** The circuit court that heard the case.
* **Issue:** The issue category of the case.
* **Petitioner:** The type of petitioner in the case.
* **Respondent:** The type of respondent in the case.
* **LowerCourt:** The political leaning of the lower court's decision (liberal or conservative).
* **Unconst:** A binary indicator of whether the case involves a constitutional issue (0 = No, 1 = Yes).
* **Reverse:** A binary indicator of whether the Supreme Court reversed the lower court's decision (0 = No, 1 = Yes).

## Technologies Used

* **Python:** Programming language for data analysis and model building.
* **Pandas:** For data manipulation and analysis.
* **Scikit-learn:** For building and evaluating the CART model.
* **Matplotlib and Seaborn:** For data visualization.

## Setup and Installation

1.  **Clone this repository:**

    ```bash
    git clone [repository URL]
    cd [repository directory]
    ```

2.  **Install dependencies:**

    ```bash
    pip install pandas scikit-learn matplotlib seaborn
    ```

3.  **Run the analysis:**

    * Open and run the provided Jupyter Notebook (`[Notebook Name].ipynb`) to reproduce the analysis.

## Analysis Overview

The analysis includes the following steps:

1.  **Exploratory Data Analysis (EDA):**
    * Distribution of categorical and numerical variables.
    * Relationships between variables, such as the impact of the circuit or issue category on reversal decisions.
    * Visualizations using bar charts, histograms, and count plots.
2.  **CART Model Building:**
    * Data preprocessing, including encoding categorical variables and splitting the dataset into training and testing sets.
    * Building a Decision Tree Classifier to predict case reversals.
    * Visualizing the CART diagram to understand the decision-making process.
3.  **CART Diagnostics:**
    * Examining feature importance to identify the most influential variables in predicting reversals.
    * Walkthrough of the CART diagram.

## Key Findings

* The docket number, circuit, issue category, and lower court's political leaning are the most influential factors in predicting case reversals.
* The CART diagram provides a visual representation of the decision-making process, highlighting the conditions under which cases are more likely to be reversed.

## Notebook Structure

* `stevens.csv`: The dataset used for the analysis.
* `[Notebook Name].ipynb`: The Jupyter Notebook containing the analysis code.
* `README.md`: This file.

## Contributing

Contributions are welcome! Please feel free to submit pull requests.
