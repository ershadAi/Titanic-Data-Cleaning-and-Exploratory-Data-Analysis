# 🚢 Titanic Data Cleaning and Exploratory Data Analysis

## 📖 Overview

This project performs **data cleaning**, **exploratory data analysis (EDA)**, and **data visualization** on the famous Titanic dataset using **Python**, **Pandas**, and **Matplotlib**.

The goal is to prepare the dataset for analysis, explore survival patterns, and visualize important insights such as passenger class, gender distribution, age distribution, fare distribution, and survival rates.

---

## ✨ Features

* Load the Titanic dataset from a CSV file
* Inspect dataset structure and missing values
* Handle missing values:

  * Fill missing ages with the mean age
  * Replace missing cabin values with `"Unknown"`
  * Replace missing embarkation values with `"Unknown"`
* Check for duplicate records
* Generate descriptive statistics
* Analyze:

  * Survival counts
  * Survival percentages
  * Passenger class distribution
  * Gender distribution
  * Average age
  * Minimum and maximum fare
  * Survival rate by passenger class
  * Survival rate by gender
  * Average age of survivors and non-survivors
* Create visualizations using Matplotlib
* Export the cleaned dataset as `Titanic_Cleaned.csv`

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib

---

## 📊 Visualizations

The project includes the following charts:

* Survival Count
* Gender Distribution
* Passenger Class Distribution
* Age Distribution
* Fare Distribution
* Survival Rate by Passenger Class
* Survival Rate by Gender

---

## 📂 Project Structure

```
Titanic-Data-Cleaning-EDA/
│
├── Titanic-Dataset.csv
├── Titanic_Cleaned.csv
├── titanic_analysis.py
├── README.md
└── images/ (optional screenshots of charts)
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Titanic-Data-Cleaning-EDA.git
```

2. Install the required libraries.

```bash
pip install pandas matplotlib
```

3. Run the Python script.

```bash
python titanic_analysis.py
```

---

## 📈 Project Outcomes

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Working with CSV files
* Using Pandas for data manipulation
* Using Matplotlib for creating charts

---

## 📄 License

This project is licensed under the MIT License.

