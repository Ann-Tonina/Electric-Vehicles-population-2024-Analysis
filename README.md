# 🚗 Electric Vehicle (EV) Data Analysis - Washington State

## 📌 Project Overview

This report presents a comprehensive analysis of electric vehicle trends in Washington State using registration and model data. The study identifies patterns in EV adoption by year, make, model, and county. Insights are aimed at stakeholders including automakers, policy makers, utility companies, and EV dealers.

---

## 🎯 Objectives

- Understand the characteristics and growth of EV adoption.
- Identify the most popular EV models and manufacturers.
- Analyze the geographic distribution of EV usage.
- Explore correlations between EV attributes such as price, range, and model year.
- Provide insights and recommendations for stakeholders in the EV ecosystem.

---

## 🧾 Dataset Description

- **Dataset Size**: 177,473 entries
- **Columns:** 17
- **Location**: Washington State
- **Timeframe**: Model Years 2000–2024
- **Features Overview:**
  - `VIN (1-10)`, `Make`, `Model`, `Model Year`: Vehicle identifiers
  - `Electric Vehicle Type`: Type (BEV, PHEV, etc.)
  - `Electric Range`, `Base MSRP`: Performance and cost
  - `CAFV Eligibility`: Clean Alternative Fuel Vehicle eligibility
  - `Geographic Info`: City, State, County, ZIP, Census Tract
  - `Electric Utility`, `Legislative District`

---

## 📁 Project Structure

EV-Data-Analysis/
│
├── data/
│ └── ev_data.csv
├── notebooks/
│ └── eda.ipynb
├── src/
│ └── correlation_analysis.py
│ └── visualizations.py
├── outputs/
│ └── charts/
├── README.md
├── requirements.txt
└── LICENSE


---

## ⚙️ Methodology

1. **Data Cleaning**: Verified non-null values, checked data types, cleaned location fields.
2. **Exploratory Data Analysis (EDA)**: Analyzed top models, manufacturers, and range/price distributions.
3. **Correlation Analysis**: Investigated relationships between Electric Range, MSRP, and Model Year.
4. **Visualization**: Charts generated using seaborn/matplotlib for patterns in the dataset.
5. **Insight Extraction**: Summary of findings converted to actionable insights.

---

## 🧰 Tools and Libraries Used

The project utilizes a range of tools and libraries for data analysis and visualization. Here are the key technologies used:

Data Analysis and Manipulation:
- Pandas
- NumPy

Visualization:
- Matplotlib
- Seaborn

---

## ▶️ How to Run the Project

1. Clone the repository:

   git clone https://github.com/Ann-Tonina/Electric-Vehicles-population-2024-Analysis.git
   cd your-repository-directory

2. Install the dependencies:

   python -m pip install --upgrade pip

   Ensure pip is up to date:
  
   Install project dependencies

   pip install -r requirements.txt

3. Launch Jupyter Notebook:

   Run the following command to open the project in Jupyter Notebook:

   jupyter notebook index.ipynb

   Run the cells sequentially to reproduce the analysis and results.

🔍 Data Understanding

Top EV Manufacturers: Tesla dominates the market, followed by Chevrolet and Nissan.

Popular Models: Tesla Model 3 and Model Y are the most registered models.

Electric Range: Most EVs have ranges between 200–350 miles.

Price Distribution: Base MSRP skews higher for premium EV brands, but lower-range options exist.

Geographic Trends: Major urban centers show higher EV adoption due to infrastructure and policy incentives.

Correlation Findings:

Positive correlation between Electric Range and Base MSRP

Newer model years tend to have higher ranges

Slight trend indicating increasing range and affordability over time

## 🔍 Key Insights

### 1. **Trends Over Time (Heatmap Analysis)**
- **Tesla leads** all other makes, especially in model years **2022–2024**, with a dramatic spike in registrations in 2023.
- EV adoption was minimal before 2015 but surged rapidly afterward, indicating growing consumer acceptance and market readiness.

### 2. **Geographic Distribution (Top 10 Counties)**
- **King County** is the dominant hub for EV ownership, followed by **Snohomish**, **Pierce**, and **Clark**.
- There is still room for growth in other counties like **Whatcom**, **Spokane**, and **Benton**.

### 3. **Correlation Insights (Numerical Analysis)**
| Feature Pair              | Correlation |
|--------------------------|-------------|
| Model Year vs. Electric Range | **-0.48** (Moderate Negative) |
| Model Year vs. Base MSRP      | **-0.24** (Weak Negative) |
| Electric Range vs. Base MSRP  | **0.11** (Very Weak Positive) |

- **Newer EVs tend to have lower prices and moderate range**, indicating a trend toward **affordable, mass-market vehicles**.
- The weak correlation between range and MSRP suggests **other factors** (brand, incentives, features) are driving consumer choices.

---

## 📌 Recommendations

### 🔹 For Automakers
- Focus on **affordable EVs** with moderate ranges (~150–250 miles).
- Compete in the **mass-market** segment instead of premium models alone.
- Use county-level data to identify high-demand zones for dealership expansion.

### 🔹 For Local Government & Utilities
- **Expand EV infrastructure** (charging stations, service centers) in **high-adoption counties** (e.g., King, Snohomish).
- Provide **incentives in low-penetration counties** to balance adoption across regions.
- Leverage utility companies to support grid readiness for increased EV demand.

### 🔹 For Policy Makers & Investors
- Promote **diversity of EV makes** to prevent market concentration.
- Invest in **supportive technologies** like batteries, charging infrastructure, and smart grids.
- Offe**tax breaks and grants** targeting not only consumers but also local businesses that switch to EV fleets.

### 🔹 For EV Dealers
- Tailor inventory based on **local county trends**.
- Highlight **total cost of ownership and environmental benefits** to educate hesitant consumers.
- Promote **incentive awareness campaigns** to help buyers benefit from local/state rebates.

## ✅ Conclusion

The EV market in Washington State is expanding rapidly, with Tesla leading adoption, especially in urban centers. A strategic push toward **cost-effective EVs** and improved **regional infrastructure** will ensure continued growth and equitable distribution. Stakeholders should leverage this data to **align offerings with demand**, **optimize policy** and **drive long-term sustainability**.


📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

