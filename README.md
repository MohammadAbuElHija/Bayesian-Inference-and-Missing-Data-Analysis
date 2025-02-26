# Bayesian Inference and Missing Data Analysis

## Project Overview
This project explores **Bayesian inference** and **handling missing data** using statistical methodologies. The objectives are to apply Bayesian estimation techniques, compare different prior distributions, and evaluate methods for dealing with missing data in regression models.

## Dataset
- **Source:** The dataset used in this project is from Kaggle: [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).
- **Sample Size:** A subset of **200 observations** is randomly selected for analysis.

## Project Structure
The project consists of two main sections:

### 1. Bayesian Inference (Part A)
- **Objective:** Estimate parameters using Bayesian methods and compare different prior choices.
- **Steps:**
  1. Define a **binary variable (Z)** based on a threshold value of a continuous variable (X).
  2. Estimate the **log-odds ratio (ψ)** using different methods:
     - **Bootstrap confidence intervals**.
     - **Uniform prior Bayesian estimation**.
     - **Jeffreys prior Bayesian estimation**.
     - **Empirical prior estimation** using past data.
  3. Compare the resulting estimates and discuss findings.

### 2. Handling Missing Data (Part B)
- **Objective:** Evaluate methods for dealing with missing values in regression models.
- **Steps:**
  1. **Introduce missingness** in a continuous dependent variable (Y) using a structured missing data pattern.
  2. Apply various **imputation techniques**:
     - **Complete case analysis** (ignoring missing data rows).
     - **Mean imputation** (filling missing values with the mean).
     - **Likelihood-based estimation** (estimating missing values based on distributional assumptions).
  3. Compare the regression estimates obtained using each approach.
  4. Discuss the effects of different imputation techniques on statistical inference.

## Methodology
- **Bayesian Inference:** Compare posterior distributions and different prior choices.
- **Bootstrap Confidence Intervals:** Estimate uncertainty in parameter estimates.
- **Handling Missing Data:** Compare traditional and modern imputation techniques.

## Requirements
To run this project, install the required Python libraries:
```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels
```

## How to Run
1. **Download the dataset** from Kaggle and place it in the project directory.
2. **Run the Jupyter Notebook (`project_analysis.ipynb`)** or execute the Python scripts.
3. **Review the outputs**, including Bayesian estimates, missing data analysis results, and regression comparisons.

## Results & Insights
- Bayesian estimation techniques provided insights into **parameter uncertainty**.
- Different prior choices significantly influenced Bayesian estimates.
- The impact of missing data imputation techniques was analyzed and compared.
- The project highlights **best practices for handling missing data** in statistical modeling.

## Acknowledgments
- **Course Assignment:** Inspired by statistical methods covered in coursework.
- **Data Source:** [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).



