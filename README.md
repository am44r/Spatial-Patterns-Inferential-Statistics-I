# 🌍 GGR276 - Spatial Patterns & Inferential Statistics  

## 📖 Overview  
This project is part of **Spatial Data Science I (GGR276)** at the **University of Toronto Mississauga**. The objective is to analyze **global surface air temperature trends** and **greenhouse gas emissions** using **spatial statistics and inferential methods** in **ArcGIS Pro and R**.  

## 🎯 Objectives  
- **Create probability maps** and analyze **spatial patterns** using physical science datasets.  
- Develop proficiency in **spatial analysis tools** using **Excel, ArcGIS Pro, and R**.  
- Perform **inferential statistics** on **greenhouse gas emissions** using **R**.  

## 📂 Datasets  
The analysis is based on **two datasets**:  

### **1️⃣ UDEL-TS Global Monthly Mean Surface Air Temperature (1901-2017)**  
- Source: **National Oceanic and Atmospheric Administration (NOAA)**  
- Download Link: [NOAA Air Temperature Dataset](https://downloads.psl.noaa.gov/Datasets/udel.airt.precip/air.mon.mean.v501.nc)  
- Spatial Resolution: **0.5-degree grid (28 km cell size)**  

### **2️⃣ Greenhouse Gas Emissions from Large Facilities (Canada, 2022)**  
- Source: **Canadian Environmental Sustainability Indicators (CESI)**  
- Layer ID: `5e327ce4bdd7490cafd03c7e6eadc1a6`  
- Available in: **ArcGIS Living Atlas**  

---

## 🔧 Tools & Software  
This project is implemented using:  
- **R** – for inferential statistics  
- **ArcGIS Pro (Optional)** – for visualization and raster analysis  

---

## 🚀 Project Workflow  

### **1️⃣ Spatial Pattern Analysis (ArcGIS / QGIS)**  
- Import the **NOAA Air Temperature Dataset** as a **multidimensional raster**.  
- Filter temperature data from **2000-2017** for specific months.  
- Calculate **descriptive statistics**:  
  - Mean  
  - Standard Deviation  
  - Minimum / Maximum  
  - Range  
- Produce **two maps**:
  - **Mean Air Temperature**
  - **Standard Deviation of Air Temperature**
- Analyze **spatial trends** in temperature across **Canada** and **the world**.

### **2️⃣ Temporal Analysis**  
- Use **temporal profiles** to inspect **climate trends** in different regions:  
  - **Northern Canada**  
  - **Inland regions**  
  - **Western & Eastern coasts**  
- Identify long-term climate patterns using **time-series analysis**.

### **3️⃣ Trend & Model Building**  
- Perform **linear regression modeling** for **climate trends**.  
- Generate a **Trend Raster** to identify regions with **significant warming trends**.  
- Compute **R-squared and P-values** to evaluate model performance.

### **4️⃣ Inferential Statistics in R**  
- Load **Greenhouse Gas Emissions Data** into **R**.  
- Perform **two-sample & three-sample difference of means tests**.  
- Use **statistical tests** to determine emission trends across industries.  
- Visualize results using **ggplot2**.  

---  
