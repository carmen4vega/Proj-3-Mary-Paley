# **Project 3: Team Mary Paley**

### **Objective**  
Understanding the relationship between diet, budget, and prices in the Ugandan population from 2005 to 2020.

---

### **Group Members**
- Emily Wu: wuemily@berkeley.edu  
- Rania Nasser: ranianasser@berkeley.edu  
- Jing Huang: hjing0117@berkeley.edu  
- Carmen Vega: carmenvega@berkeley.edu  
- Mario Zhao: mario.zhao@berkeley.edu  

---

### **Project Structure**

#### 📁 **Data Files**  
Contains all CSV files used in our analysis, including raw and cleaned datasets from various Uganda surveys.

#### 📁 **Nutrient Data**  
Includes saved nutrient dataframes generated from our analysis for each year of data. These were used to assess dietary quality and nutritional trends over time.

#### 📁 **RGSN Files**  
Stores regression-ready data for each year, used in our statistical modeling and demand estimation analyses.

#### 📄 **Acquiring Dataframes.ipynb**  
Notebook containing the preprocessing and wrangling code needed to generate all key dataframes for analysis, including:
- Expenditures  
- Prices  
- Consumption  
- Household Characteristics  
- Food Conversion Table (FCT)  
- Recommended Daily Intakes (RDI)  

#### 📄 **Uganda .ipynb Files**  
A set of 8 Jupyter notebooks, each corresponding to a specific survey year:
- 2005-06, 2009-10, 2010-11, 2011-12, 2013-14, 2015-16, 2018-19, 2019-20  
Each file contains year-specific data cleaning, analysis, and insights.

#### 📄 **Visualization Notebooks**  
- `Visualizations_Food_Inflation.ipynb`: Focuses on price trends over time.  
- `Visualizations_General.ipynb`: General exploration of food consumption and budget trends.  
- `Visualizations_Precipitation.ipynb`: Explores seasonal and climate-related effects on food demand.

#### 📄 **Presentation Slides**  
Final presentation titled **"UGANDA FOOD & CONSUMER DEMAND DURING WET & DRY SEASONS"**. Highlights:
- Interpreting household food demand in Uganda  
- Analyzing the effect of climate shocks on consumption  
- Identifying economic drivers of food insecurity  

#### 📄 **requirements.txt**  
Contains dependencies needed to run our notebooks, including the `cfe` module used in our demand estimation.
