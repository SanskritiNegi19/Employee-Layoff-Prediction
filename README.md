# Employee Layoff Prediction & Retention Analysis

## Overview

Employee Layoff Prediction & Retention Analysis is a machine-learning project that analyzes employee-related attributes to predict potential layoffs, categorize employee risk levels, and generate retention recommendations.

The project combines supervised learning, unsupervised learning, data visualization, and search algorithms for an academic exploration of workforce analytics.

## Features

- **Layoff prediction:** Predicts whether an employee is likely to be laid off.
- **Model comparison:** Compares Decision Tree, Logistic Regression, Random Forest, Support Vector Machine (SVM), and Artificial Neural Network (ANN).
- **Model evaluation:** Uses accuracy, precision, recall, F1-score, confusion matrix, and 5-fold cross-validation.
- **Risk categorization:** Groups employees into Low, Medium, and High layoff-risk categories.
- **Feature importance:** Examines features that influence model predictions.
- **Employee clustering:** Uses K-Means to group employees with similar characteristics.
- **Retention recommendations:** Generates rule-based employee retention suggestions.
- **BFS reassignment search:** Explores employee reassignment paths between roles.
- **A* reassignment search:** Searches for cost-efficient reassignment paths.
- **Risk-score estimation:** Uses Linear Regression to estimate a continuous risk score.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms

| Algorithm | Purpose |
|---|---|
| Decision Tree | Layoff classification |
| Logistic Regression | Binary classification |
| Random Forest | Classification and feature importance |
| Support Vector Machine (SVM) | Classification |
| Artificial Neural Network (MLPClassifier) | Neural-network classification |
| Linear Regression | Continuous risk-score estimation |
| K-Means | Employee clustering |

## Dataset

The notebook expects a CSV file named `employee_layoff_3000.csv` in the project directory.

The dataset is described as containing 3,000 employee records, with features such as department, salary, performance score, experience, company financial health, years at company, and skill rating.

**Target variable:** `LaidOff`

- `0`: Not laid off
- `1`: Laid off

Only include the dataset in a public repository if you have permission to share it and it contains no private or personally identifiable employee information.

## Project Workflow

1. Load and inspect the dataset.
2. Preprocess and encode categorical features.
3. Scale numerical features where required.
4. Split data into training and testing sets.
5. Train and compare machine-learning models.
6. Evaluate model performance.
7. Perform cross-validation.
8. Examine feature importance.
9. Categorize employee risk.
10. Apply K-Means clustering.
11. Explore reassignment using BFS and A* search.
12. Generate predictions and retention recommendations.

## Installation and Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Employee-Layoff-Prediction.git
   cd Employee-Layoff-Prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `AIMLFinalLabProject.ipynb` and run the cells in order.

Make sure `employee_layoff_3000.csv` is in the same directory as the notebook.

## Future Improvements

- Build an interactive web interface.
- Improve model generalization and evaluation.
- Add more relevant employee-related features.
- Create an employee analytics dashboard.
- Explore additional classification and clustering methods.

## Disclaimer

This project is intended for educational and academic purposes. Model predictions should not be used as the sole basis for real-world employment, promotion, or layoff decisions.

## Author

**Sanskriti Negi**  
B.Tech, Computer Science and Engineering

GitHub: https://github.com/YOUR-USERNAME
