# 🤖 Robot-Waiter Café – Market Analysis in Los Angeles

This project explores the viability of launching a **robot-waiter café** in Los Angeles by analyzing open data on restaurants in the city. The goal is to understand the local food service landscape, identify potential opportunities, and assess whether the concept is scalable in the long term — even after the initial novelty wears off.

## 📊 Project Highlights

### 🔍 Data Source
- Dataset: `rest_data_us_upd.csv`
- Contains information on over 17,000 food establishments in Los Angeles:
  - Name, type, address, chain status, and number of seats.

### 🧹 Step 1: Data Preparation
- Checked for missing values and duplicates.
- Converted `chain` column to boolean for clarity.
- Extracted street names from address fields for location-level analysis.

### 📈 Step 2: Exploratory Analysis

#### Establishment Types
- Most common: **restaurants**, **cafés**, **fast food**, and **bakeries**.
- **Bakeries** are 100% chain-operated; cafés and fast food also show strong chain representation.

#### Chain vs. Non-Chain Insights
- Chain establishments have **fewer seats on average** — indicating small, replicable formats are common.
- Non-chains show more variance, often with larger seating capacities.

#### Seating Trends
- **Restaurants and bars** average 40–50 seats.
- **Cafés and bakeries** average under 30 — ideal for compact, tech-enabled layouts.

#### Location Patterns
- Streets like **Wilshire Blvd**, **W Sunset Blvd**, **Hollywood Blvd**, and **S Figueroa St** support a wide range of restaurant sizes — great for flexible or flagship concepts.
- Other streets show a strong preference for smaller establishments — better suited for efficient first locations.
- Over **[insert number]** streets have only one restaurant — potential low-competition entry points.

---

## 💼 Business Insights

- The robot café aligns strongly with the **chain characteristics** of popular food formats in LA.
- A small-format café can be successful in **high-traffic** or **underserved** areas.
- The market data supports both **novelty** and **scalability** — a strong case for investor confidence.

---

## 🛠️ Tools Used
- Python, Jupyter Notebook
- Libraries: pandas, seaborn, matplotlib
