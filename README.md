# Integrated Machine Learning Laboratory Dashboard

An interactive, full-stack Machine Learning laboratory dashboard for exploring datasets, running ML experiments, making predictions, visualizing results, comparing models, understanding model behavior, and generating academic lab reports.

## Overview

This project brings Machine Learning practicals into one web-based workspace. It combines pre-trained model demonstrations with interactive training, evaluation, visualizations, Explainable AI, learning resources, and experiment reports.

### Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

## Student Project

| Detail | Information |
|---|---|
| Student | **Prathamesh Balaji Patil** |
| College | D. Y. Patil College of Engineering and Technology, Kolhapur |
| Department | Artificial Intelligence and Machine Learning |
| Class | TY A (AIML) |
| Roll Number | A11 |
| Subject | Machine Learning Laboratory |

## Machine Learning Experiments

| No. | Experiment | Category |
|---:|---|---|
| 01 | Python Libraries and Exploratory Data Analysis | Supporting |
| 02 | Simple Linear Regression | Regression |
| 03 | Multiple Linear Regression | Regression |
| 04 | Logistic Regression (Binary Classification) | Classification |
| 05 | Multiclass Logistic Regression | Classification |
| 06 | Decision Tree Classification | Classification |
| 07 | K-Nearest Neighbors (KNN) | Classification |
| 08 | Naive Bayes Classification | Classification |
| 09 | Random Forest Classification | Classification |
| 10 | Random Forest Regression | Regression |
| 11 | Linear Support Vector Machine | Classification |
| 12 | Nonlinear (RBF) Support Vector Machine | Classification |

## Main Features

### 1. Interactive Model Training
- Train supported classification and regression algorithms.
- Select a dataset, target column, and input features.
- Configure train/test split and supported hyperparameters.
- Apply preprocessing through reusable ML pipelines.
- Upload and preview CSV datasets with validation.

### 2. Interactive Visualizations
- Explore feature distributions and dataset summaries.
- View actual-versus-predicted plots and residual analysis.
- Inspect confusion matrices and supported classification curves.
- Interact with charts using zoom, pan, and hover details.

### 3. Model Comparison
- Train and evaluate multiple compatible algorithms.
- Compare models using task-appropriate evaluation metrics.
- Review results in comparison tables and charts.
- Export available comparison results.

### 4. Explainable AI
- Explore supported global feature-importance methods.
- Inspect local prediction explanations where supported.
- View decision paths for supported tree models.
- Explore nearest-neighbor information for KNN.
- Review model limitations and educational explanations.

### 5. Academic Lab Reports
- Generate experiment reports using available run results.
- Include experiment details, dataset information, configuration, metrics, charts, and conclusions.
- Export reports in supported formats, including PDF, JSON, and CSV.

### 6. Learning Resources
- Review algorithm concepts, workflows, formulas, and use cases.
- Prepare with experiment-related viva questions and answers.
- Explore practical examples and implementation guidance.

### 7. Experiment History
- Review saved experiment runs and their recorded configurations.
- Revisit available results and related artifacts.

## Evaluation Metrics

The dashboard uses metrics appropriate to the selected task and available model outputs.

**Regression**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

**Classification**
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC and Precision-Recall metrics where supported

Metric availability depends on the experiment, dataset, and model outputs.

## Repository Structure

```text
Machine-Learning-Lab/
├── app.py
├── requirements.txt
├── test_suite.py
├── README.md
├── datasets/
├── models/
├── services/
│   ├── model_service.py
│   ├── training_service.py
│   ├── evaluation_service.py
│   ├── visualization_service.py
│   ├── explainability_service.py
│   ├── learning_service.py
│   ├── report_service.py
│   ├── dataset_service.py
│   ├── comparison_service.py
│   └── history_service.py
├── static/
│   ├── css/
│   └── images/
└── templates/
```

*The structure above is a high-level overview. Exact files and folders may vary as the project evolves.*

## Getting Started

### Requirements
- Python 3.10 or a compatible version supported by the project's dependencies
- pip

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Locally

```bash
python app.py
```

Open the local address shown in the terminal (the default Flask address is commonly `http://127.0.0.1:5000`).

## Testing

The repository includes `test_suite.py` for automated application checks.

Run the test suite with:

```bash
python test_suite.py
```

Check the test output in your environment for the actual pass/fail results.

## Useful Links

- **GitHub Repository:** [Machine Learning Experiments](https://github.com/Shree0802/Machine-Learning_Experiments)
- **LinkedIn:** [Prathamesh Patil](https://www.linkedin.com/in/prathamesh-patil1718)

All project-related Machine Learning practical materials, datasets, and source code available in this repository are shared for learning and academic reference.

## License

This project is distributed under the MIT License. See the [`LICENSE`](LICENSE) file if included in the repository.

---

<div align="center">

**Developed by Prathamesh Balaji Patil**

TY A (AIML) · Roll No: A11 · DYPCET, Kolhapur

</div>
