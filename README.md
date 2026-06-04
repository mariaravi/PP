# AI Adoption, Productivity and Employee Burnout

### Data Analytics Portfolio Project

## Project Overview

Artificial Intelligence is transforming modern workplaces by changing how employees perform tasks, learn new skills, and interact with technology. While AI can improve productivity and efficiency, concerns remain regarding employee wellbeing, burnout, job satisfaction, and fear of job displacement.

This project investigates the relationship between AI adoption and employee outcomes using two independent datasets:

1. **Global AI Workplace Dataset**
2. **AI Worker Burnout and Attrition Dataset**

The project combines exploratory data analysis (EDA), data cleaning, feature engineering, and predictive modeling to examine how AI-related variables influence productivity, job satisfaction, burnout, and career outcomes.

---

## Project Goals

The main objectives of this project are:

* Explore patterns of AI adoption in the workplace.
* Investigate whether AI usage is associated with productivity gains.
* Analyze the relationship between AI usage and employee wellbeing.
* Examine burnout and attrition risk among AI-supported workers.
* Identify factors associated with employee burnout.
* Build predictive models capable of estimating burnout levels.

---

## Research Questions

### Global AI Workplace Dataset

* Does AI adoption increase productivity?
* Is AI usage associated with burnout?
* Are AI-related promotions linked to salary growth?
* Which employee groups are most concerned about AI replacing jobs?
* How does education influence AI adoption and wellbeing?

### AI Worker Burnout Dataset

* Is fear of AI replacement associated with burnout?
* How are AI assistance hours related to productivity and burnout?
* Is there a productivity–burnout tradeoff?
* Which AI usage profiles provide the best balance between productivity and wellbeing?
* Which variables are most strongly associated with burnout?

---

## Datasets

### Dataset 1: Global AI Workplace Dataset

The dataset contains information about:

* demographic characteristics,
* education level,
* industry and job role,
* AI tools used,
* AI training and skills,
* salary and career development,
* productivity changes,
* burnout and wellbeing indicators,
* attitudes toward AI and regulation.

### Dataset 2: AI Worker Burnout and Attrition Dataset

The dataset contains information about:

* burnout scores,
* attrition risk,
* AI adoption level,
* AI task replacement,
* AI assistance hours,
* productivity scores,
* job satisfaction,
* workplace characteristics,
* demographic information.

---

## Project Structure

```text
.
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   ├── 01_global_ai_dataset_review.ipynb
│   ├── 02_global_ai_data_cleaning.ipynb
│   ├── 03_global_ai_eda.ipynb
│   ├── 04_ai_burnout_dataset_exploration.ipynb
│   ├── 05_ai_burnout_data_cleaning.ipynb
│   ├── 06_ai_burnout_eda.ipynb
│   └── 07_modeling.ipynb
│
├── images
│
├── README.md
├── pyproject.toml
└── uv.lock
```

---

## Tools and Technologies

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

  * Linear Regression
  * Random Forest Regressor
  * Feature Importance Analysis

### Development Environment

* Jupyter Notebook
* Git
* GitHub

---

## Data Preparation

The project included:

* data review and validation,
* data type optimization,
* handling meaningful missing values,
* aggregation of AI usage information,
* creation of master datasets,
* feature engineering,
* preparation of modeling datasets.

For example:

* missing burnout values in the Global AI dataset were interpreted as **"No burnout"** rather than missing observations,
* AI tool usage records were aggregated to respondent level before merging.

---

## Exploratory Data Analysis

The EDA focused on:

* AI adoption patterns,
* productivity outcomes,
* burnout indicators,
* job satisfaction,
* fear of AI replacement,
* career development,
* AI usage profiles,
* relationships between AI intensity and wellbeing.

Several visualizations were created, including:

* correlation heatmaps,
* boxplots,
* regression plots,
* grouped comparisons,
* profile heatmaps,
* productivity–burnout tradeoff analyses.

---

## Modeling

### Target Variable

**Burnout Score**

### Models Evaluated

* Linear Regression
* Random Forest Regressor
* Linear Regression (AI Features Only)
* Linear Regression (Without Job Satisfaction)

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

The objective was not only to maximize prediction performance but also to understand which workplace and AI-related variables contribute most strongly to employee burnout.

---

## Key Findings

### Global AI Workplace Dataset

* AI adoption is widespread across industries and job roles.
* Reported productivity gains exist but are only weakly associated with AI usage frequency.
* AI-related promotions show limited association with salary growth.
* Fear of AI replacement varies across groups but remains relatively moderate.
* Many expected workplace relationships are weaker than anticipated.

### AI Worker Burnout Dataset

* Higher perceived AI task replacement is associated with higher burnout scores.
* Burnout appears closely connected to attrition risk.
* AI usage intensity can be used to identify distinct employee profiles.
* Productivity gains may coexist with increased burnout risk.
* Several AI-related variables contain meaningful predictive information about burnout.

---

## Limitations

Several observations suggest that parts of the data may contain synthetic or partially generated patterns:

* many group averages are very similar,
* correlations are often weak,
* some expected workplace relationships are less pronounced than anticipated.

Therefore, results should be interpreted as patterns within the available datasets rather than evidence of causal real-world effects.

---

## Author

**Mariya Aravina**

Background in Veterinary Medicine and Molecular Biology with experience in reproductive genetics research and laboratory data analysis.

Currently transitioning into Data Analytics with a focus on data-driven decision making, machine learning, and scientific data interpretation.
