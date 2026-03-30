# r-to-python-ml-workflow
 Responsible Machine Learning (assignment 1) 
## Purpose of the Analysis
The purpose of this project is to reproduce a machine learning workflow originally developed in R using Python. The goal is to understand how a predictive model is built, evaluated, and interpreted in a different programming environment.

In this analysis, I focus on predicting recidivism using a logistic regression model. In addition to replicating the original workflow, I also examine how model predictions translate into real-world decisions. This includes converting predicted probabilities into binary classifications and evaluating the model's performance using metrics such as accuracy, precision, and recall.

I compute error rates such as False Positive Rate (FPR) and False Negative Rate (FNR) across different racial groups to investigate whether the model produces unequal outcomes. By comparing these metrics across groups, the analysis highlights potential disparities in how predictions affect different populations.

Overall, this project aims to bridge technical implementation and practical implications by not only reproducing the model but also interpreting its impact.

---

## Python Libraries Used
Several Python libraries were used to complete this analysis:

- **pandas**: for data manipulation, cleaning, and grouping operations  
- **numpy**: for numerical computations and mathematical functions  
- **scikit-learn**: for building and evaluating the logistic regression model  
- **statsmodels**: for statistical modeling and interpreting model coefficients  
- **matplotlib / seaborn** : for data visualization during EDA  

These libraries together provide the necessary tools to replicate the original R workflow in Python while maintaining similar functionality and results.

---

## Instructions for Reproducing the Results
To reproduce the results of this analysis, follow these steps:

1. Download the Jupyter Notebook file provided by the instructor.  
2. Open the notebook using Google Colab. 
3. Make sure all required Python libraries are installed. If not, install them using pip or conda.  
4. Run all cells in the notebook sequentially from top to bottom.  
5. The outputs will include data preprocessing steps, exploratory analysis, model training, predictions, and evaluation metrics.  

The notebook is structured to follow the full workflow, so running all cells will reproduce the complete analysis without requiring additional modifications.


This assignment was completed with the assistance of generative AI tools (e.g., ChatGPT) as a learning aid.

Specifically, AI was used to:
- Help translate R code into equivalent Python implementations
- Assist with debugging and improving code structure
- Clarify concepts related to machine learning workflows and model diagnostics
