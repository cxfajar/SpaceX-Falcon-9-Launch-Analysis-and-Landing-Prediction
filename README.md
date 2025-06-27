# 🚀 SpaceX Launch Analysis & Prediction | End-to-End Data Science Capstone

This repository contains a full-stack data science capstone project focused on analyzing and predicting SpaceX Falcon 9 launch outcomes. Using open data from the SpaceX API and web sources, the project walks through the entire pipeline — from data collection and cleaning to visualization, geospatial analysis, SQL queries, interactive dashboards, and predictive modeling using machine learning.

---

## 🎯 Objective

To explore SpaceX’s launch performance, understand success patterns across sites and payloads, and build a machine learning model to predict future launch outcomes. This includes:

- Collecting launch data via SpaceX REST API and web scraping  
- Wrangling and cleaning data for analysis  
- Performing exploratory data analysis (EDA) with plots and statistics  
- Running geospatial analysis and SQL queries  
- Building interactive dashboards using Plotly Dash  
- Training and evaluating classification models to predict mission success

---

## 🗂️ Repository Contents

| Notebook | Description |
|----------|-------------|
| `jupyter-labs-spacex-data-collection-api.ipynb` | Pulls launch data using the SpaceX REST API |
| `labs-jupyter-spacex-Data wrangling.ipynb` | Cleans and transforms raw data for analysis |
| `edadataviz.ipynb` | Visual EDA using Matplotlib and Seaborn |
| `lab_jupyter_launch_site_location.ipynb` | Maps launch sites and nearby geography using Folium |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Performs SQL-based analysis on the cleaned dataset |
| `SpaceX_Machine Learning Prediction_Part_5.ipynb` | Trains, evaluates, and compares classification models |

---

## 🔍 Key Highlights

### 1️⃣ Data Collection

- Collected SpaceX launch data using **REST API** and **web scraping**
- Extracted JSON payloads for each launch and normalized them into structured data
- Created a historical dataset of Falcon 9 missions

### 2️⃣ Data Wrangling

- Cleaned columns, standardized units, removed missing values
- Transformed features such as payload mass, orbit type, and landing outcomes
- Created binary target labels for classification

### 3️⃣ EDA & Visualization

- Analyzed launch trends over time, by site, and by payload
- Visualized:
  - Payload vs. Success
  - Flight number vs. Orbit
  - Success rates per orbit type
  - Yearly success rate trends

### 4️⃣ Geospatial Mapping with Folium

- Mapped global launch sites with markers
- Labeled success/failure outcomes visually on map
- Analyzed proximity of launch sites to railways, coastlines, highways

### 5️⃣ SQL Analysis

- Queried launch success by site and orbit using SQLite
- Calculated average/total payloads for specific boosters
- Identified top-performing boosters and earliest ground landings

### 6️⃣ Interactive Dashboard (Plotly Dash)

- Pie charts of launch success count by site
- Scatter plot of Payload Mass vs. Success
- Slider-based payload filter to dynamically explore trends
- User-interactive analysis to support decision-making

### 7️⃣ Predictive Modeling

- Built and compared multiple **classification models**:
  - Logistic Regression
  - Decision Trees
  - SVM
  - Random Forest
- Used grid search and cross-validation for model tuning
- Visualized:
  - Model accuracy comparison
  - Confusion matrix of best model

---

## 📊 Sample Insights

- Launch success improves significantly with lower payloads and later flight numbers  
- Cape Canaveral has the most launches, but VAFB has highest success ratio  
- Most successful missions land on drone ships with specific boosters  
- Best ML model achieves ~92% accuracy in predicting launch outcomes  

---

## 🧰 Tools & Technologies

- Python, Pandas, NumPy, Matplotlib, Seaborn  
- REST API, BeautifulSoup (Web Scraping)  
- SQLite, SQLAlchemy  
- Folium (Geospatial Maps)  
- Plotly Dash (Dashboard)  
- Scikit-learn (ML Models)

---

## 🧠 Learning Outcomes

- Apply a **full data science workflow** from raw data to insight and prediction  
- Integrate **APIs**, **SQL**, **EDA**, **mapping**, and **machine learning** in one project  
- Create end-to-end storytelling using Jupyter Notebooks

---

## 📎 Capstone Alignment

This repository satisfies all major components of the Coursera IBM Data Science Capstone:

- ✅ Data Collection (API + Web Scraping)  
- ✅ Data Wrangling  
- ✅ Exploratory Data Analysis (Visualization + SQL)  
- ✅ Interactive Visual Analytics (Folium, Plotly Dash)  
- ✅ Predictive Analysis (Classification Models)

---

## 📌 How to Use

1. Clone the repository  
```bash
git clone https://github.com/yourusername/spacex-capstone.git
cd spacex-capstone
***
Run notebooks in order, ideally via Jupyter or Colab

Modify data paths or install missing libraries if needed (requirements.txt can be added)

👏 Acknowledgments
This project was built as part of the IBM Data Science Professional Certificate (Coursera). Special thanks to SpaceX and public open data sources for enabling real-world applications in learning.

⭐ Like this work?
Star this repo and feel free to fork it!
You can adapt this pipeline to other real-time data APIs and mission-critical applications.

