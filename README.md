# QTM 350 Final Project

## 📘 Overview
The goal of this project to conduct a comprehensive data analysis using real-world data from the World Bank's World Development Indicators. We are specifically focused on assessing the relationship between primary, secondary, and tertiary school enrollment trends and a country's current economic status. Our project involves data cleaning with SQL, modeling and visualization in Python, and version control with GitHub.

## 🔍 Project Topic
**Topic Chosen:** Education  
**Indicators Used:**
- Indicator 1: SE.PRM.ENRR (School enrollment, primary (% gross))
- Indicator 2: SE.SEC.ENRR (School enrollment, secondary (% gross))
- Indicator 3: SE.TER.ENRR (School enrollment, tertiary (% gross))

## 🗂 Repository Structure
```
├── data/                    # Raw and cleaned datasets
├── docs/                    # Codebook and entity-relationship diagram
├── figures/                 # Plots and tables from the analysis
├── scripts/                 # SQL and Python scripts for data processing and analysis
├── Final Project 350.qmd    # Quarto file for generating the report
├── HTML_FINAL_REPORT.html   # HTML version of the final report
├── Final Project 350.pdf    # PDF version of the final report
└── README.md                # This file
```

## 🧰 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/briantt12/qtm350_project.git
cd qtm350_project
```

### 2. Run the Code
- **SQL Scripts:** Run the code in data_cleaning_and_descriptive_stats.ipynb to create the data tables and access descriptive statistics.
- **Python Scripts:** Run qmdDataAnalysisCode.ipynb to create plots and tables to be used within the report
- **Quarto Report:** Build and render the report using Quarto:
  ```bash
  quarto render "Final Project 350".qmd
  ```

## 👥 Team Members
- Brian Tekadtuera
- Aanya Vusirikala
- Saanvi Sood
- Anushka Basu

## 📈 Key Features
- Use of SQL for data wrangling and cleaning
- Exploratory Data Analysis and Visualization in Python
- Reproducible report with Quarto
- Version-controlled collaboration via GitHub

## 📚 Further Reading
- [World Bank WDI](https://databank.worldbank.org/source/world-development-indicators)
- [WBGAPI GitHub](https://github.com/tgherzog/wbgapi)
- [Quarto Documentation](https://quarto.org/)
