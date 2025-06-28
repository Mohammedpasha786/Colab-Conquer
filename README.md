# iris_eda.ipynb
# 🌸 Iris Dataset Exploratory Data Analysis (EDA)

This project demonstrates basic **Exploratory Data Analysis (EDA)** on the famous [Iris dataset](https://bit.ly/4nejNue) using **Python**, **Pandas**, **Matplotlib**, and **Google Colab**.  
It provides a statistical summary and visual insights into the dataset to help understand the distribution and characteristics of its features.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/iris-eda/blob/master/iris_eda.ipynb)

---

## 📁 Contents

- `iris_eda.ipynb`: Jupyter Notebook with all EDA steps implemented.
- `README.md`: Detailed explanation of the project, approach, and usage instructions.

---

## 📌 Dataset Information

The **Iris dataset** contains **150 rows and 5 columns**, with the following features:

- **sepal_length** (cm)
- **sepal_width** (cm)
- **petal_length** (cm)
- **petal_width** (cm)
- **species** (class label: `setosa`, `versicolor`, `virginica`)

---

## 🧠 Project Objective

The goal of this notebook is to:

1. Load the Iris dataset from a remote URL.
2. Display basic information and descriptive statistics.
3. Compute and display key statistics: **mean**, **median**, and **standard deviation**.
4. Visualize the feature distributions using **histograms**.

---

## ⚙️ Approach

### 1. **Data Loading**
- Loaded the dataset directly from a shortened link using `pandas.read_csv()`.

### 2. **Data Summary**
- Used `.head()`, `.info()`, and `.describe()` to explore structure and data types.
- Computed:
  - **Mean** – Central tendency of features
  - **Median** – Middle value of each feature
  - **Standard deviation** – Spread of feature values

### 3. **Visualization**
- Created **histograms** for each numeric feature using `pandas.DataFrame.hist()` and `matplotlib`.
- Aimed to understand the distribution and potential outliers.

---

## 📊 Sample Output

- Mean, median, and standard deviation values printed for each numeric column.
- Histograms showing feature-wise distribution for:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## 🚀 How to Run

1. Click the **Colab badge** above or [open this notebook in Google Colab](https://colab.research.google.com/github/yourusername/iris-eda/blob/master/iris_eda.ipynb).
2. Run each cell in the notebook to explore the dataset step-by-step.

---

## 📌 Tools Used

- [Google Colab](https://colab.research.google.com/)
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn (optional)](https://seaborn.pydata.org/)

---

## 📚 References

- [Iris Dataset – UCI Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)


