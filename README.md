# 🏨 Hotel Booking Cancellation Analysis

## 📌 Project Overview

This project analyzes hotel booking data to understand reservation cancellations and identify patterns that may affect hotel revenue.

The analysis focuses on *City Hotel* and *Resort Hotel*, examining reservation status, average daily rate (ADR), monthly booking patterns, customer origin, and booking channels.

The goal is to identify key cancellation patterns and provide business recommendations that can help hotels improve revenue and reduce cancellations.

---

## 🎯 Business Problem

City Hotel and Resort Hotel are experiencing high booking cancellation rates, resulting in reduced revenue and inefficient utilization of hotel rooms.

This project aims to:

- Analyze hotel reservation cancellations
- Identify factors associated with cancellations
- Compare booking and cancellation patterns between hotel types
- Analyze pricing patterns using Average Daily Rate (ADR)
- Identify months and countries with higher cancellation levels
- Provide data-driven business recommendations for pricing and promotions

---

## ❓ Research Questions

1. What variables affect hotel reservation cancellations?
2. How can hotel reservation cancellations be improved?
3. How can hotels use the analysis to make pricing and promotional decisions?

---

## 🛠️ Tools & Technologies

- *Python*
- *Pandas* – Data manipulation and analysis
- *NumPy* – Numerical operations
- *Matplotlib* – Data visualization
- *Jupyter Notebook* – Analysis and visualization

---

## 📊 Analysis Performed

The project explores:

- Overall reservation status
- Cancellation percentage
- Reservation status by hotel type
- Average Daily Rate (ADR)
- Monthly reservation and cancellation trends
- ADR by month
- Countries with the highest number of cancellations
- Booking sources / market segments
- ADR comparison between cancelled and non-cancelled reservations

---

## 🔍 Key Findings

### 1. Cancellation Rate

Approximately *37% of reservations were cancelled*, representing a significant portion of bookings and potentially affecting hotel revenue.

### 2. City vs Resort Hotels

City Hotels have a higher number of bookings compared with Resort Hotels.

### 3. Monthly Booking Patterns

*August* has the highest number of both confirmed and cancelled reservations.

*January* has the highest number of cancelled reservations according to the analysis.

### 4. Pricing & Cancellations

The analysis shows an association between *higher Average Daily Rates (ADR) and cancelled reservations*. Cancelled reservations generally have higher ADR values than non-cancelled reservations.

### 5. Country Analysis

*Portugal (PRT)* has the highest number of cancelled reservations among the countries analyzed.

### 6. Booking Sources

The analysis shows that approximately:

- *46%* of clients come through online travel agencies
- *27%* come through groups
- *4%* book directly

---

## 📈 Visualizations

The project includes visualizations covering:

- Reservation status
- Reservation status by hotel type
- Average Daily Rate by hotel type
- Monthly reservation status
- Monthly ADR
- Countries with the highest cancellations
- ADR comparison between cancelled and non-cancelled reservations

---

## 💡 Business Recommendations

Based on the analysis, the report recommends:

1. *Optimize pricing strategies* and consider discounts where appropriate to reduce cancellations associated with higher prices.

2. *Offer reasonable discounts during weekends and holidays*, particularly for Resort Hotels.

3. *Run marketing campaigns during January*, when cancellation levels are highest.

4. *Improve hotel services and quality*, particularly in Portugal, where the analysis shows the highest number of cancellations.

---

## 📂 Project Structure

```text
Hotel-Booking-Cancellation/
│
├── Data Analysis (Hotel Booking).ipynb
├── hotel_bookings 2.csv
├── Report.pdf
└── README.md
