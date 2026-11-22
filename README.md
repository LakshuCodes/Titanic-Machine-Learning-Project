# 🚢 Titanic Survival Prediction | Machine Learning Project

An end-to-end Machine Learning project that predicts passenger survival on the Titanic using supervised learning algorithms, exploratory data analysis, feature engineering, and model evaluation.



## 📌 Project Overview

The objective of this project is to build machine learning models that predict whether a passenger survived the Titanic disaster based on demographic and travel-related information.

This project explores the complete machine learning workflow, starting from understanding raw data and performing exploratory analysis to preprocessing, model training, evaluation, and optimization.

## 🎯 Objectives

- Understand and explore real-world datasets using Exploratory Data Analysis (EDA).
- Identify patterns, relationships, and important features affecting survival.
- Handle missing values, categorical variables, and data inconsistencies.
- Apply feature engineering and data preprocessing techniques.
- Train and compare multiple supervised machine learning algorithms.
- Evaluate model performance using appropriate classification metrics.

## 🛠️ Technologies & Libraries

| Technology   | Purpose                                    |
| ------------ | ------------------------------------------ |
| Python       | Programming language                       |
| Pandas       | Data manipulation and analysis             |
| NumPy        | Numerical computing                        |
| Matplotlib   | Data visualization                         |
| Seaborn      | Statistical visualization                  |
| Scikit-learn | Machine learning algorithms and evaluation |
| Google Colab | Cloud-based development environment        |

## 📚 Machine Learning Concepts Covered

### 1. Exploratory Data Analysis (EDA)

- Understanding dataset structure and statistical summaries.
- Identifying missing values and duplicate records.
- Univariate and bivariate analysis.
- Visualizing relationships between features and survival.

### 2. Data Preprocessing

- Handling missing values.
- Encoding categorical variables.
- Feature scaling and transformation.
- Preparing data for machine learning models.

### 3. Feature Engineering

- Creating meaningful features from existing variables.
- Selecting relevant predictive features.
- Improving model input representation.

### 4. Supervised Machine Learning

Classification algorithms explored in the project:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 5. Model Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-validation

## 📊 Model Performance

The Logistic Regression model achieved the following recorded results:

| Evaluation Metric                | Result |
| -------------------------------- | -----: |
| Test Accuracy                    | 80.45% |
| 5-Fold Cross-Validation Accuracy | 79.78% |

These results provide a baseline for evaluating and comparing classification models.

## 📂 Dataset

The project uses the Titanic dataset, which contains passenger information such as:

- Passenger class
- Sex
- Age
- Number of siblings and spouses aboard
- Number of parents and children aboard
- Ticket fare
- Port of embarkation

Dataset source: [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

## 🚀 Run the Project

The project is developed using Google Colab.

**Option 1: Google Colab**

1. Open the notebook using the link below.
2. Sign in to your Google account.
3. Upload or connect the required Titanic dataset.
4. Execute the notebook cells sequentially.

**Option 2: Run Locally**

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Titanic-Machine-Learning-Project
```

Install the dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the `.ipynb` file and execute the cells.

## 🔗 Project Links

- **Google Colab Notebook:** [Open Project](https://colab.research.google.com/drive/1MgTqVq1L7j77UPn6JH6WmvVggQEl-zT5?usp=sharing)
- **Dataset:** [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- **GitHub Repository:** Add your repository URL here.

## 🔮 Future Improvements

- Hyperparameter optimization using GridSearchCV and RandomizedSearchCV.
- Further feature selection and engineering.
- Systematic comparison of all trained models.
- Improving predictive performance through model optimization.
- Deploying the final model using Streamlit or Flask.

## 👩‍💻 Author

**Lakshyaa Singh**

Machine Learning | Data Science | Artificial Intelligence

---

*This project is part of my journey towards developing practical Machine Learning and Data Science skills through hands-on implementation and experimentation.*
