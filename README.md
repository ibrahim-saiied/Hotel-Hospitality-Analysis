# Hotel Hospitality Analysis

### Link to [Interactive Dashboard](https://www.novypro.com/profile_about/ibrahim-saiied-1?Popup=memberProject&Data=1740543412374x486468345160050240)

## Introduction
<details>
   <summary><strong>📌 Overview   (click)</strong></summary>
   
   ### Overview
This Power BI project provides a detailed analysis of Lorem Ipsum Group's performance, covering revenue, occupancy rates, booking trends. The analysis aims to uncover insights across various properties and cities, offering data-driven recommendations to enhance revenue generation, optimize occupancy, and improve overall operational efficiency
</details>

<details>
   <summary><strong>📂 Data Sources   (click)</strong></summary>
   
### Data Sources
The primary dataset used for this analysis is the "fact_bookings.csv" file containing detailed information about each booking made by the cusomers

**▼  Dataset Files** [[Download]](https://raw.githubusercontent.com/ibrahim-saiied/Hotel-Hospitality-Analysis/refs/heads/main/Data%20Set.rar)
1. Dim_date File
   - <ins>date</ins> : This column represents the dates present in May, June and July.
   - <ins>mmm yy</ins> : This column represents the date in the format of mmm yy.
2. Dim_hotels File
   - <ins>property_id</ins> : This column represents the Unique ID for each of the hotels.
   - <ins>property_name</ins> : This column represents the name of each hotel.
   - <ins>category</ins> : This column determines which class[Luxury, Business] a particular hotel/property belongs to.
   - <ins>city</ins> : This column represents where the particular hotel/property resides in.
3. Dim_rooms File
   - <ins>room_id</ins> : This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
   - <ins>room_class</ins> : This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.

4. Fact_aggregated_bookings File
   - <ins>property_id</ins> : This column represents the Unique ID for each of the hotels.
   - <ins>check_in_date</ins> : This column represents all the check_in_dates of the customers.
   - <ins>room_category</ins> : This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
   - <ins>successful_bookings</ins> : This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
   - <ins>capacity</ins> : This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.
5. Fact_bookings File
   - <ins>booking_id</ins> : This column represents the Unique Booking ID for each customer when they booked their rooms.
   - <ins>property_id</ins> : This column represents the Unique ID for each of the hotels
   - <ins>booking_date</ins> : This column represents the date on which the customer booked their rooms.
   - <ins>check_in_date</ins> : This column represents the date on which the customer check-in(entered) at the hotel.
   - <ins>check_out_date</ins> : This column represents the date on which the customer check-out(left) of the hotel.
   - <ins>no_guests</ins> : This column represents the number of guests who stayed in a particular room in that hotel.
   - <ins>room_category</ins> : This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
   - <ins>booking_platform</ins> : This column represents in which way the customer booked his room.
   - <ins>ratings_given</ins> : This column represents the ratings given by the customer for hotel services.
   - <ins>booking_status</ins> : This column shows whether the customer cancelled their booking [Cancelled], completed their stay [Checked Out], or did not show up [No show].
   - <ins>revenue_generated</ins> : This column represents the amount of money generated by the hotel from a particular customer.
   - <ins>revenue_realized</ins> : This column shows the final revenue for the hotel based on the booking status. If cancelled, 40% is refunded to the customer; if Checked Out/No show, the hotel keeps the full amount.
</details>

## Case Study
Lorem Ipsum Group owns multiple hotels across Egypt. Due to strategic moves from other competitors and ineffective decision-making, Lorem Ipsum are losing its market share.
They need to provide them insights from their historical data and Create a dashboard according to the data provided by stakeholders form the last 3 months in 2022.

## Process
1) Explore, understand and validating all data.
2) Importing and clean data and Adding some columns to aid in data analysis, such as a column to identify the day type weekend or weekday with power query. 
3) Data modeling
4) Creating Measures using DAX
5) Creating the Dashboard

## Measures
;
<img src="https://github.com/user-attachments/assets/cb3a363e-c8ab-48dd-927b-0d9092c9ef8f" alt="image" width="30%" height="50%" style="display: block; margin: 0;">

## Data Model
![image](https://github.com/user-attachments/assets/05a73c82-d1ea-44e2-bda2-58739c0c8f91)

## Dashboard
![file_2](https://github.com/user-attachments/assets/98de9529-d1af-4518-a918-48f9cb60a34a)


## Insights & Recommendations
1) **City Performance**
   - Hurghada is the highest in revenue, while Cairo However has high occupancy, suffers from many cancellations. It’s important to find out why Cairo has so many cancellations.

2) **Elite Customers**
   - Need to focus more on Elite customers because they drive the revenue boost, and it has the highst cancelation should be prioritized more as it has the highest influence on revenue
(like better communication or flexible booking options)

3) **Trend Changes**
   - Revenue, bookings, and cancellations started decreased on July 10, 2022, then decreased notably on July 26, 2022. This suggests something changed during that period, so further investigation is needed.

4) **Lorem Seasons**
   - Lorem Seasons is earning much less revenue compared to others. Enhancing its marketing strategy could improve its performance.









