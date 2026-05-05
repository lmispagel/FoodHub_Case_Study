The following is an Exploratory Data Analysis Project using Python of a food delivery business:

Here's a breakdown of what the script covers across the key analytical areas:
Operational KPIs — The script tracks prep time (min 20, avg 27.4, max 35 min), delivery time (avg 24.2 min), and the percentage of orders exceeding 60 minutes total. These are your core service-level metrics.
Revenue KPIs — Question 14 calculates net revenue using a tiered commission model: 25% on orders over $20, 15% on orders $5–$20. This is where the business actually earns its margin, so the ~29% of orders over $20 are disproportionately important.
Customer KPIs — 1,200 unique customers with 698 repeat buyers shows solid retention. The top-5 frequent customer analysis ties directly into a loyalty/discount strategy.
Quality KPIs — The 736 unrated orders (38.8%) is arguably the biggest data quality issue in the whole script. Ratings are essential for the promotional offer logic (Q13), so a high non-response rate undermines that analysis.
Demand KPIs — Weekend vs. weekday order volume, top restaurant rankings, and cuisine preferences all feed into demand forecasting and marketing decisions.
