# Smart Street Lighting Efficiency — Melbourne Case Study

**Author:** Saneli Wijesinghe  
**Type:** University Project  
**Skills Demonstrated:** Python · Data Cleaning · Data Visualization · APIs · Geospatial Analysis

---

## 📌 Overview
This university project investigates the efficiency of **smart street lighting** in Melbourne by comparing council-owned streetlight locations with pedestrian movement patterns.  
Using **City of Melbourne open datasets**, the study identifies **underlit** or **overlit** areas to support **energy savings** and **public safety improvements**.

---

## 🗂 Data Source
All data for this project was sourced from the **[City of Melbourne Open Data Portal](https://data.melbourne.vic.gov.au/)**, specifically:
- **Pedestrian Counting System — Monthly Counts**
- **Council-Owned Streetlights**

---

## 🎯 Objective
Urban planners must ensure that street lighting aligns with actual pedestrian traffic patterns.  
Over-lighting wastes energy; under-lighting compromises safety.  
This project uses **open data** and **spatial analysis** to evaluate how well current lighting placement matches pedestrian movement.

---

## 📚 Learning Outcomes
Through this project, I learned to:
- Retrieve open datasets via **API calls**.
- Clean and preprocess **real-world data**.
- Extract and work with **GPS coordinates**.
- Perform **spatial joins** to combine movement and infrastructure data.
- Create **interactive maps** and **heatmaps** to communicate findings.

---

## 🛠 Methodology
1. **Data Retrieval**
   - Accessed datasets through City of Melbourne APIs.
2. **Data Cleaning & Processing**
   - Removed nulls, standardized coordinate formats, filtered by relevant time ranges.
3. **Spatial Analysis**
   - Mapped pedestrian counts against streetlight positions.
   - Highlighted areas with high foot traffic but insufficient lighting.
4. **Visualization**
   - Built interactive maps (Folium/Plotly).
   - Created density heatmaps to compare lighting and pedestrian flow.

---

## 📊 Results
- Several **high-traffic zones** were found to be **underlit**.
- Some low-traffic zones had **excessive lighting**, suggesting energy-saving opportunities.
- Recommendations were proposed for **redistribution** and **optimization** of streetlights.

---

## 📈 Future Work
- Incorporate **seasonal traffic variations**.
- Predict **future lighting needs** using machine learning.
- Include **crime statistics** for safety-driven decision-making.

---


## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/<your-username>/smart-street-lighting-efficiency.git
cd smart-street-lighting-efficiency

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/UC00166_Smart\ Street\ Lighting\ Efficiency.ipynb

