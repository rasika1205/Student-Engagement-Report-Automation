# 📊 Student Engagement Automation (n8n)

An automated data pipeline built with **n8n** that processes student data, calculates KPIs, generates visual analytics, and sends automated reports via email.

---

## 🚀 Features

* Automated trigger using Google Sheets updates
* Data cleaning pipeline
* KPI calculation (6–8 metrics)
* Location-wise student distribution analysis
* Automatic bar chart generation
* Email report delivery

---

## 🏗 Workflow Architecture

1. Google Sheets Trigger
2. Data Cleaning (JavaScript)
3. KPI Calculation
4. Location-based Aggregation
5. Chart Generation
6. Report Generation
7. Email Delivery

---

## 📸 Workflow

![Workflow](screenshots/workflow.png)

<img width="1919" height="910" alt="Screenshot 2026-03-05 225924" src="https://github.com/user-attachments/assets/668d9b9a-a7e1-4051-b31d-6a8e525d757a" />

---

## 🛠 Tech Stack

* n8n
* JavaScript
* Google Sheets API
* Gmail API

---

## 📂 Workflow File

You can import the workflow directly into n8n:

```
workflow.json
```

---

## 🎯 Use Case

This system can be used by:

* Universities
* EdTech companies
* Training institutes

to automatically monitor student engagement metrics.

---

## ⚡ Future Improvements

* Dashboard integration
* Slack notifications
* Real-time analytics
