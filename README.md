# 🚴‍♂️Divvy Trips 2019
Analyze Cyclistic’s 2019 bike-share data to understand how annual members and casual riders use bikes differently — and provide recommendations to help convert casual riders into members.

## Data Used
<a href="https://divvy-tripdata.s3.amazonaws.com/index.html">Divvy Bike Share System Data (2019 Q1–Q4)</a>
</br>
Used under a public data license for educational purposes.

## Dasboard
<a href="https://app.powerbi.com/groups/4b9c4c99-827a-4dba-b8da-c1541a4cd226/list?experience=power-bi">Healthcare Operations Dasboard</a>
</br>

## 📊 Project Overview
(Google Data Analytics Capstone Case Study) Analyze Cyclistic’s 2019 bike-share data to understand how annual members and casual riders use bikes differently — and provide recommendations to help convert casual riders into members.

## 🧩 Business Task
The marketing director aims to analyze Cyclistic historical trip data to identify how annual members and casual riders use the service differently. The analysis focuses on uncovering actionable insights to drive a new marketing strategy centered on member conversion.


## 🧰 Tools Used
Excel – Data cleaning and preprocessing.
</br>
SQL – Big Data Management, Advanced Filtering and Performance Optimization.
</br>
Power BI – Data modeling, DAX measures, dashboards.
</br>
PowerPoint → Final presentation of insights and recommendations.

## 🧹 Data Cleaning
Identified and removed duplicate trip IDs and handled missing values in station names to prevent skewed counts.
</br>
Converted ride start and end times into standard formats to extract Day of Week, Month, and Time of Day for behavioral analysis.
</br>
Excluded "false starts" (trips under 60 seconds) and maintenance rides (unusually long durations) that do not represent actual customer behavior.
</br>
Created new calculated columns, such as Ride Length (Minutes) and Rush Hour Flags, to identify the "Commuter" vs. "Leisure" segments.
</br>
Cross-referenced totals (e.g., verifying the 3M Member trips) against baseline reports to ensure 100% data accuracy before visualization.

## 📈 Key Insights
The "Commuter Gap" [High Priority]: Casual riders currently only have a 46.74% rush hour usage rate compared to 63.44% for members. Closing this gap represents a prime opportunity to convert casuals who already use the service for work.
</br>
Weekend Peak Engagement [Quick Win]: Casual ridership peaks dramatically on Saturday and Sunday afternoons, with a single high-volume spike of 184K trips at 1:00 PM. This is the optimal window for digital ad spend and influencer marketing.
</br>
The " Duration Discrepancy" [Strategic Adjustment]: Casual riders average 35.29 to 37.28 minutes per ride, nearly 3x longer than the 12.55-minute member average. Marketing the membership as a way to avoid "overage fees" for long rides is a key incentive.
![](https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis-Report/blob/5289b2f4094235bb6b2cbaed7071cbc38c4f525f/Charts/Top%2010%20Routes%20Through%20Rush%20Hours%20By%20Casual.png)
</br>
![](https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis-Report/blob/5289b2f4094235bb6b2cbaed7071cbc38c4f525f/Charts/Total%20Number%20Of%20Trips%20By%20Day%20%26%20Time%20Of%20Day%20By%20Member.png)

## 💡 Recommendations
"Commute for Less" Campaign [High Priority]: Launch targeted digital advertisements at the Top 10 commuter stations. These ads should specifically highlight the cost-savings of an annual membership for the 406,000 casual riders identified as regular weekday commuters.
</br>
Weekend "Lifestyle" Membership [Quick Win]: Introduce a "Weekend-Only" or "Lifestyle" tier promoted by social media influencers at weekend hotspots like Streeter Dr & Grand Ave. Target the peak engagement window of Saturday at 1:00 PM to maximize reach.
</br>
Benefit Education: "Experience More" [Strategic Adjustment]: Leverage the fact that casual riders already average 35–37 minutes per ride. Market the member benefit of longer inclusive ride times (45 mins) to show them how to avoid current overage fees.

## 🧠 Outcome
This analysis provides data-driven insights for Cyclistic’s marketing strategy, emphasizing how understanding rider behavior can help increase membership conversion and long-term engagement.
</br>

---

## 🗂️ Project Structure


Divvy Trips 2019
</br>
README.md
</br>
LICENSE
├── Link |
    └──<a href="https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis-Report/blob/5289b2f4094235bb6b2cbaed7071cbc38c4f525f/Data%20Source/Data%20Source%20Link.txt">Data Source Link.txt</a>
</br>
├── Presentation |
   └── <a href="https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis-Report/blob/5289b2f4094235bb6b2cbaed7071cbc38c4f525f/Document/Divvy%20Trips%202019.pdf">Divvy Trips 2016.pdf</a>
</br>
├── Images |
   └── <a href="https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis-Report/tree/5289b2f4094235bb6b2cbaed7071cbc38c4f525f/Charts">Charts</a>

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---

