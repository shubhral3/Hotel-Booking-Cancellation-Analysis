# 🏨 Hotel Booking Cancellation Analysis

> **"Unlock Booking Behaviors — Plan Smarter, Travel Better"**

This end-to-end data analytics project analyzes hotel booking data to uncover insights, predict booking cancellations, and visualize customer behavior using an interactive Power BI dashboard.

---

## 📌 Problem Statement

Hotels often face large financial losses and operational inefficiencies due to frequent booking cancellations.  
This project aims to:
- **Predict which bookings are likely to be canceled**
- **Understand booking patterns and customer segments**
- **Provide decision-makers with a dynamic dashboard for smarter planning**

---

## 🛠️ Tools & Technologies

| Tool         | Purpose                          |
|--------------|----------------------------------|
| **Python**   | Data Cleaning, Feature Engineering, Machine Learning |
| **Pandas**   | Data manipulation                |
| **Seaborn**  | Exploratory Data Visualization   |
| **Scikit-learn** | Predictive Modeling (Random Forest) |
| **Power BI** | Dashboard creation & storytelling |
| **Jupyter Notebook** | Code execution & explanation |

---

## 🧠 Key Objectives

- Clean and preprocess raw hotel booking data (119K+ rows, 32 features)
- Engineer new features (like `total_guests`, `total_nights`, etc.)
- Train a predictive model to classify bookings as "Canceled" or "Not Canceled"
- Create an interactive Power BI dashboard to explore cancellation trends by:
  - Month
  - Country
  - Market segment
  - Room type

---

## 📈 Machine Learning Approach

- **Target Variable:** `is_canceled` (1 = Canceled, 0 = Not Canceled)
- **Model Used:** Random Forest Classifier
- **Important Features:** Lead time, Deposit type, Customer type, Previous cancellations

---

## 📊 Power BI Dashboard

The dashboard offers:
- Total Cancellation Count, Repeated Guests, and Stay Distribution
- Monthly Cancellation Trends
- Market Segment-wise cancellation
- Country-wise guest distribution
- Room type demand stability

---

## 📂 File Structure

| File | Description |
|------|-------------|
| `Hotel_booking_demand.ipynb` | Data Cleaning, Feature Engineering & ML |
| `cleaned_hotel_bookings.csv` | Cleaned data used for dashboarding |
| `dashboard_screenshot.png` | Preview of Power BI dashboard |
| `README.md` | Project documentation |

---

## 🔍 Key Insights

- **August & July** saw the highest cancellation volumes
- **Online TA** segment had over 50% of cancellations
- **Portugal (PRT)** contributed the highest number of repeated guests
- Guests are more likely to book for **weeknights** than weekends
- **Non-refundable deposits** and long lead times increase cancellation risk

---

## 👥 Who is this project for?

This dashboard and predictive model can benefit:
- **Hotel Revenue Managers**
- **Travel Agencies**
- **Business Analysts in Hospitality**
- **Operations/Forecasting Teams**

---

## 💡 Future Improvements

- Deploy model with a live booking prediction UI (Streamlit)
- Add time-series forecasting for occupancy rate
- Integrate real-time data from booking platforms



