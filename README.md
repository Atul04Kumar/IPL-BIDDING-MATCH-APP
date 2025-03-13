# 🏏  Pie-in-the-Sky: IPL Bidding App
## 📌 App Overview
Pie-in-the-Sky is a mobile application that allows registered users to legally bid on IPL matches. Users can predict match winners, earn points based on correct predictions, and compete on a leaderboard. Admins manage match rosters, update details, and maintain system functionalities.

---

## 🚀 Features
### 📝 User Registration
##### ✔ New users register with their *mobile number, email ID, and password*.
##### ✔ Registered users can participate in bidding.
---
### 🏏 Match Details
##### ✔ Displays *playing teams, match venue, and current standings* in the points table.
##### ✔ Updates *winner details* after each match.
##### ✔ Updates *team standings* and bidder points.
##### ✔ Sends *notifications* to users when required.
---
### 🎯 Predict Winner
##### ✔ Users predict the *match winner before the toss*.
##### ✔ Bids can be changed *only until the toss occurs*.
##### ✔ Users *cannot see other users' predictions*.
##### ✔ Matches can have *different start times* due to disruptions like rain.
---
### 🏆 Point System
✔ Users *gain points* for correct predictions, but *do not lose points* for incorrect ones.
✔ *Dynamic point allocation* based on team standings:
   - *Tournament Start:* ✅ *2 points* for a correct prediction.
   - *Points Difference ≤ 6:*
     - Predicting *higher-ranked team wins: ✅ **2 points*.
     - Predicting *lower-ranked team wins: ✅ **3 points*.
   - *Points Difference > 6:*
     - Predicting *higher-ranked team wins: ✅ **2 points*.
     - Predicting *lower-ranked team wins: ✅ **5 points*.
---
### 📊 Leaderboard
##### ✔ Users can view their *points and ranking* in real-time.
##### ✔ Displays the *top 3 users* on the leaderboard

---

## 📌 Project Overview  
The *IPL Match Bidding App* is a data-driven system designed to analyze *bidding patterns, match statistics, and team performances* using SQL. This project builds a *relational database* to track *bids, match outcomes, and user performance, enabling insights into **bidding trends, win probabilities, and team strategies*.

---

## 🚀 Features  
✅ *Database Design:* Well-structured *relational schema* ensuring *data integrity* and efficiency  
✅ *SQL Querying:* Advanced *Joins, CTEs, Window Functions, Subqueries* for analytics  
✅ *Match & Bidding Analysis:* Win probabilities, bidder success rates, and team performance evaluation  
✅ *Data Integrity & Optimization:* Implemented *Indexes, Constraints, and Query Optimization* for enhanced performance  

---

## 📊 Database Schema  

The database consists of the following *normalized tables*:  

- *IPL_User* – Stores bidder and admin details.
- *IPL_Bidder_Details* – Contains bidder information, including contact details.
- *IPL_Bidding_Details* – Captures user bids with timestamps and statuses.
- *IPL_Bidder_Points* – Records bidding performance and rankings.
- *IPL_Tournament* – Stores tournament details like name, date range, and team count.
- *IPL_Match* – Tracks match details, including teams, toss winners, and match winners.
- *IPL_Match_Schedule* – Contains match schedules, venues, and timings.
- *IPL_Stadium* – Stores stadium names, cities, capacities, and addresses.
- *IPL_Team* – Maintains details of all participating teams.
- *IPL_Team_Players* – Links players to their respective teams and roles.
- *IPL_Player* – Contains individual player details and performance stats.
- *IPL_Team_Standings* – Maintains tournament standings for each team, including match results and points.


---

## 🛠 ER Diagram
![ER Diagram](https://github.com/Raghavendra317/IPL-Match-Bidding-App/blob/main/ER%20Diagram.png)

## 📌 Key SQL Queries & Insights  

### 🏆 *Bidding & Performance Analysis*  
- *Calculate the win percentage* of each bidder (ranked from highest to lowest)  
- *Track total bids per team* and identify top teams receiving maximum bids  
- *Analyze bidder success rates* and identify patterns in betting behavior  

### 📊 *Match & Toss Impact Analysis*  
- Find *stadium-wise win probabilities* based on toss decisions  
- Identify *teams winning most matches after winning the toss*  
- Extract *top-performing teams and players* based on match outcomes  

### 📈 *Player & Team Insights*  
- List *top 5 all-rounders and bowlers* with highest wickets  
- Calculate *total points for teams across seasons* and *rank teams*  
- Determine *season duration and longest IPL season*  

---

## 🛠 Technologies Used  
✅ *Database:* MySQL  
✅ *SQL Techniques:* *DDL, DML, DQL, Joins, Subqueries, CTEs, Window Functions, Views, Indexing, Query Optimization*  
✅ *Data Visualization:* Power BI / Tableau (for insights presentation)  

---

