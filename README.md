# 🍽️ Zomato Partnership Strategy Analysis

This project uses Zomato restaurant data to uncover insights that can help Zomato make better decisions about restaurant partnerships and onboarding.

---

## 📌 Objectives
- Identify high-potential restaurants not yet partnered for delivery
- Detect underperforming delivery partners
- Analyze how features like **online ordering**, **table booking**, and **cost** affect restaurant performance
- Recommend restaurant types and price ranges to focus on

---

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

## 🧠 Key Techniques
- Data Cleaning with **Pandas**
- Custom metric: **Reliable Rating = Rating × log1p(Votes)**
- Grouped Analysis
- Visualizations using **Seaborn** and **Matplotlib**

---

## 📊 Sample Insights
- Online ordering improves performance significantly
- Restaurants offering table booking have higher engagement
- "Other" and "Buffet" types perform best
- Mid-range restaurants (₹400–₹700) show best customer satisfaction

---

## 📁 File Structure
- `notebooks/`: Jupyter Notebook with all analysis
- `data/`: Zomato dataset (not included here due to size)
- `visuals/`: Charts and plots
- `README.md`: Project overview
- `requirements.txt`: Python libraries used

---


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



3. **Root Files**  
   - `README.md`: Project overview and documentation
   - `requirements.txt`: Python dependencies list
