# K Nearest Neighbors Project

## Project Description

This project implements the K-Nearest Neighbors (KNN) classification algorithm using Python and Scikit-learn. The objective is to classify observations into their respective target classes using the `KNN_Project_Data` dataset.

The project includes data visualization, feature scaling, model training, model evaluation, and selecting the optimal value of K using the Elbow Method.

---

## Dataset

Dataset: `KNN_Project_Data`

Target Variable:

* `TARGET CLASS`

---

## Project Workflow

### Exploratory Data Analysis (EDA)

* Loaded the `KNN_Project_Data` dataset into a Pandas DataFrame.
* Created a Seaborn pairplot with `TARGET CLASS` as the hue.

### Data Preprocessing

* Standardized the features using `StandardScaler`.
* Converted the scaled features into a new DataFrame.

### Train-Test Split

* Split the data into training and testing sets.
* Test Size: 30%

### Machine Learning Model

Algorithm:

* K-Nearest Neighbors (KNN)

Initial Model:

* `n_neighbors = 1`

### Model Evaluation

The model was evaluated using:

* Confusion Matrix
* Classification Report

### Choosing the Best K Value

* Calculated error rates for K values from 1 to 39.
* Plotted `Error Rate vs. K Value`.
* Retrained the model using:

```python
K = 30
```

* Generated a new Confusion Matrix and Classification Report.

---

## Concepts Used

* Exploratory Data Analysis (EDA)
* Pairplot Visualization
* Feature Scaling using StandardScaler
* Train-Test Split
* K-Nearest Neighbors (KNN)
* Confusion Matrix
* Classification Report
* Elbow Method
* Error Rate Analysis

---

## Project Structure

```text
K-Nearest-Neighbors-Project/
│
├── 02-K Nearest Neighbors Project.ipynb
├── KNN_Project_Data
└── README.md
```

---

## Requirements

* Python 3.x
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Author

Meet Tailor — Data Science Learner

GitHub: https://github.com/MeetTailor-Data

---

## License

Created for learning and educational purposes only.
