# netflix-data-cleaning-task
Elevate Labs Internship Task 1 - Netflix Movies and TV Shows Dataset Cleaning using Pandas

# Netflix Data Cleaning Task - Data Analyst Internship (Elevate Labs)

## 📌 Objective:
Clean and preprocess the raw Netflix Movies and TV Shows dataset using Python (Pandas).

---

## 🔧 Tools Used:
- Python (Pandas)
- Jupyter Notebook

---

## ✅ Steps Performed:
1. **Loaded Dataset**: `netflix_titles.csv`
2. **Checked for Missing Values**:
   - Filled `director`, `cast`, and `country` with `'Unknown'`.
   - Dropped rows with missing `date_added`, `rating`, or `duration`.
3. **Removed Duplicate Rows**
4. **Standardized Text Fields**:
   - `type` → lowercase
   - `rating` → uppercase
   - `country` → stripped whitespace
5. **Converted `date_added` to datetime format**
6. **Renamed columns to snake_case**
7. **Exported Cleaned Data** to `netflix_cleaned.csv`

---

## 📁 Files Included:
- `netflix_titles.csv` – Original Dataset
- `task 1(netflix movies and tv shows dataset_cleaning).ipynb` – Jupyter notebook with full cleaning process
- `netflix_cleaned.csv` – Final cleaned dataset
