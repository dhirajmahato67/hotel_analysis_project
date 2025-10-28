🏨 Hospitality Data Analysis Project — AtliQ Grands

In today’s competitive hospitality industry, data-driven decision-making has become essential for business growth. This project focuses on AtliQ Grands, a well-established hotel chain in India that operates across Delhi, Mumbai, Bangalore, and Hyderabad. Despite being in the industry for nearly two decades and offering diverse hotel types — from luxurious AtliQ Palace to business-class AtliQ Seasons — the company recently faced a significant decline in revenue and market share due to rising competition.

To address this challenge, AtliQ Grands decided to leverage data analytics to gain insights from its booking database. The data contained crucial information such as customer bookings, revenue, cancellations, and occupancy across various room types and booking platforms (like MakeYourTrip, LogTrip, Tripster, and AtliQ’s own website).


🔍 Step 1: Data Exploration

The project began with a deep dive into the raw datasets to understand the structure, volume, and relationships within the data. Using Pandas and NumPy, I explored key business metrics such as:
1. Identifying unique property IDs in the booking data
2. Calculating total bookings per property
3. Detecting overbooked days (when bookings exceeded room capacity)
4. Finding properties with the highest capacity

This initial exploration helped uncover patterns in hotel operations and provided a foundation for more advanced analysis.


🧹 Step 2: Data Cleaning

Once the data was explored, I focused on improving its quality and reliability.
Using a combination of Pandas functions and statistical imputation, I:

1. Identified missing values and filled them appropriately using mean or median depending on data distribution.
2. Filtered out invalid records, such as cases where successful bookings exceeded total capacity — ensuring the dataset accurately reflected real-world operations.
This step transformed the raw, inconsistent data into a clean, structured dataset ready for analysis.


💡 Step 3: Insight Generation

With a refined dataset, I performed detailed data analysis and visualization using Matplotlib to uncover actionable business insights. Some of the key analyses included:
1. Average Occupancy Rate across different room categories and cities
2. Weekday vs. Weekend performance — identifying when occupancy was higher
3. Monthly trends, such as occupancy in June and revenue patterns month-over-month
4. Revenue realized per city and hotel type, revealing which regions and hotel segments were performing best
5. Average customer ratings across cities, providing a perspective on service quality
6. Pie chart of revenue share by booking platform, helping the business understand which platforms drive the most income

Additionally, I integrated new data for the month of August to simulate a real-world scenario where continuous data inflow demands periodic analysis updates.


📊 Key Business Outcomes

Through this project, I was able to simulate how AtliQ Grands’ management team could:
1. Identify underperforming cities or room types
2. Optimize pricing and marketing strategies based on occupancy trends
3. Improve allocation of rooms across platforms to boost revenue
4. Strengthen partnerships with high-performing booking channels


🧠 Tools & Skills Used

1. Python Libraries: Pandas, NumPy, Matplotlib
2. Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Statistical Imputation, Visualization
3. Domain Knowledge: Hospitality & Revenue Management


🚀 Conclusion

This project demonstrated how data analytics can transform hospitality operations by turning raw booking data into strategic insights. From understanding customer behavior to identifying performance bottlenecks, the analysis empowered AtliQ Grands to make data-informed decisions — a key step toward reclaiming market share and improving profitability in a competitive landscape.
