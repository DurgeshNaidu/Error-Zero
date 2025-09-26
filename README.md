# 🧹 Data Cleaning System (Python + Jupyter)

This project is a **menu-driven data cleaning system** for customer databases.  
It allows you to load, clean, and export datasets from multiple formats like **CSV, Excel, JSON, and SQL**.

---

## 🚀 Features
- Load data from **CSV, Excel, JSON, SQL**
- Preview raw data
- Cleaning options:
  - Remove duplicates
  - Handle missing values (drop or fill)
  - Standardize emails
  - Clean phone numbers
  - Normalize column names
  - Convert dates to `YYYY-MM-DD`
- Export cleaned dataset to **CSV, Excel, JSON**
- Generate cleaning report

---

## 📂 Project Structure
```
data-cleaning-system/
│── data_cleaning_system.ipynb   # Main Notebook
│── customer_sample.csv          # Sample dataset
│── requirements.txt             # Dependencies
│── README.md                    # Documentation
```

---

## ⚙️ Installation
Clone this repository:
```bash
git clone https://github.com/your-username/data-cleaning-system.git
cd data-cleaning-system
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:
```bash
jupyter notebook
```

---

## ▶️ Usage
1. Open `data_cleaning_system.ipynb` in Jupyter Notebook.
2. Run all cells.
3. Use the **menu system**:
   - Load a file (CSV, Excel, JSON, SQL)
   - Preview & clean data
   - Export cleaned file
   - Generate report

---

## 🧪 Example Dataset
A sample dataset (`customer_sample.csv`) is included to test:
- Duplicate records
- Messy emails
- Inconsistent phone numbers
- Mixed date formats
- Missing values

---

## 📊 Sample Report
Example after cleaning:
```
📊 Cleaning Report:
- duplicates_removed: 1
- missing_handled: 2
```

---

## 📌 Future Improvements
- Add GUI (Streamlit/Gradio) for non-technical users
- Support for more file formats
- Automated profiling with `pandas-profiling`

---

## 👨‍💻 Author
Developed by **Your Name**
