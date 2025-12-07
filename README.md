# 🏙️ Real Estate Data Analysis  
### Data Preparation and Exploratory Data Analysis (EDA)

This project analyzes real estate listings from a major city with a population of 5.65 million people.  
My primary task as a Data Analyst was to **prepare the data for further work**, ensure its quality, and identify key patterns supported by visual analysis.

---
The analysis follows a reproducible DS pipeline:  
<img width="708" height="177" alt="image" src="https://github.com/user-attachments/assets/535fd6ad-8f39-41b5-afe5-90445e5f0bd1" />


---
##As a Data Analyst, my role was to:

- **prepare high-quality data**,  
- **clean and structure it**,  
- **engineer informative features**,  
- **identify key market patterns**,  
- **support findings with visual evidence**,  

## ✔ What Was Done

### 1. Data inspection and error correction
- Checked missing values across all features.  
- Filled logically interpretable gaps (e.g., no balcony → 0).  
- Preserved missing values that could carry meaningful information.  
- Converted columns into proper data types (dates, booleans, numeric).

**Result:** a clean, consistent dataset suitable for analysis and modeling.

---

### 2. Cleaning and standardizing categorical data
- Processed locality names.  
- Resolved implicit duplicates and inconsistent spelling variations.

**Result:** accurate regional grouping and reliable cross-location analysis.

---

### 3. Feature engineering

---

### 4. Exploratory Data Analysis (EDA)
Conducted visual and statistical analysis of key property characteristics:

#### • Distribution of areas and ceiling heights  
Highlighted outliers and corrected unrealistic values.
<img width="583" height="379" alt="image" src="https://github.com/user-attachments/assets/b56a9733-feb3-43b1-97ce-0cada91f558d" />



#### • Price and price-per-square-meter analysis  
- Price increases with total area.  
- Kitchen area is a strong factor, especially in lower-budget segments.  
- First and last floors tend to sell at a discount.

<img width="309" height="238" alt="image" src="https://github.com/user-attachments/assets/d9e0406a-1324-4d16-b2ee-d29b09a1a1ac" />

#### • Time on market  
- Median exposure: ~90 days  
- Fast sales: up to 30 days  
- Long sales: over 180 days  

#### • Spatial price dependence  
A strong inverse relationship:  
**greater distance from the city center → lower price per m²**.

---

## 📉 Examples of Visualizations Used

- Histograms (areas, price, kitchen area, ceiling height)  
- Boxplot of price per m² by floor type  
- Scatterplots (area vs price)  
- Line chart (price per m² vs distance to center)  
- Bar chart of top 10 localities  

---

## 🧩 Key Findings

- **Total area and kitchen area** show the strongest positive relationship with property price.  
- **Price per m² declines sharply** within the first 5–7 km from the city center and stabilizes beyond ~12 km.  
- **Floor type matters**: first and top floors consistently show lower price per m² compared to mid-level floors.  
- **Ceiling heights above 3 meters** correlate with higher-priced segments.  
- **Time on market** reveals typical behavioral patterns: the majority of listings stay active around 2–3 months, while unusually long listings may indicate overpriced or low-quality properties.  
- **Locality analysis** shows clear segmentation: some areas form premium clusters, while others consistently appear in low-price segments.

Together, these insights help build a reliable foundation for modeling and explain the structure of the real estate market.

---

