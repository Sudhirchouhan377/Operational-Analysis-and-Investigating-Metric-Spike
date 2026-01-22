# Operational Analytics and Investigating Metric Spikes

Operational Analytics plays a pivotal role in modern data-driven organizations, enabling companies to move beyond static reporting toward **real-time, actionable intelligence**.  
The core objective of this project is to **investigate anomalies and metric spikes** across diverse operational areas, with a focus on identifying underlying drivers and providing strategic recommendations to enhance business performance.

The project covers areas such as **user engagement, sales performance, marketing effectiveness**, and more.  
You’ll be provided with datasets containing **user information, events data, and email engagement details**.

---

## Dataset Overview

### `job_data` with the following columns:
- `job_id`: Unique identifier of jobs  
- `actor_id`: Unique identifier of actor  
- `event`: The type of event (`decision`, `skip`, `transfer`)  
- `language`: The language of the content  
- `time_spent`: Time spent to review the job in seconds  
- `org`: The organization of the actor  
- `ds`: The date in the format `yyyy/mm/dd` (stored as text)  

### `users`
Contains one row per user, with descriptive information about that user’s account.

### `events`
Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).

### `email_events`
Contains events specific to the sending of emails.

---

##  Case Study 1: Job Data Analysis
Worked with the **`job_data`** table, investigating job-related metrics.  
Key tasks include:
- **Jobs Reviewed Over Time** → Calculated the number of jobs reviewed per hour for each day in November 2020  
- **Throughput Analysis** → Calculated the 7-day rolling average of throughput (number of events per second)  
- **Language Share Analysis** → Calculated the percentage share of each language in the last 30 days  
- **Duplicate Rows Detection** → Identified duplicate rows in the data  

---

## Case Study 2: Investigating Metric Spikes
Worked with **`users`, `events`, and `email_events`** tables.  
Key tasks include:
- **Weekly User Engagement** → Measured the activeness of users on a weekly basis  
- **User Growth Analysis** → Analyzed user growth over time for a product  
- **Weekly Retention Analysis** → Measured retention of users on a weekly basis after signing up  
- **Weekly Engagement Per Device** → Measured weekly engagement segmented by device  
- **Email Engagement Analysis** → Analyzed user engagement with email services  

---

## Summary of Findings
- Detailed results are available here:  
  [Case Study 1 & Case Study 2 Report](https://github.com/Sudhirchouhan377/Operational-Analysis-and-Investigating-Metric-Spike/blob/main/report/case__study_1%20&%20case_study_2)

---

## Author
- **©2025 Sudhir Chouhan**  
- [LinkedIn Profile](https://www.linkedin.com/in/sudhir-chouhan2663/)  

