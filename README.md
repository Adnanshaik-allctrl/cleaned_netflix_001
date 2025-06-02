# Netflix Data Cleaning – cleaned_netflix_001

This project contains a cleaned version of the Netflix titles dataset, originally sourced from Kaggle.

## Dataset Source

Original dataset: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)

- **Raw file**: `netflix_titles.csv`
- **Cleaned file**: `cleaned_netflix.csv`

## Data Cleaning Summary

The following data wrangling steps were performed in the `netflix.ipynb` notebook:

- Removed duplicate records
- Handled missing/null values in critical columns
- Standardized date formats
- Split and normalized multi-valued fields (like genres and cast)
- Ensured consistency in categorical columns (e.g., Country, Rating, Type)
- Converted data types for better usability

## 📂 Files in this Repository

- `netflix_titles.csv` — Raw dataset from Kaggle
- `cleaned_netflix.csv` — Cleaned and processed dataset
- `netflix.ipynb` — Jupyter notebook with all the data cleaning steps
- `README.md` — This file

## 🔧 Tools Used

- Python 3
- Pandas
- NumPy
- Jupyter Notebook

## 📈 Usage

You can use the cleaned dataset for exploratory data analysis, visualization, or building machine learning models on Netflix content.

---

Feel free to contribute or suggest improvements!
