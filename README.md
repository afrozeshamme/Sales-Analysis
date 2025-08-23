# 📊 Sales Analysis

This project demonstrates end-to-end **Sales Data Analysis** using Python (Jupyter Notebook) and Power BI.  
It includes data cleaning, exploratory data analysis (EDA), visualization, and an interactive dashboard.

---

## 🗂️ Repository Structure

```
.
├── Regional_Sales_Analysis.ipynb   # Jupyter Notebook with data cleaning + EDA
├── SALES REPORT.pbix               # Power BI dashboard
├── Regional Sales Dataset.xlsx     # Raw dataset
└── Sales_data(EDA Exported).csv    # Cleaned/exported dataset for BI
```

---

## 🚀 Getting Started

### Option A — Run the Jupyter Notebook

**Requirements**
- Python 3.9+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`

**Setup**
```bash
# (optional) create and activate virtual environment
python -m venv .venv
.venv\Scripts\activate   # Windows
source .venv/bin/activate   # macOS/Linux

# install dependencies
pip install pandas numpy matplotlib seaborn jupyter
```

**Run**
```bash
jupyter notebook
```
Open `Regional_Sales_Analysis.ipynb` and run all cells.

---

### Option B — Explore the Power BI Report

1. Open `SALES REPORT.pbix` in Power BI Desktop.  
2. Update file paths if prompted (point to `Sales_data(EDA Exported).csv`).  
3. Click **Refresh** to update all visuals.  

---

## 📊 Project Workflow

1. **Data Preparation**  
   - Load raw Excel file (`Regional Sales Dataset.xlsx`)  
   - Handle missing values, convert data types  
   - Export cleaned dataset to CSV  

2. **Exploratory Data Analysis (EDA)**  
   - Regional sales comparison  
   - Revenue and order trends over time  
   - Category / product performance  

3. **Visualization in Power BI**  
   - KPI cards (Revenue, Orders, Average Order Value)  
   - Bar/line charts for regions and time  
   - Interactive slicers for filtering  

---

## 🔁 Reproducing the Pipeline

1. Replace or update `Regional Sales Dataset.xlsx` with new data.  
2. Run the notebook → generates `Sales_data(EDA Exported).csv`.  
3. Open the Power BI report and click **Refresh**.  

---

## 🛠️ Possible Improvements

- Add `requirements.txt` for Python environment  
- Include screenshots of dashboard visuals  
- Create a data dictionary for all columns  
- Automate the data pipeline with scripts  

---

## 🤝 Contributing

1. Fork this repo  
2. Create a branch (`feature-xyz`)  
3. Commit your changes  
4. Open a Pull Request  

---


## 🙌 Acknowledgements

- Data Source: `Regional Sales Dataset.xlsx`  
- Analysis: `Regional_Sales_Analysis.ipynb`  
- Dashboard: `SALES REPORT.pbix`  
