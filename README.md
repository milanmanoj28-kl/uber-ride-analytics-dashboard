# Uber Ride Analytics Dashboard (Power BI)

An interactive Power BI dashboard analyzing Uber ride booking data, covering completed vs. lost bookings, revenue trends, vehicle-type performance, pickup/drop locations, and customer/driver ratings.

## Dashboard Preview

<img width="3300" height="2550" alt="Uber Dashboard_page-0001" src="https://github.com/user-attachments/assets/383f595b-8ec6-45d0-99e1-58a0c623a486" />

<img width="3300" height="2550" alt="Uber Dashboard_page-0002" src="https://github.com/user-attachments/assets/6f7897b1-2fdb-40c6-bc96-cb099e52e969" />


## Overview

This project visualizes ride-hailing operations data to surface booking performance, revenue by vehicle category, and service quality metrics at a glance. The dashboard is filterable by vehicle type (Auto, Bike, eBike, Go Mini, Go Sedan, Premier) and supports both monthly and quarterly views.

## Key Metrics

- **93K** Completed Bookings
- **57K** Lost Bookings (cancelled)
- **52M** Total Revenue
- **24.64 km** Average Distance per Ride
- **2.51M km** Total Distance Covered

## Features

- **Booking Status Breakdown:** Radial charts for Completed, Cancelled, and Incomplete rides
- **Vehicle Type Filter:** Auto, eBike, Go Sedan, Bike, Go Mini, Premier
- **Trend Analysis:** Monthly booking trend line and monthly revenue bar chart, toggle between Month/Quarter views
- **Revenue by Vehicle:** Horizontal bar comparison across all vehicle categories (Auto leads at 13M)
- **Location Insights:** Top pickup location (Khandsa) and top drop location (Ashram) by completed bookings
- **Ratings Overview:** Aggregated Customer and Driver ratings

## Tools & Techniques

- **Power BI Desktop** — data modeling, visuals, report layout
- **DAX** — calculated measures and KPIs
- **Power Query** — data cleaning and transformation

## Insights

- Auto is the highest revenue-generating vehicle category, followed by Bike and Go Mini
- Lost bookings account for a notable share (~38%) of total bookings, highlighting a cancellation trend worth investigating
- Khandsa and Ashram emerge as the top pickup and drop hubs respectively

## Dataset

Sourced externally (shared dataset used for Power BI practice/learning purposes).

## File Structure
