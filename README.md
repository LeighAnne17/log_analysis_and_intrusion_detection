🔐 Log Analysis & Intrusion Detection
📌 Project Overview

Cyberattacks often start quietly with repeated login failures, suspicious IP addresses or abnormal access patterns hidden inside logs.

This project focuses on analyzing authentication logs to identify potential security threats, such as brute-force attacks and abnormal login behavior.
It demonstrates how Python and data analysis techniques can be used to support real-world cybersecurity monitoring and incident detection.

This project was built as part of my cybersecurity-focused data science portfolio, showcasing practical analysis skills rather than theory alone.

-----------------------------------------------------------------------------------------

🎯 Objectives

Analyze authentication logs for suspicious activity

Identify users and IP addresses with abnormal failed login behavior

Visualize login trends over time

Apply basic anomaly detection techniques

Present findings in a clear, professional, and security-focused manner

-----------------------------------------------------------------------------------------

🧠 Key Cybersecurity Concepts Demonstrated

Log analysis

Brute-force attack detection

Anomaly detection

Security monitoring fundamentals

Threat pattern identification

Data-driven security insights

------------------------------------------------------------------------------------------

🛠️ Tools & Technologies

Python

Pandas & NumPy – data processing

Matplotlib & Seaborn – visualization

Google Colab – interactive analysis environment

CSV Authentication Logs – simulated real-world dataset

-----------------------------------------------------------------------------------------

📂 Dataset Description

The dataset simulates authentication logs commonly found in enterprise systems.

Key Fields:

timestamp – login attempt time

username – user account attempting access

ip_address – source IP of login attempt

status – Success or Failed login

location – country of origin

The dataset includes repeated failed login attempts to simulate potential attack behavior.

-----------------------------------------------------------------------------------------

📊 Analysis Performed
✔ Exploratory Analysis

Dataset structure and quality checks

Success vs failed login distribution

✔ Security-Focused Insights

Users with the highest number of failed logins

IP addresses associated with repeated failures

Login activity trends over time

✔ Anomaly Detection

Statistical thresholding to flag users with unusually high failed login attempts

Identification of accounts that may require security intervention

-----------------------------------------------------------------------------------------

🚨 Key Findings

Most users behave normally with minimal failed login attempts

A small number of users and IPs show repeated failed access, which could indicate:

Brute-force attempts

Credential stuffing

Unauthorized access attempts

Login activity varies over time, reinforcing the importance of continuous monitoring

----------------------------------------------------------------------------------------

🔍 Why This Project Matters

Authentication logs are one of the first places security teams look when investigating incidents.

This project demonstrates:

Practical cybersecurity thinking

The ability to translate raw logs into actionable insights

Strong Python and data analysis skills applied to security use cases

It also reflects how data analytics and cybersecurity intersect in real-world environments.

----------------------------------------------------------------------------------------

🚀 Future Improvements

Machine learning–based intrusion detection

IP reputation scoring

Geo-location anomaly analysis

Real-time monitoring dashboards

Integration with SIEM-style pipelines

----------------------------------------------------------------------------------------

👩‍💻 About the Author

Leigh-Anne Ndimande
Aspiring Data Scientist | AI & Cybersecurity Enthusiast

This project is part of my growing portfolio focused on:

Data Analytics

Data Science

Machine Learning

Artificial Intelligence

Cybersecurity & Threat Analysis
