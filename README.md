# 📊 Azure Machine Learning Designer - Sales Quantity Prediction

![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?logo=microsoftazure&logoColor=white)
![Azure ML](https://img.shields.io/badge/Azure-Machine%20Learning-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Linear Regression](https://img.shields.io/badge/Algorithm-Linear%20Regression-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📖 Project Overview

This project demonstrates an end-to-end **Machine Learning regression pipeline** developed using **Microsoft Azure Machine Learning Designer**.

The objective was to predict the **Quantity Ordered (`QUANTITYORDERED`)** using historical sales data through Azure's low-code drag-and-drop machine learning environment.

The project covers the complete ML workflow, including:

- Data exploration
- Feature selection
- Data splitting
- Model training
- Model scoring
- Performance evaluation

---

# 🎯 Objective

Build a regression model capable of predicting the **Quantity Ordered** based on historical sales information.

**Target Variable**

```
QUANTITYORDERED
```

---

# 📂 Dataset

The dataset contains sales transactions with customer, product, and order information.

### Dataset Summary

| Property | Value |
|----------|--------|
| Records | 2,823 |
| Features | 25 |
| Problem Type | Regression |
| Target Variable | QUANTITYORDERED |

### Example Features

- ORDERNUMBER
- PRICEEACH
- SALES
- ORDERDATE
- PRODUCTLINE
- CUSTOMERNAME
- COUNTRY
- DEALSIZE
- STATUS
- PRODUCTCODE

---

# 🏗 Azure ML Designer Pipeline

The machine learning workflow was created using Azure Machine Learning Designer.

## Pipeline Components

| Step | Component | Purpose |
|------|-----------|---------|
| 1 | Summarize Data | Explore dataset statistics and feature distribution |
| 2 | Select Columns in Dataset | Select relevant features for training |
| 3 | Split Data | Divide data into training and testing sets |
| 4 | Linear Regression | Select regression algorithm |
| 5 | Train Model | Train the Linear Regression model |
| 6 | Score Model | Generate predictions on test data |
| 7 | Evaluate Model | Calculate performance metrics |

---

# 🖼 Pipeline Architecture

> Replace the image below with your uploaded pipeline screenshot.

```markdown
![Azure ML Pipeline](Auto%20ML%20Designer%20Pipeline.png)
```

---

# 📈 Model Performance

The trained model achieved the following evaluation metrics:

| Metric | Value |
|---------|--------|
| **Coefficient of Determination (R²)** | **0.6505** |
| **Mean Absolute Error (MAE)** | **4.3808** |
| **Root Mean Squared Error (RMSE)** | **5.6550** |
| **Relative Absolute Error (RAE)** | **0.5406** |
| **Relative Squared Error (RSE)** | **0.3495** |

---

# 📊 Interpretation of Results

### R² Score (0.6505)

The model explains approximately **65% of the variation** in the Quantity Ordered, indicating a solid baseline regression model.

### Mean Absolute Error (MAE)

On average, predictions differ from the actual values by approximately **4.38 units**.

### Root Mean Squared Error (RMSE)

RMSE of **5.66** indicates the average prediction error while assigning greater weight to larger prediction errors.

### Relative Errors

Both Relative Absolute Error and Relative Squared Error demonstrate that the model performs significantly better than a simple baseline predictor.

---

# 💻 Technologies Used

- Microsoft Azure
- Azure Machine Learning Designer
- Linear Regression
- Machine Learning
- Regression Analysis
- Data Analytics

---

# 📁 Repository Structure

```
Azure-ML-Designer-Sales-Prediction
│
├── Dataset
│   └── sales_data_sample.csv
│
├── Images
│   ├── pipeline.png
│   └── evaluation_metrics.png
│
├── Report
│   └── Azure_ML_Designer_Project_Report.pdf
│
├── README.md
└── LICENSE
```

---

# 📷 Project Screenshots

## Azure ML Designer Pipeline

```markdown
![Pipeline](Images/pipeline.png)
```

## Model Evaluation

```markdown
![Evaluation Metrics](Images/evaluation_metrics.png)
```

---

# 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

- Azure Machine Learning Designer
- Cloud-based Machine Learning
- Regression Modeling
- Data Preparation
- Feature Selection
- Model Training
- Model Evaluation
- Machine Learning Workflow Design

---

# 🚀 Future Improvements

Potential enhancements include:

- Feature engineering
- Hyperparameter tuning
- Comparing multiple regression algorithms
- Cross-validation
- Automated Machine Learning (AutoML)
- Model deployment as a REST API
- Real-time inference using Azure ML Endpoints

---

# 📄 Project Report

A detailed project report is available in the **Report** folder.

```
Report/Azure_ML_Designer_Project_Report.pdf
```

---

# 👨‍💻 Author

**Osama Ghafoor**

Master's in Computer Science

Diploma in Artificial Intelligence Operations (AIOps)

Passionate about Artificial Intelligence, Machine Learning, Cloud Computing, and Automation.

---

# ⭐ If you found this project useful

Please consider giving this repository a **Star ⭐**.

It motivates me to continue building and sharing practical AI and Cloud projects.
