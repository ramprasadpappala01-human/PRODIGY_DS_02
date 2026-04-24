# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **data cleaning and exploratory data analysis (EDA)** on a Titanic dataset.
The goal is to preprocess raw data, handle missing values, encode categorical features, and visualize important patterns.

---

## 📊 Key Objectives

* Clean and preprocess dataset
* Handle missing values
* Convert categorical variables into numerical format
* Generate summary statistics
* Visualize data distributions and relationships

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Dataset

* File used: `test.csv`
* Dataset contains passenger details such as:

  * Age
  * Fare
  * Gender
  * Passenger Class
  * Embarkation Port

---

## ⚙️ Data Preprocessing Steps

1. Removed unnecessary column:

   * `Cabin`

2. Handled missing values:

   * Filled `Age` with median
   * Filled `Fare` with median

3. Encoded categorical variables:

   * `Sex`: male → 0, female → 1
   * `Embarked`: One-hot encoding

4. Dropped irrelevant columns:

   * `PassengerId`, `Name`, `Ticket`

---

## 📈 Exploratory Data Analysis

### 🔹 Summary Statistics

* Used `.describe()` to get statistical insights

### 🔹 Visualizations

* **Age Distribution** (Histogram + KDE)
* **Fare Distribution** (Histogram + KDE)
* **Passenger Class Distribution** (Count Plot)
* **Gender Distribution** (Count Plot)
* **Correlation Heatmap** (Feature relationships)

---

## 📊 Output

The project generates:

* Multiple distribution plots
* Count plots for categorical variables
* Correlation heatmap for feature relationships

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

```bash
pip install pandas matplotlib seaborn
```

### 3. Run the script

```bash
python your_script_name.py
```

---

## ⚠️ Notes

* Ensure `test.csv` is in the same directory as the script
* Missing values are handled using median imputation
* Visualization requires a graphical environment (or Jupyter Notebook)

---

## 💡 Future Improvements

* Add feature engineering
* Perform predictive modeling
* Improve visual styling
* Handle outliers explicitly

---

## 📬 Contact

Feel free to reach out for suggestions or improvements!

---

⭐ If you found this useful, consider giving the repo a star!
