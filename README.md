
# Hotel Booking Analysis

## Problem Statement

This project analyzes a hotel booking dataset to understand customer behavior and booking patterns. The dataset contains booking information for **City Hotels and Resort Hotels**, including details such as booking date, number of guests, length of stay, meal type, parking spaces, and more. The aim is to explore the data and identify important factors that affect hotel bookings.

## Business Objective

The objective of this project is to analyze booking data of City Hotels and Resort Hotels and gain insights about the factors that influence bookings and hotel business performance.

## Project Summary

* The dataset contains **119,390 rows and 32 columns**.
* The data includes three data types: **object, float64, and int64**.
* The dataset contains **missing values and duplicate records**.
* Missing values were handled and **31,994 duplicate rows were removed**.
* The columns **Company, Agent, Country, and Children** had missing values, with the highest missing values in the **Company** column.
* Data preprocessing included **data collection, data cleaning, and exploratory data analysis (EDA)**.
* Basic functions like **head(), tail(), info(), describe(), and columns()** were used to explore the dataset.
* New columns **total_people** and **total_stay** were created.
* Rows where the total number of guests (adults + children + babies) was **0 were removed**.
* The column **reservation_status_date** was converted from object type to **date format**.
* Missing values were handled using **fillna()** before performing data visualization.
* Various charts and graphs were used to understand the patterns and trends in hotel bookings.

## Solution to Business Objective

The analysis helped identify several useful insights for hotel businesses:

* Identify months with **high booking and revenue**.
* Understand **preferred room types and meal types**.
* Analyze **optimal stay length** of guests.
* Study **customer preferences such as parking spaces and facilities**.
* These insights help hotels improve **planning, customer satisfaction, and revenue growth**.
* Hotels can also improve service quality by **taking guest feedback and offering promotions to repeat customers**.

## Conclusion

* **City Hotels are more preferred** than Resort Hotels.
* **Average Daily Rate (ADR)** is higher in City Hotels.
* Guest stay length is **directly related to ADR and revenue**.
* Only **3.9% guests are repeat customers**, meaning retention is low.
* **Most guests (91.6%) do not require parking spaces**.
* **BB (Bed & Breakfast)** is the most preferred meal type.
* **July and August** have the highest number of bookings.
* **TA/TO (Travel Agents/Tour Operators)** is the most used booking channel with **79.1% bookings**.
* Around **27.5% of bookings are canceled**.
* **Room type A** is the most preferred room type.

---

If you want, I can also **make this even better for GitHub (with emojis, sections, and formatting so recruiters like it more)**.
