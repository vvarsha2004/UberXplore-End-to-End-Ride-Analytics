# 🚖 UberXplore-End-to-End-Ride-Analystics – Power BI

An interactive Power BI dashboard that analyzes Uber ride data across multiple vehicle types (Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL) to track **bookings, revenue, trip distances, payment methods, peak travel times, and customer trends.**

---

## 📌 Overview

This project transforms raw ride-booking data into a clean, multi-page Power BI report that helps stakeholders quickly understand business performance — from completed/cancelled/incomplete ride breakdowns to revenue contribution by vehicle type and customer.

**Key headline metrics tracked across the report:**
- 🚗 Completed Bookings
- ⚙️ Lost Bookings
- 💰 Total Revenue
- 📈 Total Distance Travelled
- 📍 Average Distance per Ride
- ⭐ Average Customer & Driver Ratings

---

## 🗂️ Dashboard Pages

### 1. Home Page
Landing page with project description and navigation buttons to all report sections (Overview, Vehicle, Revenue, Rider).

### 2. Overview Page
High-level summary for a selected vehicle type, including monthly booking/revenue trends, top pickup and drop locations, and average customer/driver ratings.

### 3. Vehicle Page
A consolidated table comparing all vehicle types side-by-side — customer count, revenue, completed bookings, contribution %, and a monthly trend sparkline for each.

### 4. Revenue Page
Deep dive into revenue performance — revenue by vehicle type and revenue by customer ID, helping identify top revenue-generating segments and customers.

### 5. Rider Page
Customer-centric view showing revenue by customer ID, payment method distribution (UPI, Cash, Uber Wallet, Credit/Debit Card), and a breakdown of incomplete rides by cancellation source (customer vs. driver).

### 6. Vehicle Detail (Example: Bike)
Each vehicle type has its own detail page with completed/cancelled/incomplete ride breakdowns, monthly bookings and revenue trends, top pickup/drop points, and ratings.

---

## 🛠️ Tech Stack

- **Power BI Desktop** – Data modeling, DAX measures, and report design
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated columns/measures for KPIs (completed %, revenue contribution, ratings, etc.)
