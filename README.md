
---

# 🚢 Titanic Data Analysis & Logistic Regression

Welcome to the Titanic Data Analysis and Logistic Regression project. This project dives into the famous Titanic dataset to perform data analysis, visualization, and logistic regression for predicting the survival of passengers. The analysis is implemented in the Jupyter Notebook `titanic_regression.ipynb`.

---

## 📜 Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Dependencies and Setup](#dependencies-and-setup)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

---

## 🌟 Project Overview

This project analyzes the Titanic dataset to understand the factors that contributed to passenger survival. The main goals are:

- Perform **Data Cleaning** to handle missing values and duplicates.
- Carry out **Exploratory Data Analysis (EDA)** to visualize important trends and patterns.
- Apply **Logistic Regression** to predict the likelihood of a passenger's survival based on different features.

Key techniques used in this project:
- **Pandas**, **NumPy** for data manipulation.
- **Matplotlib**, **Seaborn** for data visualization.
- **Scikit-learn** for machine learning and logistic regression.

---

## 📊 Dataset

The dataset used for this project is the famous Titanic dataset, which contains information about passengers aboard the Titanic. The key features in the dataset include:

- **PassengerId**: Unique ID for each passenger
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- **Survived**: Survival (0 = No, 1 = Yes)

You can find the dataset [here](https://www.kaggle.com/c/titanic/data) or use the one provided in the repository.

---

## 🛠️ Project Workflow

### 1. Import Libraries and Set Environment
The project starts by importing the necessary libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.

### 2. Load the Data
The dataset is loaded and initial exploration is performed using `pandas` to understand its structure.

### 3. Initial Data Inspection
We inspect the data using functions like `head()`, `info()`, and `describe()` to gather insights into the dataset.

### 4. Data Cleaning
- **Handling Null Values:** Missing values are handled using techniques such as imputation.
- **Handling Duplicates:** Any duplicate entries in the dataset are identified and removed.

### 5. Exploratory Data Analysis (EDA) & Visualization
This section includes data visualizations to understand the distribution of key features, relationships between variables, and survival trends. Various plots include:
- Distribution of ages, fares, and other numerical features.
- Survival rates by class, gender, age, etc.

### 6. Analyzing Relationships
We explore the relationships between variables such as gender and survival, class and survival, etc., using visualizations and correlation matrices.

### 7. Statistical Analysis
We use statistical methods to check the significance of variables in relation to survival.

### 8. Regression Analysis
Here, we apply **Logistic Regression** to predict the survival outcome based on selected features. We split the data into training and testing sets, train the logistic regression model, and evaluate its performance.

### 9. Save and Store Work
The model and results are saved for future use.

### 10. Logistic Regression
The logistic regression model is fine-tuned, and predictions are made. We evaluate the model’s accuracy using metrics such as **accuracy score**, **confusion matrix**, and **ROC-AUC curve**.

---

## 💻 Dependencies and Setup

To run this project, make sure you have Python 3.8+ and the required libraries installed.

### 1. Clone the repository
```bash
git clone https://github.com/your_username/titanic-regression.git
cd titanic-regression
```

### 2. Create and activate a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate  # For Windows use `venv\Scripts\activate`
```

### 3. Install the dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook
```bash
jupyter notebook titanic_regression.ipynb
```

---

## 🎯 Results

The key results from the logistic regression analysis show that factors such as **gender**, **passenger class**, and **age** significantly impacted survival rates. The final model achieved a performance score of:

- **Accuracy:** XX.X%
- **Precision:** XX.X%
- **Recall:** XX.X%
- **AUC Score:** XX.X%

The model was evaluated using a **confusion matrix**, **ROC curve**, and other metrics.

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve this project or add new features:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit (`git commit -m 'Added new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

- **Author:** [Your Name]
- **GitHub:** [Your GitHub](https://github.com/your_username)
- **LinkedIn:** [Your LinkedIn](https://linkedin.com/in/yourusername)
- **Email:** your.email@example.com

---

