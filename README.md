# Deloitte_Data_Analytics_Internship
## Certificate
- <a href="https://github.com/SandeshReddyGS/Deloitte_Data_Analytics_Internship/blob/main/Deloitte%20Analysis%20Dashboard.png">Certificate</a>
# Task - 1
Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:
Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.
## The reason the client wanted to collect telemetry was to answer 2 questions:
* In which location did machines break the most?
* What are the machines that broke most often in that location?
## Data Sets Required : - <a href="https://github.com/SandeshReddyGS/Deloitte_Data_Analytics_Internship/blob/main/daikibo-telemetry-data.zip">daikibo-telemetry-data</a>
# Task - 2
* Your task is to analyse the telemetry data collected by Daikibo in a software called Tableau.
* Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
* Create a bar chart called “Down Time per Factory”.
* Create a new sheet with a new bar chart called “Down Time per Device Type”.
* Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).
![Deloitte Analysis Dashboard](https://github.com/user-attachments/assets/efad0966-d895-4c53-bae8-f4a8d231c2c2)
- <a href="https://github.com/SandeshReddyGS/Deloitte_Data_Analytics_Internship/blame/main/Tableau%20dashboard%20deloitte.twb">Dashboard file</a>
# Task - 3
After a worrisome number of internal complaints about gender inequality in terms of salary, Daikibo Industrials wants us to help them investigate.
The Forensic Tech team has built an algorithm to quantify “level of gender pay equality” for most job roles within the company, in all company locations. Our Forensics lead thinks it would be a great idea for you to finish the job.
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:
* Factory
* Job Role
* Equality Score (integer; ranging between -100 and +100; 0 is ideal)
## To do:
Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
## Examples:
* 10 → Fair
* -9 → Unfair
* -30 → Highly Discriminative
## The edited version of the file : - <a href="https://github.com/SandeshReddyGS/Deloitte_Data_Analytics_Internship/blob/main/Task%205%20Equality%20Table.xlsx">Equality Table</a>
