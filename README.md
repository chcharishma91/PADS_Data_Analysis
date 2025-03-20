# PADS_Data_Analysis  
## Parkinson’s Disease Smartwatch Data Analysis  

### **Project Overview**  
This project analyzes the **Parkinson’s Disease Smartwatch Dataset (PADS)** from [PhysioNet](https://physionet.org/content/parkinsons-disease-smartwatch/1.0.0/), focusing on:  
- Tremor patterns  
- The effect of alcohol on tremors  
- Motor symptom variations  

The dataset includes **time-series movement data, questionnaire responses, and patient demographics**.  
The goal is to extract insights into how different factors impact tremors and overall motor function.  

---

## **Objectives**  
1. **Data Cleaning & Exploration**: Process raw data using **Python** and **Power BI**.  
2. **Tremor Analysis**: Assess the **impact of alcohol on tremors** using movement data (**tremor_X, tremor_Y, tremor_Z**).  
3. **Visualization**: Develop **interactive Tableau dashboards** to represent trends and patterns.  

---

## **Dataset Information**  
- **Source**: [PADS - Parkinson’s Disease Smartwatch dataset](https://physionet.org/content/parkinsons-disease-smartwatch/1.0.0/)  
- **Data Structure**:  
  - **Movement**: Time-series smartwatch sensor data  
  - **Questionnaire**: Patient responses on symptoms  
  - **Patients**: Demographic and clinical information  

---

## **Tools & Technologies**  
- **Power BI** – Data cleaning and initial analysis  
- **Jupyter Notebook (Python)** – Data exploration and processing  
- **Tableau** – Interactive visualizations  

---

## **Key Insights**  
- **Does alcohol improve or worsen tremors?**  
- **Which patient demographics show severe symptoms?**  
- **What are the tremor patterns?**  
- **What correlations exist between questionnaire responses and movement data?**  

---

## **Project Structure**  


PADS_Data_Analysis
│ -- data/ # [Raw and processed dataset](https://www.dropbox.com/scl/fi/w5q0mantky7y3z83yx99t/pads-parkinsons-disease-smartwatch-dataset.zip?rlkey=ojegoam7d8s9rl6tnb6voytpn&st=b9cq3n8o&dl=0)

│ -- notebooks/ # Jupyter Notebooks for analysis

│ -- reports/ # Visualizations and insights

│ -- README.md # Project documentation

│ -- Detailed_Project_Documentation/ # Additional project details

│ -- PADS_analysis.pbix # [Power BI data model and cleaning steps](https://www.dropbox.com/scl/fi/3g9f7m9mlvcnlyai6wszd/PADS_Analysis.pbix?rlkey=ddzlic99p4mf8h82g38dcfd0s&st=kqpu8zxt&dl=0)


---

## **Visualizations & Dashboards**  
- **Tableau**: Dashboards for **demographics, questionnaire responses, and tremor analysis**.  

---

## **How to Run This Project**  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/chcharishma91/PADS_Data_Analysis.git  
   cd PADS_Data_Analysis  

2. **Open Power BI** and load `PADS_analysis.pbix` for data exploration  
    *(Refer to the **Detailed Project Documentation** for step-by-step guidance.)*  
3. **Use Tableau** to interact with the visualizations.  
4. **Run Jupyter Notebooks** for deeper data analysis.  

---

## **Next Steps**  
- Implement **feature engineering** for more granular tremor analysis.  
- Develop **machine learning models** to predict symptom progression.  
- Expand **medication effect analysis** using statistical methods.  

---

## **Acknowledgments**  
- **Dataset Credits**: PhysioNet contributors  
- **Tools Used**: Power BI, Tableau, Jupyter Notebook  


