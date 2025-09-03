# Exploratory Data Analysis(EDA) of COVID-19 
Capstone project analyzing COVID-19 dataset with EDA and visualizations.

## 📌 Problem Statement
The COVID-19 pandemic disrupted health systems and economies worldwide.  
This project performs **Exploratory Data Analysis (EDA)** and visualization on COVID-19 data to identify global and regional trends in cases, deaths, and recoveries.  

The objective is to transform raw COVID-19 data into actionable insights by applying cleaning, preprocessing, and statistical analysis.

---

## 🎯 Objectives
- Clean and preprocess the raw COVID-19 dataset.  
- Create a **processed dataset** for analysis and visualization.  
- Perform **univariate, bivariate, and time-series analysis**.  
- Visualize pandemic waves, continent-level comparisons, and trends.  
- Provide insights into mortality rates and pandemic progression.  

---

## 📂 Repository Structure

COVID19-Data-Analysis/
│── data/
│    ├── dataset_link.md              # Links to raw + processed datasets
│    └── .gitkeep                     # Keeps folder in GitHub
│
│── notebook/
│    ├── Covid - 19_Data_Analysis.ipynb # Jupyter Notebook with full analysis
│    ├── data_analysis_link.md        # Additional dataset reference (if needed)
│    └── .gitkeep
│
│── requirements.txt                  # Python dependencies
│── README.md                         # Project overview (this file)



---

## 📊 Dataset

### Sources
- **Raw Dataset**: [covid-data.csv (GitHub source)](https://raw.githubusercontent.com/SR1608/Datasets/main/covid-data.csv)  
- **Processed Dataset**: [covid19-data.csv (Google Drive link)](https://drive.google.com/file/d/13HT01DAlO-JWNIA7aCER4S5LvpfZZupo/view?usp=sharing)  
### Processed Dataset Features
- `date` → Record date  
- `continent` → Continent name  
- `location` → Country name  
- `new_cases` → New confirmed cases (daily)  
- `new_deaths` → New confirmed deaths (daily)  
- `total_cases` → Cumulative confirmed cases  
- `total_deaths` → Cumulative deaths  
- `fatality_rate` → Derived feature (deaths / cases)  
- `rolling_avg_cases` → 7-day moving average of cases  
- `rolling_avg_deaths` → 7-day moving average of deaths  

---

## 🔍 Methodology
1. **Data Collection**  
   - Retrieved COVID-19 dataset from open-source repository.  

2. **Data Cleaning & Preprocessing**  
   - Removed duplicates and handled missing values.  
   - Converted `date` column to datetime.  
   - Aggregated country and continent-level statistics.  
   - Created derived variables (fatality rate, rolling averages).  

3. **Exploratory Data Analysis (EDA)**  
   - Univariate: case distributions, death counts.  
   - Bivariate: correlation between cases and deaths.  
   - Time-series analysis: case spikes and mortality trends.  

4. **Visualization**  
   - Line plots for time-series progression.  
   - Bar charts for top-affected countries.  
   - Heatmaps for continent-level analysis.  

---

## 📈 Results & Insights
- Global spikes in cases aligned with major pandemic waves.  
- Mortality trends varied by continent, with some showing significantly higher fatality rates.  
- Rolling averages highlighted the **second and third waves** of COVID-19 spread.  
- Processed dataset enabled clearer comparisons between countries and regions.  

---

## 🛠️ Tech Stack
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`  
- **Jupyter Notebook** for analysis  
- **Google Drive** for processed dataset hosting  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<digvijay2420>/COVID19-Data-Analysis.git
   cd COVID19-Data-Analysis
