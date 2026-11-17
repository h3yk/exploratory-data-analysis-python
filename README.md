# Exploratory Data Analysis (EDA) in Python

Exploratory data analysis across four datasets (`diamonds`, `iris`, `tips`, and `titanic`) using Python, `pandas`, `NumPy`, `Matplotlib`, and `Seaborn`.

## Project Structure

* `project (2).ipynb` — Main Jupyter Notebook with code, visualizations, and interpretations

* `project (2) (1).html` — Exported HTML report of the notebook

* `datasets/` — Source CSV files (`diamonds.csv`, `iris.csv`, `tips.csv`, `titanic.csv`)

## Analysis Covered

1. **Data Importing & Overview** — Loading the four CSV datasets and inspecting initial records.

2. **Dataset Shapes & Data Quality** — Reviewing dimensions, data types, and missing value counts (e.g., `age`, `embarked`, `deck`, and `embark_town` in `titanic.csv`).

3. **Summary Statistics** — Computing descriptive statistics for numerical columns.

4. **Univariate Analysis** — Visualizing numerical distributions (diamond `price` histogram with KDE) and categorical frequencies (diamond `cut` countplot).

5. **Bivariate Analysis** — Exploring relationships across variable types:

   * *Numerical–Numerical*: `total_bill` vs. `tip` scatterplot (`tips`)

   * *Numerical–Categorical*: `total_bill` distribution by `day` boxplot (`tips`)

   * *Categorical–Categorical*: Customer `time` vs. `smoker` grouped countplot (`tips`)

6. **Multivariate Analysis** — Multi-variable scatterplots (`iris`) and a numerical correlation heatmap (`tips`).

## Tools & Libraries

* Python 3

* `pandas` & `NumPy`

* `Matplotlib` & `Seaborn`

* Jupyter Notebook / Google Colab

## Author

Hayk Nahapetyan
