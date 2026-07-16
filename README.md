# Penguin Species Classification using Machine Learning

A machine learning project that predicts the species of a penguin based on its physical characteristics using the **Palmer Penguins Dataset**. This project demonstrates the complete ML workflow—from data preprocessing to model training and evaluation.

---

## Project Overview

The goal of this project is to classify penguins into one of three species:

* Adelie
* Chinstrap
* Gentoo

The model learns patterns from features such as bill dimensions, flipper length, body mass, island, sex, and year to accurately identify the penguin species.

---

## Features

* Data loading using the Palmer Penguins dataset
* Missing value handling
* Data cleaning and preprocessing
* Feature encoding
* Train-test split
* Random Forest Classification
* Decision Tree Classification
* Model evaluation using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

---

## Dataset

**Dataset:** Palmer Penguins

The dataset contains biological measurements collected from penguins living in Antarctica.

### Features

| Feature             | Description                           |
| ------------------- | ------------------------------------- |
| Island              | Island where the penguin was observed |
| Bill Length (mm)    | Length of the penguin's bill          |
| Bill Depth (mm)     | Depth of the penguin's bill           |
| Flipper Length (mm) | Length of the flipper                 |
| Body Mass (g)       | Penguin body weight                   |
| Sex                 | Male/Female                           |
| Year                | Year of observation                   |

### Target

* **Species**

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Palmer Penguins Dataset

---

## Machine Learning Workflow

Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Handle Missing Values
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Encoding
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
(Random Forest & Decision Tree)
      │
      ▼
Model Evaluation
(Accuracy, Confusion Matrix, Classification Report)
      │
      ▼
Species Prediction


---

## Models Used

### Random Forest Classifier

* Ensemble learning algorithm
* High accuracy
* Reduces overfitting
* Better generalization

### Decision Tree Classifier

* Easy to understand
* Useful for comparison
* Fast training

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

---

## Project Structure

```text
Penguin-Species-Classification/
│
├── Penguin_Classification.ipynb
├── README.md
├── requirements.txt
└── images/
    └── (optional screenshots)
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Penguin-Species-Classification.git
```

### 2. Navigate to the project

```bash
cd Penguin-Species-Classification
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open the Jupyter Notebook and execute all cells.

---

## Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Handling missing values
* Feature engineering
* Encoding categorical variables
* Training classification models
* Evaluating model performance
* Comparing machine learning algorithms

---


## Support

If you found this project useful, consider giving this repository a **Star** ⭐ on GitHub.
