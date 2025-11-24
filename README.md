# Notebooks Contest – Fabric Data Days 2025  
## Cities of Tomorrow: Urban Growth & Sustainability

This repository contains my submission for the **Microsoft Fabric Data Days – Notebooks Contest**, themed **“The Cities of Tomorrow – Urban Growth & Sustainability.”**  
The project is implemented with **Python** in a **Microsoft Fabric Notebook** and follows the official contest requirements (EDA, modeling and data storytelling in a single `.ipynb` file).

---

## 1. Project Overview

As the world’s population becomes increasingly urban, cities face the challenge of balancing **growth, livability and environmental sustainability**.  

This project uses open data and Fabric notebooks to:

- Explore patterns of **urban sustainability** across cities  
- Build an **Urban Sustainability Index (USI / IES)** that combines multiple indicators  
- Apply **EDA, clustering and predictive modeling** to profile “cities of tomorrow”  
- Tell a **clear, narrative-driven story** about how data can guide better urban policy

The final deliverable notebook is:

- **`Nov2025_RenanOliveiraAndrade_CitiesOfTomorrow.ipynb`**  
  - Single notebook, ready to be uploaded to the **Fabric Notebook Gallery** as required by the contest.

---

## 2. Repository Structure

```
.
├── datasets/                  
│   ├── urban_planning_dataset.csv          
│   ├── wdi_*.csv                            
│   ├── un_*.xlsx                            
│   └── ...                                  
│
├── images/                    
│   └── ... 
│
├── links/                     
│   └── ... 
│
├── Nov2025_RenanOliveiraAndrade_CitiesOfTomorrow.ipynb
│
├── wdi-download.ipynb          
├── unhabitat-download.ipynb    
│
├── .gitignore                  
└── README.md                   
```

> **Note:** All analysis for the contest is consolidated in the main notebook.

---

## 3. Data Sources

### 3.1 Primary Dataset (Kaggle – Required)

**Sustainable Urban Planning & Landscape Dataset – Kaggle**

- Granularity: **City-level**  
- Examples of fields:  
  - Green Area %  
  - Urban Density  
  - Transport Infrastructure Score  
  - Renewable Energy Index  
  - Pollution Index  
  - Livability Index  

### 3.2 Optional Context Datasets (Global Indicators)

1. **World Bank – WDI**  
2. **UN-Habitat – SDG Indicators**  

---

## 4. Notebook Contents

1. Introduction  
2. Data Loading & Cleaning  
3. Exploratory Data Analysis  
4. Urban Sustainability Index (USI / IES)  
5. Modeling & Clustering  
6. Global Context  
7. Conclusions  

---

## 5. How to Run

### Microsoft Fabric
1. Upload the notebook and datasets.  
2. Attach a Lakehouse.  
3. Run the notebook sequentially.

### Local (Jupyter / VS Code)

```
git clone https://github.com/axlrn/Notebooks-Contest-Fabric-Data-Days-2025.git
pip install -r requirements.txt
jupyter lab
```

---

## 6. Contest Compliance

- Single `.ipynb`
- Python code + EDA + storytelling  
- Optional modeling  
- Public data sources only  

---

## 7. Credits

Author: **Renan Oliveira Andrade**  
Contest: *Microsoft Fabric Data Days – Notebooks Contest*  
