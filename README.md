# 🏨 Hotel Booking Analytics Dashboard

> An end-to-end data analysis project built in **Microsoft Excel**, exploring **119,390 hotel reservations** across City and Resort Hotels (2015–2017). The project uncovers cancellation patterns, guest behaviour, room performance, and seasonal demand — presented through an interactive dashboard.

---

## 📸 Dashboard Preview

![Hotel Performance & Cancellation Analysis Dashboard](https://img.shields.io/badge/View-Dashboard_Overview-blue?style=for-the-badge&logo=microsoftexcel)](Hotel-Booking-Analytics/Dashboard_Screenshots/Dashboard_Overview.png)

---

## 📊 Pivot Table Summary

![Pivot Tables](https://img.shields.io/badge/View-Booking_Analysis-blue?style=for-the-badge&logo=microsoftexcel)](Hotel-Booking-Analytics/Dashboard_Screenshots/booking_analysis.png)

---

## 🎯 Project Objective

Hotels lose significant revenue due to booking cancellations and unmatched room assignments. This project analyses **3 years of reservation data** to answer:

- Which hotel type has the highest cancellation rate?
- Who are the most frequent guests — and who cancels the most?
- Which months drive peak demand and highest cancellations?
- Does getting your preferred room affect cancellation behaviour?

---

## 🗂️ Dataset Overview

- **Source:** Real-world hotel demand dataset (publicly available)
- **Total Records:** 119,390 bookings
- **Period Covered:** 2015 – 2017
- **Hotels:** City Hotel & Resort Hotel

| Column | Description |
|---|---|
| `hotel` | Hotel type (City Hotel / Resort Hotel) |
| `is_canceled` | Booking cancelled? (0 = No, 1 = Yes) |
| `arrival_date_year` | Year of guest arrival |
| `arrival_date_month` | Month of guest arrival |
| `adults` / `children` / `babies` | Guest composition |
| `country` | Guest's country of origin |
| `reserved_room_type` | Room type requested at booking |
| `assigned_room_type` | Room type actually given |
| `reservation_status` | Outcome — Check-Out, Canceled, or No-Show |
| `room_status` | Did assigned room match request? (Desired / Un-Desired) |
| `guest_status` | Guest group type (Couples / Family / Single) |

---

## 💡 Key Insights

### 🏨 1. Hotel Performance
| Hotel | Total Bookings | Cancellations | Cancellation Rate |
|---|---|---|---|
| City Hotel | 79,330 | 33,102 | **41.7%** |
| Resort Hotel | 40,060 | 11,122 | **27.8%** |

> City Hotel drives **66% of all bookings** but suffers a cancellation rate nearly **1.5× higher** than Resort Hotel — a key revenue risk.

---

### 👥 2. Guest Segment Analysis
| Guest Type | Total Bookings | Cancellations | Cancellation Rate |
|---|---|---|---|
| Couples | 81,560 | 32,424 | **39.8%** |
| Single | 22,577 | 6,555 | **29.0%** |
| Family | 15,253 | 5,245 | **34.4%** |

> **Couples** are the largest segment at **68% of all bookings**, but also account for the majority of cancellations — making them a high-priority segment to retain.

---

### 🛏️ 3. Room Satisfaction vs. Cancellations
| Room Outcome | Total Bookings | Cancellations |
|---|---|---|
| Desired (room matched) | 104,473 | 43,422 |
| Un-Desired (room didn't match) | 14,917 | 802 |

> Surprisingly, guests who received their **preferred room still cancelled far more** than those who didn't — indicating cancellations are driven by external factors (price changes, travel plans) rather than room dissatisfaction.

---

### 📅 4. Monthly Demand & Seasonality
| Month | Total Guests | Cancellations |
|---|---|---|
| January | 5,929 | 1,807 |
| February | 8,068 | 2,696 |
| March | 9,794 | 3,149 |
| April | 11,089 | 4,524 |
| May | 11,791 | 4,677 |
| June | 10,939 | 4,535 |
| **July** | **12,661** | **4,742** |
| **August** | **13,877** | **5,239** |
| September | 10,508 | 4,116 |
| October | 11,160 | 4,246 |
| November | 6,794 | 2,122 |
| December | 6,780 | 2,371 |

> **August is peak season** with 13,877 guests. **January is the slowest month** with just 5,929 — less than half of August. Cancellations also peak in summer, suggesting high-demand months attract more speculative bookings.

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Application |
|---|---|
| **Microsoft Excel** | Data cleaning, analysis, and dashboard creation |
| **Pivot Tables** | Aggregating data by hotel type, guest segment, room status, and month |
| **Excel Charts** | Bar charts and pie charts for visual storytelling |
| **Dashboard Design** | Interactive slicer (Year filter: 2015–2017) for dynamic filtering |
| **Data Analysis** | Cancellation rate calculation, trend identification, segment comparison |

---

## 📂 Project Structure

```
Hotel-Booking-Analytics/
│
├── Dashboard%20Screenshots/
│   ├── Dashboard_Overview.png               # Main dashboard screenshot
│   └── Pivot_Tables.png                     # Pivot table screenshot
├── Hotel_Booking_Analytics_Dashboard.xlsx   # Full workbook: raw data + pivot tables + dashboard
└── README.md                                # Project documentation
```

---

## 🚀 How to Open & Explore

1. Download `Hotel_Booking_Analytics_Dashboard.xlsx` and open in **Excel 2016 or later**
2. Go to the **`Dashboard`** sheet — use the **year slicer** (2015 / 2016 / 2017) to filter all charts dynamically
3. Visit the **`pivot`** sheet to explore the underlying summary tables
4. The **`hotel_bookings`** sheet holds the full raw dataset — filter, sort, or build your own analysis

---

## 🔮 Future Scope

- 🐍 Migrate to **Python** (pandas + seaborn) for statistical depth and automation
- 💰 Add **ADR (Average Daily Rate)** and revenue impact analysis
- 📊 Rebuild as an interactive **Power BI or Tableau** dashboard
- 🤖 Build a **cancellation prediction model** using logistic regression or decision trees

---

## 👤 About

This project was built as part of a data analytics portfolio to demonstrate skills in **data cleaning, pivot analysis, dashboard design, and business insight generation** using real-world hospitality data.

Feel free to connect or reach out on [LinkedIn](#) if you'd like to discuss this project!

---

## 📄 License

Open for educational and portfolio use. Dataset adapted from publicly available hotel booking demand data.
