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
![Summary 2](https://github.com/user-attachments/assets/93576d5c-abfe-4a34-bd48-debde1a1bb2a)

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
![Bookings 2](https://github.com/user-attachments/assets/44856161-eb14-4402-a4e2-de0e7016946d)

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

## Revenue
![Revenue 4](https://github.com/user-attachments/assets/b938388b-88c1-4b02-a5c7-3949101f2c0e)

### Key Metrics:
1. Total Bookings (Attempted): 12,652
2. Total Successful Booking Value: ₹6,900,234
3. Average Booking Value: ₹545.4

4. Booking Value by Payment mode
  	- Cash: ₹3,821,738 (55.4%)
  	- UPI: ₹2,763,547 (40.0%)
  	- Credit Card: ₹249,494 (3.6%)
  	- Debit Card: ₹65,455 (0.9%)

Insight: Over 95% of revenue comes from Cash and UPI, highlighting a high dependence on instant payment methods.
	 But still Cash Dominates.

### Problem Identification Insights
1. Heavy Dependence on Cash
  	- Cash dominates with 55.4% of revenue.
  	- This increases risk of fraud, reconciliation errors, and poor tracking.
### Suggested Solutions
1. Promote Digital Payments
  	- Offer UPI/Card incentives (discounts, loyalty points).
  	- Use driver training to nudge digital transactions.
2. Analyze Spend Patterns
  	- Understand what ride types these top customers prefer and replicate conditions to convert mid-tier users 
    	  to high-value.


## Cancellations
![Cancelations 5](https://github.com/user-attachments/assets/60f4b8e6-81ac-4eb7-b948-76fc822e2743)

### Key Metrics:
1. Total Bookings: 20,407
2. Successful Bookings: 12,652
3. Total Canceled Bookings: 5,735
4. Bookings Canceled due to Driver Not Found: 2,020
5. Overall Cancellation Rate: 28.10%

- Note: Nearly 3 in every 10 rides are getting canceled, which impacts both customer satisfaction and driver productivity.

### Cancellations by Customer
1. Total Customer Cancellations: 2,081
2. Avg. Customer Arrival Time: 85.18 seconds

- Reasons & Cancelled Rides count:
	- Driver is not moving towards pickup 610 (29.31%)
	- Asked to cancel   - 	552	26.53%
	- Change of plans   -	408	19.61%
	- AC is not working -	320	15.38%
	- Wrong address	    - 	191	9.18%

-Insight: Over 55% of customer cancellations are due to driver-side behavioral or service issues 
	  (not moving, asking to cancel, no AC).

### Cancellations by Driver
1. Total Driver Cancellations: 3,654
2. Avg. Vehicle Arrival Time: 170.64 seconds

- Reasons & Cancelled Rides count:
	- Personal & Car related issue-	1,263	34.56%
	- Customer-related issue    -	1,064	29.12%
	- Customer was coughing/sick-	742	20.30%
	- More than permitted people-	585	16.01%

- Insight: The top reason here is driver personal/car issues, which indicates poor vehicle preparedness and 
 	   weak attendance control. Health concerns and over-capacity are also growing triggers.


### Problem Identification Insights
1. High Cancellation Rate at 28.10% is above industry best practices (which is usually <15%).
2. Driver-initiated cancellations are nearly double compared to customer-initiated — damaging platform trust.
3. Driver not moving and asking customer to cancel are repeat violations that indicate poor compliance or lack of incentive alignment.
4. AC not working and vehicle condition issues point to fleet quality gaps.

### Suggested Solutions

1. Incentive Penalties for Cancellations
	- Penalize drivers who frequently ask customers to cancel or fail to move towards pickup.
	- Reward low-cancellation drivers with performance bonuses.
2. Vehicle & Driver Readiness Audits
	- Mandatory health and vehicle checks before shift starts.
	- Block access if AC or vehicle health isn’t up to mark.
3. Reduce Cancellations Repeated Patterns
	- If a customer or driver has repeated cancellation reasons (like “wrong address” or “more than allowed people”), show pre-alerts or auto-correct addresses.
4. Customer live updates and Feedback
	- Use real-time status tracking to assure customers of movement and estimated pickup time.
	- Introduce an option to report drivers who request cancellation directly in the app.

## Ratings
![Ratings 7](https://github.com/user-attachments/assets/fdb8bf85-345a-4e72-981d-5c028a82e58c)

### Key Metrics:

1. Successful Bookings: 12,652
2. Overall Ratings: 4.0
3. Avg.Customer Arrival Time: 84-86 secs
4. Avg.Driver Arrival Time: 168-172 secs

### Problem Identification Insights
1. Top-Rated Vehicles Like Prime Plus Have Lower Bookings
	- Suggests quality isn’t translating into demand, potentially due to pricing or visibility issues.
2. Arrival Time Gaps Exist (Vehicle vs. Customer)
	- Even a 5–10 second gap at scale can impact driver idle time and customer satisfaction.

### Suggested Solutions
1. Top-Rated Vehicles Are Underbooked
	- Prime Plus and Prime SUV have some of the highest driver ratings but relatively fewer bookings compared to Mini or Auto.
2. Arrival Time Optimization Needed
	- Vehicle arrival times average around 170–172 seconds, while customer arrival times are in the 83–86 second range.
	- While reasonably aligned, the difference between best and worst arrival times is still 9 seconds for vehicles and 3 seconds for customers.
