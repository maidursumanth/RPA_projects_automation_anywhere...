Automated Email Reminder System : <br>

📌 Project Overview<br>

This project is an RPA solution developed using Automation Anywhere A360 to automate email reminders based on data stored in Google Sheets.<br>
The bot checks records in a sheet, identifies pending entries based on date conditions, and automatically sends reminder emails when criteria are met.<br>
This project simulates a real-world business follow-up system.<br>

🎯 Objective<br>

To automate manual follow-up emails by:<br>
Reading data from Google Sheets<br>
Checking reminder status<br>
Calculating date differences<br>
Sending automated emails<br>
Updating the sheet after sending<br>

🛠 Tools & Technologies Used<br>

Automation Anywhere A360 (Community Edition)<br>
Google Sheets Integration<br>
Email Automation<br>
Date & Time Operations<br>
Conditional Logic<br>
Loops<br>

🔄 Workflow<br>

Connect to Google Sheets<br>
Retrieve multiple rows of data<br>
Loop through each record<br>
Check if status is "Pending"<br>
Calculate difference between current date and record date<br>
If difference exceeds defined limit (e.g., 2 days)<br>
Send reminder email automatically<br>
Update status to "Email Sent"<br>
Save changes<br>

📊 Business Logic Example<br>

If Status = Pending<br>
AND Days Difference > 2<br>
→ Send Email Reminder<br>
Otherwise → Skip Record<br>

🚀 Skills Demonstrated<br>

Data-driven automation<br>
API / Cloud sheet integration<br>
Date calculation logic<br>
Conditional processing<br>
Loop-based automation<br>
Process automation design<br>

📂 Files Included<br>

automated_email_system.csv – Exported bot file<br>
sample_sheet.xlsx – Sample Google Sheet structure<br>
Screenshots – Workflow preview<br>

💡 Learning Outcome<br>

This project strengthened my understanding of:<br>
Real-time automation scenarios<br>
Automating follow-up workflows<br>
Handling structured data<br>
Building practical RPA business use cases<br>

📸 Screenshots <br>

![Email Reminder Workflow](Automated_email_system.png)

