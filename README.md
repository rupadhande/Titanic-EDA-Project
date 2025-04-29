# Titanic-EDA-Project

This project involves basic **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**.

---

## Steps Performed

- **Data Loading**: Imported the Titanic dataset into a pandas DataFrame.
- **Data Understanding**:
  - Used `info()` to view column names, data types, and missing values.
  - Used `describe()` to get summary statistics of numerical features.
- **Data Exploration**:
  - Used `value_counts()` to analyze distribution for categorical columns like `Sex`, `Survived`, `Pclass`, and `Embarked`.
- **Visualization**:
  - **Pairplot** (`sns.pairplot`) to visualize pairwise relationships between `Age`, `Fare`, `SibSp`, and `Parch` colored by `Survived`.
  - **Heatmap** (`sns.heatmap`) to show correlation between numerical features.
  - **Boxplot** (`sns.boxplot`) to compare `Age` and `Fare` distributions against `Pclass` and `Survived`.
  - **Scatterplot** (`sns.scatterplot`) to visualize the relation between `Fare` and `Age` based on `Survived`.
  - **Histogram** (`plt.hist`) to visualize the distribution of `Age` and `Fare`.

---

## Files Included

- **EDA_titanic_project.ipynb**: Jupyter Notebook containing all the code and visualizations.
- **The Description.pdf**: A detailed summary of the key insights and findings from the exploratory data analysis.

---

