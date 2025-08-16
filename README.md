# ✈️ Flight Price Prediction – EDA & Feature Engineering

This project is based on a Kaggle dataset for **flight price prediction**.  
The main goal is to perform **Exploratory Data Analysis (EDA)** and **Feature Engineering** to clean, analyze, and transform the raw data into a format suitable for predictive modeling.  

This project is inspired by Krish Naik’s tutorial on EDA & Feature Engineering.

---

## 📂 Dataset

- **Source**: [Kaggle – Flight Price Prediction](https://www.kaggle.com/)  
- The dataset contains flight booking details such as:  
  - Airline  
  - Date of Journey  
  - Source & Destination  
  - Route & Duration  
  - Number of Stops  
  - Ticket Price  

---

## 🛠️ Tech Stack / Tools

- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔑 Project Steps

1. **Data Cleaning**
   - Handle missing values  
   - Fix inconsistent data formats  

2. **Feature Engineering**
   - Extract day, month, year from `Date_of_Journey`  
   - Split and process `Arrival_Time` and `Dep_Time`  
   - Convert `Duration` into total minutes  
   - Encode categorical variables (`Airline`, `Source`, `Destination`) using Label Encoding & One-Hot Encoding  

3. **Exploratory Data Analysis**
   - Visualize flight prices across airlines, routes, and number of stops  
   - Identify trends and patterns in ticket pricing  

4. **Data Preparation for ML**
   - Convert categorical variables to numeric  
   - Normalize and prepare features for model training  

---

## 📊 Results / Insights

- **Airline** strongly impacts ticket price (e.g., Jet Airways generally has higher fares).  
- **Number of Stops** is directly proportional to ticket cost.  
- **Departure time** plays a role in pricing (early morning vs. evening).  

---

##  How to Run

Clone the repository and run the notebook:

```bash
# Clone this repository
git clone https://github.com/your-username/flight-price-prediction.git

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
