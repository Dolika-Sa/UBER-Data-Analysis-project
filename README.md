# 🚗UBER-Data-Analysis-project

This project presents a comprehensive analysis of Uber ride data from 2016, focusing on identifying usage patterns, user behavior, and key operational insights. The goal is to derive actionable intelligence from trip records to support decision-making and business strategy for ride-hailing services.

# 📊 Project Objectives

- Preprocess and clean the Uber dataset for analysis.
- Visualize trends in ride usage by time, category, and purpose.
- Analyze which types of users book Uber the most and when.
- Identify peak usage periods (daily, weekly, monthly).
- Examine ride distances and infer purpose-specific patterns.

## 📁 Dataset

The dataset contains **1,155 valid entries** and includes the following columns:

- `START_DATE` – Trip start timestamp
- `END_DATE` – Trip end timestamp
- `CATEGORY` – Business or Personal
- `START` – Pickup location
- `STOP` – Drop-off location
- `MILES` – Trip distance
- `PURPOSE` – Reason for the trip

## 📈 Key Findings

### 1. **User Category**
- 100% of rides are marked under the **Business** category.

### 2. **Trip Purpose**
| Purpose               | Percentage |
|------------------------|------------|
| Meeting               | 21.6%      |
| Meal/Entertainment    | 15.5%      |
| Errands/Supplies      | 13.8%      |
| Customer Visit        | 12.9%      |
| Temporary Site Visit  | 10.4%      |

> Majority of rides were business-related travel activities.

### 3. **Peak Booking Hours**
- Most bookings occur during **7–10 AM** and **4–7 PM** (over 60%).

### 4. **Weekly Trends**
- **Thursday and Friday** account for **37%** of all rides.

### 5. **Monthly Trends**
- **March–May** are the most active months.
- **December** has the lowest ride frequency (4.6%).

### 6. **Distance Breakdown**
- 76% of trips are **under 10 miles**, typical for intra-city travel.

---

## 📦 Technologies Used

- **Python** (Pandas, NumPy)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Jupyter Notebook** for analysis and presentation

