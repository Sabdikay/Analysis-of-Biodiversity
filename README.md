# **Biodiversity Analysis in National Parks**  

## **Introduction**  
This project analyzes biodiversity data from the **National Parks Service**, focusing on species observed across various parks. Conducted in **Jupyter Notebook**, the analysis utilizes **pandas, NumPy, matplotlib, seaborn, and chi2_contingency** for data processing, statistical testing, and visualization.  

The goal is to explore patterns in conservation status, endangered species, and species distribution across parks.  

### **Key Questions Explored:**  
- What is the distribution of conservation status for species?  
- Are certain types of species more likely to be endangered?  
- Are the differences between species and their conservation status statistically significant?  
- Which animal is most prevalent, and how is their distribution spread across parks?  

---

## **Data Sources**  
The project is based on two datasets provided by [Codecademy](https://www.codecademy.com/):  
- **`species_info.csv`**: Contains species classification, scientific names, and conservation status.  
- **`observations.csv`**: Records species sightings across national parks in the past seven days.  

This dataset is **inspired by real-world data** and helps in understanding biodiversity trends across different regions.  

---

## **Technologies Used**  
- **Python**  
- **Jupyter Notebook**  
- **pandas** (Data processing & analysis)  
- **NumPy** (Numerical computation)  
- **matplotlib & seaborn** (Data visualization)  
- **chi2_contingency** (Statistical testing)  

---

## **Exploratory Data Analysis (EDA)**  
### **1. Understanding the Data**  
- The `species_info.csv` dataset contains **5,824 rows** and **4 columns** (Category, Scientific Name, Common Names, Conservation Status).  
- The `observations.csv` dataset contains **23,296 rows** and **3 columns** (Scientific Name, Park Name, Observations).  

### **2. Conservation Status Distribution**  
- The majority of species are **not under conservation efforts**, while a small subset falls under categories such as **Endangered, Threatened, and Species of Concern**.  
- A **pie chart** was created to visualize the distribution of conservation status.

### **3. Species Analysis**  
- The dataset contains **7 unique categories**: Mammals, Birds, Reptiles, Amphibians, Fish, Vascular Plants, and Nonvascular Plants.  
- **Mammals and Birds** were found to have the highest rate of species under protection.  

### **4. Statistical Significance Testing**  
- **Chi-squared tests** were performed to analyze differences in conservation status.  
- Results show that **mammals and reptiles** exhibit a statistically significant difference in conservation status, while **mammals and birds do not**.  

### **5. Most Observed Species**  
- The **Deep-Root Clubmoss** had the **highest number of sightings**, while the **Golden Corydalis** was the **least observed** species.  
- **Bats** were identified as the most frequently occurring mammals, with Yellowstone National Park having the highest bat sightings.  

### **6. Species Observations by National Park**  
- The dataset includes data from **four national parks**:  
  - Great Smoky Mountains  
  - Yosemite  
  - Bryce Canyon  
  - Yellowstone  
- The number of observed species was **artificially identical** across all parks, suggesting **synthetic data generation**.  

### **7. Protected vs. Non-Protected Species**  
- **Protected species** sightings were **higher than non-protected** species in most parks, except for the **Great Smoky Mountains National Park**.  

### **8. Visualizations**  
- **Bar charts** comparing species counts across parks.  
- **Stacked bar chart** showing species categories under conservation.  
- **Pie charts** visualizing conservation status distribution.  
- **Statistical plots** comparing endangered species proportions.  

---

## **Findings & Insights**  
✔ **Most species in the dataset are not under conservation efforts.**  
✔ **Mammals and birds have the highest percentage of protected species.**  
✔ **There is a significant difference in conservation status between mammals and reptiles.**  
✔ **Bats are the most commonly observed mammals, especially in Yellowstone National Park.**  
✔ **The identical species count across parks suggests that the data is artificially generated.**  

---

## **Future Research & Enhancements**  
🔹 Incorporate a **time-based dataset** to analyze trends in species conservation over the years.  
🔹 Include **national park area size** to assess biodiversity density.  
🔹 Conduct **spatial analysis** to identify clustered distributions of species.  

---

## **How to Run the Project**  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/Sabdikay/Analysis-of-Biodiversity.git
   cd Biodiversity-Analysis
   ```
2. **Install required dependencies:**  
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. **Run the Jupyter Notebook:**  
   ```bash
   jupyter notebook
   ```
4. **Open and execute the analysis notebook.**  

---

## **Conclusion**  
This project successfully analyzed biodiversity data, highlighting conservation trends and species distribution patterns across national parks. Through statistical testing and visualizations, I uncovered key insights about endangered species and national park ecosystems.  

This analysis can serve as a foundation for more in-depth studies on biodiversity, wildlife conservation, and ecological trends in protected areas.  

📊 **Explore the project and contribute to further research!** 🚀
