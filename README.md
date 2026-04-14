<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:134E5E,100:71B280&height=200&section=header&text=Chicago%20Green%20Area%20Analysis&fontSize=30&fontColor=ffffff&animation=fadeIn" />

### 🌳 Spatial Analysis of Urban Green Space & Equity  
### *A Data-Driven Study of Chicago’s Community Areas*

![GIS](https://img.shields.io/badge/Field-Geospatial%20Analysis-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Urban%20Sustainability-green?style=for-the-badge)
![Tools](https://img.shields.io/badge/Tools-GIS-orange?style=for-the-badge)
![City](https://img.shields.io/badge/City-Chicago-red?style=for-the-badge)

</div>

---

## Overview

This project analyzes the **distribution of green spaces (parks)** across Chicago and evaluates **spatial inequality in access** using demographic and geospatial data.

The study integrates:
- Green area distribution  
- Population density  
- Socioeconomic indicators  

to support **equitable urban planning and sustainability decision-making**.

---

## Project Objectives

- Quantify green space distribution across 77 community areas  
- Analyze spatial inequality in park accessibility  
- Compare green coverage vs population density  
- Evaluate accessibility for **low-income residents**  
- Support **data-driven urban planning policies**  

---

## Study Area

### Chicago, Illinois, USA

- Population: ~2.7 million  
- Administrative Units: **77 Community Areas**  
- Features:
  - Extensive park system  
  - Lake Michigan shoreline parks  
  - Strong socioeconomic contrasts  

---

## Background

<details>
<summary><strong> Why this study matters</strong></summary>

Urban green spaces:
- Improve **mental & physical health**  
- Reduce **urban heat island effects**  
- Enhance **livability and biodiversity**  

However, access is often **unevenly distributed** due to:
- Historical zoning  
- Urban development patterns  
- Socioeconomic disparities  

This project investigates these inequalities using spatial data analysis.

</details>

---

## Data Sources

<details>
<summary><strong> Click to expand data sources</strong></summary>

- Chicago City Boundary  
- Parks (Green Areas)  
- Community Areas  
- Population Data (ACS 5-Year)  
- Chicago Rail Lines  

All datasets were obtained from the **Chicago Data Portal**.

</details>

---

## Methodology

<details>
<summary><strong> Data Processing Workflow</strong></summary>

### Step 1: Data Integration
- Joined population data to community areas using **community name**

### Step 2: Spatial Overlay
- Intersected parks with community boundaries

### Step 3: Area Calculation
- Calculated park areas using **geometry tools**
- Aggregated total green area per community

### Step 4: Data Enrichment
- Joined aggregated green area back to community dataset

</details>

---

## Workflow Summary

```text
Acquire Data
   ↓
Join Population Data
   ↓
Intersect Parks with Communities
   ↓
Calculate Park Area
   ↓
Aggregate Green Space
   ↓
Join Results
   ↓
Spatial Analysis & Mapping
```

---

## Analysis & Results

---

### 1. Distribution of Green Areas

<details>
<summary><strong>View Interpretation</strong></summary>

- Parks are **generally well distributed**
- Strong concentration along **Lake Michigan shoreline**
- **O’Hare** shows minimal green space (airport dominance)
- Rail access favors **northern & central areas**
- Southern regions show **reduced accessibility**

</details>

---

### 2. Green Area Coverage (Choropleth)

<details>
<summary><strong>View Interpretation</strong></summary>

- Highest coverage near **Lake Michigan**
- Few communities exceed **~21% green coverage**
- Inner-city areas show **lower green space availability**
- Highlights **clear spatial inequality**

</details>

---

### 3. Population Density Distribution

<details>
<summary><strong>View Interpretation</strong></summary>

- High density:
  - Northern neighborhoods  
  - City center  

- Low density:
  - Industrial zones (e.g., O’Hare)  
  - Southern peripheries  

- Reveals **north–south spatial gradient**

</details>

---

### 4. Population per Green Area

<details>
<summary><strong>View Interpretation</strong></summary>

- High values = **low access to green space**
- Most disadvantaged:
  - Inner-city areas  
  - Northwestern communities  

- Better access:
  - Lakefront communities  

- Example hotspots:
  - Avondale  
  - Humboldt Park  

</details>

---

### 5. Green Space per Low-Income Residents

<details>
<summary><strong>View Interpretation</strong></summary>

- Most communities show **limited access for low-income groups**
- Southern areas:
  - Lower density  
  - Some green availability  
  - BUT poor accessibility (limited rail access)

- Indicates:
  - **Environmental inequality**
  - **Transport-access gap**

</details>

---

## Sample Result

<div align="center">

<img src="result/GreenAreas_per_Comm.png" alt="" width="700">

</div>

---

## Key Insights

- Green space distribution is **not equitable**  
- Lakefront areas dominate in green availability  
- Transport accessibility influences park usage  
- Inner-city & NW regions are most underserved  
- Low-income populations face **disproportionate limitations**  

---

## Tools Used

- GIS Software (ArcGIS Pro) 

---

<div align="center">

#### 🌟 This project highlights the role of geospatial analysis in promoting urban equity. Star this project if foud useful.

</div>
