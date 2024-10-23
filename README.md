# AtliQ-Grands-Hospitality-Analysis


## Project Overview


AtliQ Grands has noticed a drop in its market share and revenue because of competition and some management choices. This project focuses on bringing the business back to life by using hospitality analytics to help make better decisions.

### Project Goal

This project aims to increase AtliQ Grands' market share and revenue in the luxury hotel sector. The company plans to outshine its competitors and improve management decisions by using data-driven strategies and business intelligence.

**Here is the link to my report**-
https://app.powerbi.com/view?r=eyJrIjoiY2FiZGJkZjgtNjAwMS00MTZhLTg5MDQtZmVhNGZjNDBlODY0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## Data Structure and Data Modeling

The datasets include two types of tables:

**Dimension Tables**: These contain static data, such as customer and product details.

- dim_date
- dim_hotels
- dim_rooms

**Fact Tables**: These contain transaction data.

- fact_aggregated_bookings
- fact_bookings

Here is the data model which follows a STAR SCHEMA
![data model](https://github.com/HritikSundriyal/AtliQ-Grands-Hospitality-Analysis/blob/main/Data%20Model.png)

## Power BI Dashboard Overview:

The dashboard contains Four pages

### **1. Home Page** - This is a landing page where users will arrive the first time they log in. From this home page, they can easily navigate to different sections of the site.

![home page](https://github.com/HritikSundriyal/AtliQ-Grands-Hospitality-Analysis/blob/main/Home%20Page.png)

### 2. Overview Page - Here, you'll find an overview of all the key metrics.

![overview page](https://github.com/HritikSundriyal/AtliQ-Grands-Hospitality-Analysis/blob/main/Overview%20Page.png)



### 3. Revenue & Occupancy Contributors Page (R&O) - This page provides information about revenue and occupancy rates.


![R & 0 page](https://github.com/HritikSundriyal/AtliQ-Grands-Hospitality-Analysis/blob/main/R%20%26%20O%20Page.png)



### 4. Booking & Average Rating Contributors Page (B& AR) - This page tells you about the Bookings and Ratings


![B & AR page](https://github.com/HritikSundriyal/AtliQ-Grands-Hospitality-Analysis/blob/main/B%20%26%20AR%20Page.png)


## Comprehension

### Insights:

- **Revenue:** Mumbai generated the highest revenue at 661M, while Delhi had the lowest at 290.92M.
- **Category Performance:** The Luxury category accounted for 61.62% of total revenue, compared to the Business category, which generated 38.82% of the total revenue (1.69 billion).
- **Occupancy Rates:** Delhi had the highest occupancy percentage at 60.44%, despite having the lowest Daily Sales Revenue per Night (DSRN) at 435. In contrast, Bangalore had the lowest occupancy at 55.68%.
- **Top Property:** AtliQ Exotica is the best performer among all properties, with 316M in revenue, a 57.20% occupancy rate, and a 24.39% cancellation rate.
- **Weekend vs. Weekday Occupancy:** The occupancy percentage on weekends (Friday and Saturday) is 62.6%, higher than on weekdays.
- **Booking Trends:** Mumbai is the leading city for bookings, followed by Hyderabad, Bangalore, and Delhi.
- **Booking Channels:** Most bookings come from other channels, with Makeyourtrip and Logtrip following.
- **Room Class Bookings:** The Elite room class saw the most bookings (49K), followed by the Standard room class (38K).

## Skills learnt from project

### Key Metrics:

- **RevPAR:** Revenue per Available Room  
- **ADR:** Average Daily Rate  
- **DBRN:** Daily Booked Room Nights  
- **DSRN:** Daily Sellable Room Nights  
- **DURN:** Daily Utilized Room Nights  
- **Realization %**  
- **Occupancy %**  
- **Cancellation %**  

**Power BI fundamentals:**

* Data cleaning and Star schema modeling
* Learned about page navigation, tooltip, and conditional formatting.

**Soft skills:**

* Domain knowledge in hospitality










