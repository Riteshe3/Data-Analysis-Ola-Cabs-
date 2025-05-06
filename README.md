# Data-Analysis-Ola-Cabs-
Ola dashboard offers a visually vibrant, data-rich overview of performance. With 12,652 successful rides and ₹6.9M in revenue, the platform maintains a strong 4.0 rating across vehicles. Sleek charts highlight booking trends, top customers, and punctual service—reflecting reliable, customer-focused operations

### Dataset: 
- <a href = "https://github.com/Riteshe3/Data-Analysis-Ola-Cabs-/blob/main/Bookings-20000-Rows.xlsx">Ola Cabs Data</a>

### Dashboard Link :  
- <a href = "https://github.com/Riteshe3/Data-Analysis-Ola-Cabs-/blob/main/Bookings-20000-Rows.xlsx">Ola Cabs PowerBi Dashboard</a>

## Dashboard cover
![Ola Dashboard 1](https://github.com/user-attachments/assets/af176968-9868-4600-baae-3c9f1e766a86)

## Problem Statement

The Primary objective is to analyze and visualize the operational and Performance Data of Ola Cabs Business.
The Dataset consist of booking records with multiple vehicle type including Auto, Bike, e-Bike, Mini, PrimePlus,
Prime Sedan, Prime SUV, spread across various locations and time periods.
This Power Bi Dashboard focuses on analyzing, Visualizing, which further helps in unclocking insights that could
drive strategic improvements.

1. Cancellation Rates: Out of 20,407 Total Bookings, 5,735 Bookings were cancelled. Hence Cancellation rate is
around (28.10%). There bookings are cancelled either by driver or customer, with key reason being "Driver not
moving","Change of plans", "Customer related issues".

2. Long Arrival Timings: The average vehicle arrival time is 170.64 seconds, with some regions reporting even
higher delays, causing dissatisfaction and drop-offs in customer retention.

3. Revenue Gaps by Payment Mode: A large proportion of revenue comes from cash payments (3.8k), digital modes
like UPI, Credit/Debit card still lags, indicating comparative low digital adoption or technical issues.

& More.

This Power BI dashboard was developed to analyze and visualize these key metrics, providing actionable insights
to help Ola optimize performance and enhance the customer experience.

## Summary
![Summary 2](https://github.com/user-attachments/assets/bcb76e6a-7155-463c-924a-555ceb4a5fe5)

### Key Metrics:
- Total Bookings: 20,407
- Total Bookings Value: 6,900,234
- Booking Status Breakdown:
  - Sucessfully Bookings: 62% = 12,653 Bookings
  - Cancelled by Driver: 17.9% = 3,657 Bookings
  - Cancelled by Customer: 10.2% = 2,080 Bookings
  - Driver not Found: 9.9% = 2,015 Bookings
- Ride Volume Over Time: Bookings Fluctuate between 645 to 700, with noticeable dips around 16-17 July and 
25-27 July.

### Problem Identification Insights
1. High Cancellation Rate:
  	- Nearly 38% of all bookings failed, which is a major issue.
  	- Driver side Cancellations (17.9%) are the biggest contributor and need immediate attention.
2. Supply & Demand Gap
  	- 9.9% failure rate due to "Driver Not Found" indicates Potential Shortage of Drivers during certain hours.
3. Fluctuating Ride Volume:
  	- While the system makes moderate consistency, noticable dips suggests opportunities for deeper analysis, 
    	  possibly due to Technical issues or Drop in Demand.

### Suggested Solutions
1. Reduce Driver Cancellations:
  	- Introduce penalty or incentive structures for consistent driver behavior.
	- Provide better ride matching logic to avoid long pickup distances which often lead to cancellations.
2. Improve Driver Allocation Algorithms:
  	- Use historical booking patterns to predict peak hours and proactively assign standby drivers.
  	- Focus on under-served zones using geo-location heat maps (possibly shown in further slides).
3. Enhance User Trust and Feedback:
  	- Add a reason-for-cancellation capture feature to get qualitative data.
  	- Use insights to design interventions such as:
		- Re-engagement offers for canceled bookings.
	  	- Priority matching for repeat users.

4. Analyze and Prepare for Booking Dips:
  	- Correlate booking dips with external events (e.g., weather, holidays) or system performance.
  	- Implement targeted marketing or surge driver supply in advance.

## Bookings
![Bookings 2](https://github.com/user-attachments/assets/1e9c97f4-db62-4877-98d2-222a0ffd1fe2)

### Key Metrics:
1. Total Successful Bookings: 12,652
2. Total Booking Value: ₹6,900,234
3. Average Booking Value: ₹545
4. Sum Ride Distance: 289,000 km
5. Average Ride Distance: 14.16 km
6. Average Arrival Time: 170.64 seconds (~2.85 minutes)

### Booking Status Breakdown
1. Success: 62% → 12,652 bookings
2. Cancelled by Driver: 17.91% → ≈3,654 bookings
3. Cancelled by Customer: 10.2% → ≈2,081 bookings
4. Driver Not Found: 9.9% → ≈2,020 bookings

### Problem Identification Insights
1. Driver Cancellations are High: Nearly 18% of bookings are canceled by drivers — that’s 3,654 lost trips, impacting both customer experience and revenue.
2. Significant Booking Losses from "Driver Not Found": Over 2,000 bookings failed due to no driver being available — likely due to driver unavailability during peak hours or sparse locations.
3. Only 62% of Users Complete Bookings: A large share of traffic does not convert into successful rides.
4. Arrival Time is Fair but Optimizable: 2.85 minutes is competitive, but further reduction can help improve conversion rate and reduce customer cancellations.

### Suggested Solutions

1. Tackle Driver Cancellations
  	- Use driver behavior analytics to flag repeat cancelers.
2. Expand Supply in Under-Served Zones
  	- Target locations with high “Driver Not Found” rates with driver onboarding or repositioning strategies.
3. Minimum Fare Adjustments
  	- Consider minimum fare thresholds for short-distance rides to protect margins.
4. Customer Engagement for Recovery
  	- Auto-retry or reallocation mechanisms for failed bookings to recover otherwise lost revenue.
5. Optimize Arrival Time with AI
  	- Improve pickup time predictions using real-time traffic, weather, and demand patterns
