# Raffaele Simbari
---

# **Machine Learning Projects**

## - **Pilot Machine Learning Project**
[link to code](file:///Users/raffaelesimbari/Desktop/M.L./Individual%20project/mldata_0003185670/ML_Individual_Project.html)

### Introduction
This project explores the use of Principal Component Analysis (PCA) for dimensionality reduction in combination with Logistic Regression to classify a dataset containing 1400 samples and 20 features. 

### Project Overflow
The project is divided into several key steps:

1. *Data Analysis*
   - Load and Explore Data: Import the dataset, check for missing values, and explore the distribution of features and labels.
   - Data Preprocessing: Handle any missing values, standardize the features to ensure they're on the same scale, and split the data into training and testing sets.
     
2. *PCA (Principal Component Analysis)*
   - Apply PCA: Perform PCA to reduce the dimensionality of the dataset.
   - Explained Variance: Visualize the cumulative explained variance to determine how many components are needed to retain most of the information.

3. *Logistic Regression*
   - Train Model: Train a Logistic Regression model using both the original and PCA-transformed data.
   - Hyperparameter Tuning: Optimize the model’s hyperparameters.

4. *Random Forest (extra)*
   - Feature Selection: use of Random Forest as an additional classifier to perform feature selection. By evaluating feature importance, identify the most relevant features for classification.
   - Perform Logistic Regression: use of the key features based on the Random Forest model to train a Logistic Regression classifier and evaluate its performance.

### Final Objective
The final objective of this project is to evaluate whether applying Principal Component Analysis (PCA) improves the performance of a Logistic Regression classifier. Using a Pipeline to streamline the process, the goal is to identify the optimal number of PCA components and fine-tune the classifier’s hyperparameters to achieve the best classification results.
At the end of the analysis we can compare the results and performances of Logistic Regression obtained by the three different strategies:

- Logistic Regression on the raw dataset 
- Logistic Regression using data obtained by the PCA 
- Logistic Regression using data obtained by features selection of Random Forest
   
## - **AI Lab** 
[link to code](file:///Users/raffaelesimbari/Desktop/AI%20LAB/AILAB/AI_LAB/main_AILab.html)

### Introduction
This project applies various machine learning (ML) techniques to classify the hypoxic or normoxic state of cells using single-cell RNA sequencing (scRNA-Seq) data. The dataset includes two cancer cell lines: HCC1806 and MCF7, each sequenced with two distinct technologies: SmartSeq and DropSeq. These sequencing methods provide high-resolution insights into gene expression at the single-cell level, enabling us to understand how cells respond to hypoxic conditions.

### Project Workflow
The project is divided into several key steps:

1. *Exploratory Data Analysis (EDA)*
   - We begin by examining the dataset to uncover patterns, distributions, and potential sources of variability, which helps inform the subsequent steps of analysis.

2. *Unsupervised Learning*
   - Unsupervised learning techniques are used to identify natural groupings or clusters in the data without relying on predefined labels. This phase helps to reveal hidden structures in the dataset.

3. *Supervised Learning*
   - Supervised learning models are trained to classify cells into hypoxic or normoxic states based on labeled data. Multiple classification techniques are assessed to determine the most effective model for this task.

4. *Model Selection*
   - We compare the performance of various classifiers to identify the best model for distinguishing between hypoxic and normoxic cells.

### Final Objective
In the final phase, the goal is to develop a more generalizable classifier that can effectively classify cells across multiple cell lines and/or sequencing techniques. This aspect of the project is part of ongoing research, as creating a robust multi-cell-line or multi-sequencing classifier remains a challenging but valuable task in the field.

---

# **Statistic Projects**

## - **Life Expectancy Analysis** 
[link to report](file:///Users/raffaelesimbari/Desktop/Analyzing_Life_Expectancy.pdf)

### Introduction
This project explores global life expectancy trends using statistical analysis in R. The goal is to analyze how various factors (e.g., GDP, education, healthcare) influence life expectancy across countries.

### Project Workflow
The project is divided into several key steps:

1. *Data Exploration*
   - Import and explore the dataset using visualizations (e.g., scatter plots, histograms) to understand trends and correlations.

2. *Regression Analysis*
   - Apply multivariate regression to identify factors predicting life expectancy, check normality and analysis of the residuals

3. *Model Selection*
   - Run model selection algorithms to try and obtain a better model (Step-up, Step-Down, Step-Both).

4. *Hypothesis Testing*
   - Perform a statistical test (e.g., t-test, ANOVA) to check for significant differences, such as life expectancy between different regions.

### Final Objective
The primary objective of this project is to identify key drivers of life expectancy and understand how they vary across countries. By applying regression and statistical tests, the project aims to provide insights into the global health landscape.

---

# **Numerical Methods Projects** 

## - **Revisiting Lotka-Volterra: Expanding Predator-Prey Dynamics to Multi-Species Systems** 
[link to code](file:///Users/raffaelesimbari/Desktop/Numerical%20methods/Project/Project.html)

### Introduction
This project extends the classic Lotka-Volterra model to simulate predator-prey interactions in multi-species environments. Starting with a two-species system (predator and prey), we then introduce a third species to interact with both. This approach provides insights into ecological stability and species coexistence in more complex ecosystems.

### Project Workflow
1. *Initial Two-Species Model*
   - Study the classic Lotka-Volterra predator-prey model with two species, solving the system using the Euler and Runge-Kutta 4th order methods. Plot and compare prey and predator populations over time to observe oscillations and assess method accuracy.
   - 
2. *Introduction of a Third Species*
   - Introduce a third species into the system, updating the equations to account for interactions with both the prey and predator. Solve the extended system using the same numerical methods and analyze how the third species affects population dynamics, stability, and predator-prey oscillations. Plot the populations over time and observe potential impacts on system stability.

### FInal Objective
The primary objective of this project is to extend the classic Lotka-Volterra predator-prey model by introducing a third species and analyzing the resulting interactions within the ecosystem.










  
  
