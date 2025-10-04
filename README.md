\# Codveda Technologies — Data Analysis Internship (EDA Project)



\*\*Intern:\*\* Esraa Elsayed Salama  

\*\*Task:\*\* Exploratory Data Analysis (EDA)  

\*\*Tools:\*\* Python, pandas, matplotlib, seaborn, Jupyter



\## 📊 Objective

Perform EDA to calculate summary statistics, visualize distributions (histograms, boxplots, scatterplots), and identify correlations between numeric features.



\## 📂 Project Files

\- `data/iris\_dataset.csv` — dataset used for the task  

\- `notebooks/01\_EDA.ipynb` — Jupyter notebook with the analysis  

\- `outputs/summary\_stats.csv` — summary statistics (mean, median, mode, std)  

\- `outputs/figures/` — saved plots (hist\_\*.png, box\_\*.png, corr\_heatmap.png)  

\- `outputs/EDA\_report.pdf` — exported PDF report



\## 🔑 Key Findings

\- Strong correlation between `petal\_length` and `petal\_width` (~0.96).  

\- `sepal\_width` shows mild outliers.  

\- Petal features clearly separate species in the dataset.



\## 🚀 How to Run Locally

```powershell

python -m venv venv

.\\venv\\Scripts\\Activate.ps1

pip install -r requirements.txt

jupyter notebook notebooks/01\_EDA.ipynb

