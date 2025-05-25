# Zomato Restaurant Data Analysis



## 📊 Project Overview

This project analyzes Zomato restaurant data to uncover insights about customer preferences, restaurant performance, and dining trends in India. The analysis includes exploratory data analysis (EDA), data visualization, and answering key business questions.

## 📂 Dataset Information

**File:** `Restaurant_data.xlsx`  
**Records:** 148 restaurants  
**Features:**
- Restaurant name
- Online order availability (Yes/No)
- Table booking availability (Yes/No)
- Rating (e.g., 4.1/5)
- Number of votes
- Approximate cost for two people
- Restaurant type (Buffet, Cafes, Dining, etc.)

## 🎯 Key Questions Answered

1. Which restaurant type is most popular among customers?
2. How are votes distributed across different restaurant types?
3. What is the typical rating range for most restaurants?
4. What's the average spending for couples ordering online?
5. Which ordering mode (online/offline) receives higher ratings?
6. Which restaurant types receive more offline orders?

## 🛠️ Technical Implementation

### Tools & Technologies
- **Python 3.11.4**
- **Libraries:**
  - Pandas (Data manipulation)
  - Matplotlib & Seaborn (Visualization)
- **Jupyter Notebook** (Interactive analysis)

### Data Processing Steps
1. Data loading and cleaning
2. Handling missing values
3. Feature engineering
4. Exploratory Data Analysis (EDA)
5. Visualization

## 📈 Key Findings

### 1. Restaurant Type Distribution
![Type Distribution]![image](https://github.com/user-attachments/assets/7103e3af-651a-486b-bee9-c1299fdae0ae)

- **Dining** restaurants are most popular (77)
- Followed by **Cafes** (15)
- **Buffet** and **Other** types are less common

### 2. Rating Analysis
![Rating Distribution]![image](https://github.com/user-attachments/assets/f503cdf1-c0d9-475a-830e-1424fbbe46c4)

- Most restaurants have ratings between **3.5-4.0**
- Average rating: **3.63**

### 3. Cost Analysis
![Cost Distribution]![image](https://github.com/user-attachments/assets/2829bf13-e8b6-4479-aad4-3fc94dc8e36d)

- Most common price range: **₹300-₹600** for two people
- Average spending: **₹418**

### 4. Online vs Offline Comparison
![Order Mode]![image](https://github.com/user-attachments/assets/a75a3aec-6219-4c57-b233-81bc2a2db169)

- Online orders receive **higher ratings** on average
- Dining restaurants receive more **offline orders**

## 🚀 How to Use This Project

### Prerequisites
- Python 3.11+
- Jupyter Notebook
- Required libraries (install via `requirements.txt`)

### Zomato Dataset
- Download Restaurant_data.xlsx
  

### Folder Details
1. **`data/`**  
   - Contains the raw dataset file `Restaurant_data.xlsx`
  

2. **`notebooks/`**  
   - Jupyter notebook `Restaurant_data_code.ipynb` with:
     - Data cleaning code
     - Exploratory analysis
     - Visualization code
     - Insights generation

3. **`reports/`**  
   - PDF report `Restaurant_Data-Analysis_Report.pdf` containing:
     - Full project documentation
     - Methodology
     - Analysis results
     - Visualizations
     - Conclusions

4. **Root Files**  
   - `README.md`: Project overview and documentation
   - `requirements.txt`: Python dependencies list
