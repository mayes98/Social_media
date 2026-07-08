# Stress Level Prediction and Explainability of Social Media Use in Teenagers

## Project Overview

This project focuses on **predicting stress levels among teenagers based on their social media usage patterns** while also providing **explainable machine learning insights** into the factors that contribute to stress prediction. The objective is not only to develop an accurate predictive model but also to improve the interpretability of the model so that the key features influencing stress levels can be understood.

The project follows a complete end-to-end data science workflow, beginning with data preprocessing and exploratory data analysis, followed by feature engineering, machine learning model development, model evaluation, and explainability techniques.

The entire project is **Dockerized**, allowing it to be executed in a consistent and reproducible environment regardless of the host operating system.

---

# Objectives

The primary objectives of this project are:

- Predict stress levels among teenagers using social media usage data.
- Analyze the relationship between different social media behaviors and stress levels.
- Build an end-to-end machine learning pipeline.
- Evaluate the performance of multiple machine learning models.
- Interpret and explain the model's predictions using explainable AI techniques.
- Provide a reproducible environment through Docker.

---

# Project Workflow

The project follows the following workflow:

## 1. Data Collection

- Load the social media dataset.
- Inspect the dataset structure.
- Understand available features and the target variable.

---

## 2. Data Preprocessing and Cleaning

The preprocessing stage prepares the dataset for machine learning by improving its quality.

This stage includes:

- Handling missing values.
- Removing duplicate records.
- Correcting inconsistent data.
- Converting data into appropriate data types.
- Encoding categorical variables.
- Scaling or normalizing numerical features where appropriate.
- Detecting and handling outliers.
- Preparing the final dataset for analysis.

---

## 3. Exploratory Data Analysis (EDA)

The exploratory analysis aims to understand the characteristics of the dataset before model development.

Activities include:

- Generating descriptive statistics.
- Understanding feature distributions.
- Examining the target variable distribution.
- Identifying trends and patterns.
- Performing correlation analysis.
- Exploring relationships between variables.
- Identifying potential predictive features.

---

## 4. Data Visualization

Visualization is used to better understand the dataset and communicate findings.

Typical visualizations include:

- Histograms
- Bar charts
- Scatter plots
- Box plots
- Correlation heatmaps
- Distribution plots
- Pairwise feature relationships

---

## 5. Feature Engineering

During this stage, relevant features are prepared to improve model performance.

This may include:

- Feature selection.
- Feature transformation.
- Feature encoding.
- Creation of additional meaningful variables.
- Removal of redundant or highly correlated features.

---

## 6. Model Development

The processed dataset is used to build machine learning models capable of predicting stress levels.

The workflow includes:

- Preparing training and testing datasets.
- Training one or more machine learning models.
- Hyperparameter tuning.
- Comparing different models.
- Selecting the best-performing model based on evaluation metrics.

*The specific machine learning algorithms will be added and updated as the project progresses.*

---

## 7. Model Evaluation

The developed models are evaluated to determine their predictive performance.

Evaluation includes:

- Performance metric calculation.
- Model comparison.
- Error analysis.
- Validation of prediction quality.
- Selection of the most suitable model.

---

## 8. Model Explainability

After selecting the best-performing model, explainability techniques are applied to understand how the model makes predictions.

This stage focuses on:

- Identifying the most influential features.
- Explaining individual predictions.
- Understanding overall feature importance.
- Improving transparency and interpretability.

---

## 9. Results and Conclusions

The final stage summarizes:

- Model performance.
- Important findings.
- Key factors influencing stress prediction.
- Practical insights obtained from the analysis.

---

# Project Structure

```
social_media/
│
├── data/
│   └── Teen_Mental_Health_Dataset.csv
│
├── notebooks/
│
├── src/
│
├── Dockerfile
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- JupyterLab
- Docker

---

# Docker

This project is fully **Dockerized**, providing a portable and reproducible environment for development and analysis.

## Build the Docker image

```bash
docker build -t social_media .
```

## Run the Docker container

```bash
docker run --name social_media_container -p 8888:8888 -v "$(pwd)":/app social_media
```

Once the container starts, open your browser and navigate to:

```
http://localhost:8888/lab
```

---

# Future Improvements

The repository will continue to be updated with:

- Additional feature engineering techniques.
- Multiple machine learning model implementations.
- Hyperparameter optimization.
- Explainable AI methods.
- Model comparison experiments.
- Performance improvements.
- Additional visualizations.
- Documentation updates.

