




# **Estimation of Leaf Area Index (LAI) and NDVI Time-Series Analysis Using Landsat Imagery**  

## **1. Introduction**  
Leaf Area Index (LAI) and the Normalized Difference Vegetation Index (NDVI) are key indicators for assessing vegetation health, canopy structure, and ecosystem productivity. These indices are widely used in forestry, agriculture, and climate change studies to monitor vegetation dynamics over time.  

The study area, located in **central Nepal (27.26°N – 27.98°N, 84.92°E – 85.87°E)**, features diverse landscapes, including tropical forests, agricultural lands, and hilly terrains. The region experiences a monsoonal climate, influencing seasonal variations in vegetation cover.  

### **Objective:**  
- To estimate **LAI and NDVI trends (2015–2024)** using Landsat 8 imagery.  
- To analyze the spatial and temporal variations of vegetation in the study area.  

---

## **2. Study Area Description**  

### **Geographic and Climatic Characteristics**  
The selected region spans across **lowland Terai, Chure hills, and mid-hill regions of central Nepal**. These variations influence vegetation growth and LAI values.  

The Terai region, which includes parts of Chitwan and Makwanpur, experiences a hot and humid climate, with summer temperatures ranging from 30–40°C and winter temperatures from 5–20°C. The mid-hill regions, such as Dhading and Nuwakot, have a more temperate climate, with summer temperatures between 25–30°C and winter temperatures dropping as low as 0°C. The region receives an annual rainfall of approximately 1,500mm to 2,500mm, primarily during the monsoon season (June–September).  

### **Vegetation & Land Use**  
The study area consists of a mix of land cover types. The Terai lowlands are dominated by dense **Sal (Shorea robusta) forests**, particularly in areas such as Chitwan National Park. The Chure hills and mid-hills have a mix of **broadleaf forests and agricultural lands**, while urban and semi-urban settlements are concentrated around Hetauda and Dhading.  

---

## **3. Theoretical Background**  

### **Normalized Difference Vegetation Index (NDVI)**  
NDVI is a widely used vegetation index that assesses vegetation density and health by utilizing the red and near-infrared (NIR) bands of satellite imagery. It is calculated using the formula:  

\[
NDVI = \frac{(NIR - RED)}{(NIR + RED)}
\]  

NDVI values range from -1 to 1. Negative values (close to -1) indicate water bodies and barren land, while higher values (closer to 1) indicate dense vegetation. In this study area, NDVI values are expected to be lower in urban and agricultural areas, moderate in mixed forests, and highest in dense Sal forests.  

### **Leaf Area Index (LAI)**  
LAI measures the total one-sided leaf area per unit ground area, providing insights into vegetation structure and canopy density. Since LAI cannot be directly measured from satellite images, it is estimated using empirical relationships with vegetation indices such as EVI (Enhanced Vegetation Index).  

In this study, LAI is estimated using the equation:  

\[
LAI = 3.618 \times EVI - 0.118
\]  

where EVI is calculated as:  

\[
EVI = 2.5 \times \frac{(NIR - RED)}{(NIR + 6 \times RED - 7.5 \times BLUE + 1)}
\]  

This method is well-suited for tropical and temperate forests, making it applicable to Nepal’s diverse landscapes.  

---

## **4. Expected LAI and NDVI Patterns in the Study Area**  

### **LAI Variations Across Different Land Covers**  
In urban and barren areas such as Hetauda and parts of Dhading, LAI values are expected to be below 1, indicating minimal vegetation cover. Shrublands and degraded forests in the Chure hills typically have LAI values ranging from 1 to 2, representing low-density vegetation.  

Agricultural lands and mixed forests in the mid-hills (Makwanpur and Nuwakot) generally have moderate LAI values, ranging from 2 to 4, reflecting seasonal crop cycles and natural vegetation cover. The highest LAI values, ranging from 4 to 6, are expected in dense Sal forests found in Chitwan National Park and other protected areas. These forests have a well-developed canopy with high biomass productivity.  

### **Seasonal Variations in NDVI and LAI**  
The NDVI and LAI values in the study area fluctuate seasonally. During the **pre-monsoon period (March–May)**, vegetation growth begins, leading to moderate NDVI and LAI values. The **monsoon season (June–September)** marks the peak growing period, resulting in the highest NDVI and LAI values due to ample rainfall and favorable conditions for plant growth.  

In the **post-monsoon season (October–November)**, NDVI and LAI values gradually decline as crops are harvested and some tree species shed leaves. The lowest values are observed in **winter (December–February)** when deciduous trees lose their foliage and the overall vegetation activity decreases.  

---

## **5. Application of NDVI and LAI Analysis in the Study Area**  

Monitoring NDVI and LAI in this region provides valuable insights for various environmental applications. In **forest management**, these indices help identify areas affected by deforestation and degradation, particularly in the Chure and Terai forests. In **agriculture**, NDVI trends allow for crop health assessment, helping farmers optimize land use in Makwanpur and Nuwakot.  

From a **climate change perspective**, long-term analysis of LAI and NDVI can reveal trends in vegetation response to climate variability. Rising temperatures, altered precipitation patterns, and land-use changes impact vegetation dynamics, making continuous monitoring essential.  

Additionally, these indices are useful in **disaster management**, as they help detect drought conditions, soil erosion, and land degradation patterns. In flood-prone areas, monitoring vegetation cover can provide early warnings about changing land stability and potential risks.  

---

## **6. Conclusion**  

The study area in **central Nepal** encompasses diverse landscapes, including tropical forests, mid-hill vegetation, and agricultural lands. By analyzing **LAI and NDVI trends from 2015 to 2024**, this study provides insights into vegetation health, ecosystem stability, and climate change impacts. Seasonal variations and land cover differences significantly influence these indices, making them valuable tools for environmental monitoring and sustainable land management.  

