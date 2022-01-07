# Telecom prepaid plan analytics

### 1. Project description
You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.

You are going to carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. Your job is to analyze clients' behavior and determine which prepaid plan brings in more revenue.

Guiding Question
Which prepaid plan brings in more revenue?
<hr>

### 2. Objective:
Analyze clients' behavior and determine which prepaid plans brings in more revenue
Use analytics to assists the comercial department in making adjustment in advertising budget
Apply Statistical Data Analysis to a real-life analytical case study.
<hr>

### 3. Tools:
`pandas, matplotlib.pyplot, math, numpy, scipy`
<hr>

### 4. Data Source
**Dataframe users (information about subscribers):**
user_id — unique user identificator
first_name — user name
last_name — user last name
age — user age
reg_date — registration date (day, month, year)
churn_date — the date when the user stopped using the services (if there is Nan value, the subscriber was still using the services)
city — city where the user lives
tarif — plan name
**Dataframe calls (информация о звонках):**
id — unique call id
call_date — date of the call
duration — call duration (minutes)
user_id — id of the user who made the call 
**Dataframe messages (information about text messages):** 
id — unique message id
message_date — data when the message was sent
user_id — id of the user who sent the message
**Dataframe internet (information about internet sessions):**
id — unique session id
mb_used — Mb used (for the session)
session_date — data of the internet session
user_id — unique user identification number
**Dataframe tariffs:**
tariff_name 
rub_monthly_fee — monthly payment in rubles
minutes_included — number of minutes included in the plan package 
messages_included — number of messages included in the plan package 
mb_per_month_included — internet traffic included in the plan package 
rub_per_minute — extra minute fee 
rub_per_message — etxra text message fee
rub_per_gb — extra internet traffic fee (per GB)<hr>


