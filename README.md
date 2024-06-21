# Uk-Rail-Analysis-Project


About this project
I'll play the role of a BI Developer for National Rail, a company that provides business services to passenger train operators in England, Scotland, and Wales.

I've been asked by my manager to create an exploratory dashboard that helps them:

1-Identify the most popular routes 2-Determine peak travel times 3-Analyze revenue from different ticket types & classes 4-Diagnose on-time performance and contributing factors

Data QA and Profiling in Power Query

Data Quality Assurance (QA) and Profiling are critical steps in the data preparation process, ensuring that the data used for analysis is accurate, complete, and reliable. Below are the key aspects and steps involved in performing data QA and profiling in Power Query

Data Profiling
Column Quality: Use Power Query’s data profiling tools to evaluate column quality. This includes checking for:

Error Values: Identify and analyze any errors within columns.

Empty Values: Determine the number and percentage of empty or null values.

Valid Values: Assess the percentage of valid entries.

Column Distribution: Analyze the distribution of data within each column to identify patterns, outliers, and anomalies.

Value Distribution: Review histograms and frequency counts to understand the spread of data values.

Unique Values: Identify the number of unique values in a column to spot duplicates or inconsistencies.

Column Statistics: Examine basic statistics for numeric columns

Min, Max, Average, and Standard Deviation: Provide insights into the range and variability of data.

Count and Distinct Count: Understand the total count and distinct count of values

undefinedundefinedundefined





📉 Delay reasons

I chose only three reasons for further analysis that we can effectively track and monitor, as they are within our control:

1- signal issues

2-technical problems

3-Staff shortages.

undefined

undefined

undefinedundefinedFor the unknown reason of delay no one asked for a refund request!

🟪Technical issues are the primary cause of delays, with 388 refund requests, indicating the urgent need for prompt resolution to minimize disruptions.

🟪Staff shortages lead to 261 refund requests, emphasizing the critical role of adequate staffing levels in maintaining service reliability and customer satisfaction.

🟪Signal failures contribute to 215 refund requests, highlighting the necessity of investing in infrastructure to prevent such issues and improve overall service performance.

🟪The total of 1118 refund requests underscore the substantial impact of delays on passenger dissatisfaction, highlighting the importance of responsive customer service and compensation policies.

🟪Proactive maintenance, improved staffing, and infrastructure upgrades present opportunities to minimize delays, enhance service reliability, and improve overall customer experience and loyalty.

🟪Proactive measures to address common delay reasons mitigate operational risks, improve service quality, and maintain passenger trust and loyalty.

🟪Allocating resources towards addressing delay causes aligns with long-term business sustainability goals, ensuring efficient operations and positive passenger experiences.





![Delays](https://github.com/WALIDHUSSEIN/Uk-Rail-Analysis-Project/assets/119229080/463a6ee8-1faa-4b51-ae0a-7729c70084c3)



Peaks

undefined

Key Insights and Recommendations

Wednesday Peak: Busiest day for both AM and PM peaks.

Extra resources needed to handle demand.

Peak Hours:

PM Peak > AM Peak: More passengers travel during evening hours, suggesting the need for increased evening services.

weekday vs. Weekend:

Weekday Stability: Passenger numbers are stable on weekdays, with a significant drop on Saturday.

Sunday Activity: High passenger numbers on Sunday PM peak, due to leisure activities.

Daily Trends:

Wednesday: Highest passenger counts, mid-week work activities driving demand.

Friday: AM peak like other weekdays, but PM peak significantly lower, indicating early departures or remote work. Sunday: High passenger numbers in the PM, suggesting return from weekend activities.

Resource Allocation: Evening Services: Increase frequency/capacity during PM peaks, especially on Wednesdays and Sundays.

Wednesday Focus:

Ensure smooth operations on the busiest day with adequate services and staff.

Saturday Strategies: Run fewer services or promote to boost ridership on low-demand days.

Strategic planning:

Promotional Campaigns:

Target Friday and Saturday with discounts or events to increase travel. Mid-Week Management: Implement real-time monitoring on Wednesdays to manage high demand. Data-Driven Adjustments: Continuously monitor data to optimize resource allocation and services.

Revenue Insights:AM Peak Revenue: Higher revenue despite fewer passengers, suggesting higher fare/spending per passenger. Monday and Tuesday: Strong AM peak revenues indicate consistent commuter behavior, emphasizing the need for reliable services. Friday Opportunities: Lower PM passenger count but reasonable revenue suggests potential for targeted evening services or promotions.

Delays
undefined

Non-Peak Delays are the Highest: The non-peak period has the highest total delays across the week. This may suggest that operational inefficiencies or reduced staffing during off-peak hours could be contributing factors.

Tuesday and Wednesday have High Delays:Both Tuesday (413) and Wednesday (372) have high delays compared to other days. These might be critical days to investigate underlying issues.

Friday has the Lowest Total Delay:The total delay on Friday is the lowest (290), indicating better operational efficiency or reduced passenger volume.

Recommendations

Investigate Non-Peak Delays:
Since non-peak delays are the highest, it’s essential to examine the root causes. Consider reviewing staffing levels, maintenance schedules, and operational protocols during these times.

2. Focus on High Delay Days: - Conduct a detailed analysis of Tuesday and Wednesday to identify specific problems that could be leading to higher delays. Look into whether specific events, staff shortages, or technical issues are more prevalent these days.

3. Implement Best Practices from Low Delay Days: - Review operations on Fridays to understand why delays are the lowest. Implement similar practices on other days where feasible.

Peak Time Analysis: - While non-peak times show the highest delays, PM peak also has significant delays. Ensuring robust staffing and technical support during these times can help in managing delays better.

Regular Monitoring and Feedback

6. Maintenance Scheduling

Peak Hours Passenger Distribution:

undefined

AM Peak: Highest: London Paddington -> Reading with 1299 passengers.

PM-Peak:PM-Peak: Highest

Underutilized Routes with High Revenue:Route: Liverpool Lime Street -> London Euston Total Passengers: 1097Total Revenue: £113,299This route has moderate passenger numbers but high revenue, suggesting it might be a premium service or have higher ticket prices.

Congestion During Peak Hours: AM Peak Congestion:

London Paddington -> Reading with 1299 passengers.

PM Peak Congestion: Manchester Piccadilly -> Liverpool Lime Street with 1542 passengers.

These routes experience high congestion during peak hours, indicating a potential need for increased service frequency or capacity.

London St Pancras -> Birmingham New Street

Action: Monitor growth and consider adding additional services to meet increasing demand.

Recommendations

Enhance High-Demand Routes:

Routes: Manchester Piccadilly -> Liverpool Lime Street, London Paddington -Reading

Action: Increase the number of trips or add more carriages during peak hours to accommodate high passenger numbers.

Optimize Revenue on High-Value Routes:

Routes: London Kings Cross -> York, Liverpool Lime Street -> London Euston

Action: Evaluate and increase ticket prices, offer premium services, or promote these routes more to leverage their high revenue potential.

Address Peak Time Congestion:Routes: London Paddington -> Reading, Manchester Piccadilly -> Liverpool Lime Street

Action: Implement crowd management strategies, such as staggered boarding times or encouraging off-peak travel through discounts.

Invest in Underutilized but High-Revenue Routes:

Routes: Liverpool Lime Street -> London Euston

Action: Explore ways to attract more passengers, such as marketing campaigns or improving onboard services to justify the higher ticket prices.

Expand Services on Growing Routes:*Routes: London Euston -> Birmingham New Street,

Passenger Behavior:

undefined

Most passengers (87.9%) book their tickets 1 day before or on the same day as the trip. A sizable portion of the revenue (58.3%) comes from same-day bookings.

Revenue Distribution: Same-day tickets generate a higher average revenue per passenger (£30.70) compared to advance bookings (£17.60-£17.65).

Recommendations

Incentivize Early Bookings: Offer discounts or promotions for tickets purchased more than 2 days in advance to encourage early bookings.

Dynamic Pricing Strategy: Implement a dynamic pricing model with prices increasing as the trip date approaches to encourage early bookings and maximize revenue from last-minute purchases.

Marketing Campaigns: Target frequent last-minute bookers with personalized offers or loyalty programs to enhance customer retention.

Service Enhancements for Early Bookers: Provide Perks such as free seat selection, priority boarding, or complimentary services to create a value proposition for booking in advance.

Capacity Management: Optimize fleet and crew management based on booking patterns, ensuring resources are allocated effectively to handle the high volume of last-minute bookings.undefined

