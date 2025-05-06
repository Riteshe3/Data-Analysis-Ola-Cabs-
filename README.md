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

###Key Metrics:
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

