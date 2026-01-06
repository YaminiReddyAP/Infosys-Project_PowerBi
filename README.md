📊 Election Data Analysis using Power BI
  
   📌 Project Overview

This project focuses on analyzing Indian General Election data and transforming complex election datasets into interactive and insightful Power BI dashboards.
The dashboards enable year-wise, state-wise, party-wise, candidate-wise, and demographic analysis to support data-driven understanding of election trends.

🎯 Objectives

Analyze national and regional election results

Visualize voting trends across multiple years

Compare party and candidate performance

Understand demographic patterns of election winners

Create media-ready, interactive dashboards

🗂️ Dataset Details

Records: ~10,000+

Columns: 20+

Coverage: All Indian states and constituencies

Data includes:

Candidate details

Votes polled & votes secured

Party, state, constituency

Winning margin, gender, age, category

🛠️ Tools & Technologies

Power BI Desktop

Power Query – Data cleaning & preprocessing

DAX – Measures and KPIs

Excel / CSV – Source dataset

📈 Dashboards Developed

Election Overview Dashboard

State-wise Analysis

Party Performance Analysis

Candidate Performance

Year-wise Voting Trends

Winning Analysis

State-wise Map Analysis

Demographic Analysis

📌 Key KPIs

Total Votes Polled

Total Votes Secured

Total Seats

Seats Won

Winning Margin

Vote Share %

Total Candidates & Winners

🧮 Sample DAX Measures
Total Votes Polled = 
SUM('Indian General Election'[Total_Votes_Polled])

Seats Won = 
CALCULATE(
    DISTINCTCOUNT('Indian General Election'[Constituency]),
    'Indian General Election'[Is_Winner] = TRUE()
)

Total Candidates =
DISTINCTCOUNT('Indian General Election'[Candidate Name])

🧪 Testing & Validation

Data accuracy verified against source

DAX calculations validated

Performance optimized for slicers & filters

Cross-page interactions tested

🚀 Future Scope

Integration of sentiment analysis from social media

Mobile-optimized Power BI dashboards

Expansion to local & municipal election data
