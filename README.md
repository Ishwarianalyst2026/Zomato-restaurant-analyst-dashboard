# Zomato Restaurant Analysis Dashboard 🍽️📊

## 📷 Dashboard Preview

![Power BI Dashboard](images/dashboard.png)

---

## 📊 Key Business Questions Solved

### 🔹 Restaurant Analysis
- Which city has the highest number of restaurants?
- Which cuisines are most popular?
- Distribution of restaurants by price range

### 🔹 Customer Rating Insights
- Average restaurant rating by city
- Relationship between ratings and votes
- High-rated vs low-rated restaurants

### 🔹 Online Delivery Analysis
- Restaurants offering online delivery
- Online delivery availability comparison
- Impact of delivery on ratings

### 🔹 Table Booking Analysis
- Restaurants providing table booking
- Comparison between booking vs non-booking restaurants

### 🔹 Cost & Pricing Analysis
- Average cost for two people
- Restaurant distribution by price range
- Cost vs rating analysis

---

## 🧠 Key Insights
- New Delhi has the highest restaurant count
- Online delivery services are highly popular
- Higher-rated restaurants receive more customer votes
- North Indian cuisine is one of the most common cuisines
- Many restaurants do not provide table booking services

---

## 📈 Dashboard Features (Power BI)
- Interactive slicers (Country, City, Cuisine, Rating)
- KPI cards
- Bar charts & pie charts
- Scatter plot analysis
- Dynamic filtering visuals

---

## 🐍 Python Data Cleaning Highlights
- Removed null values
- Removed duplicate records
- Corrected data types
- Cleaned text values
- Exported cleaned CSV dataset

Example:
```python
import pandas as pd
import numpy as np

df = pd.read_csv("zomato.csv")
df.drop_duplicates(inplace=True)
df.isnull().sum()
```

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Power BI

---

## 📂 Dataset Information
- Total Records: 9548
- Total Columns: 19

---

## 🚀 Project Workflow

Raw Dataset  
➡️ Python Data Cleaning  
➡️ Export Clean CSV  
➡️ Power BI Dashboard  
➡️ Business Insights

---

## 👩‍💻 Author
**Ishwari Prabhune**  
Aspiring Data Analyst | Power BI Enthusiast
