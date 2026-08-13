AI Project KPI Analyst

An AI-powered project performance analysis and reporting automation built with n8n, Google Sheets, JavaScript, and AI Agents.

📌 Project Overview

The AI Project KPI Analyst automatically evaluates project performance using multiple KPI metrics. It calculates an overall project score, determines the project status, identifies weak performance areas and risks, and generates actionable recommendations using AI.

The final analysis is automatically written back to Google Sheets.

🎯 Problem

Project managers often need to manually review multiple KPI metrics to understand project performance.

This can be time-consuming and makes it difficult to quickly identify:

- Weak KPI areas
- Project risks
- Performance issues
- Cost and resource problems
- Areas requiring immediate attention

💡 Solution

This automation collects project KPI data from Google Sheets and processes it through an n8n workflow.

The system automatically:

1. Reads project KPI data
2. Calculates the overall KPI score
3. Determines the project status
4. Sends the project data to an AI Agent
5. Analyzes project performance
6. Identifies weak KPI areas and risks
7. Generates practical recommendations
8. Updates the results in Google Sheets

⚙️ Workflow

Google Sheets
     ↓
Get Project KPI Data
     ↓
JavaScript KPI Calculation
     ↓
Overall Score & Project Status
     ↓
AI Agent
     ↓
Project Performance Analysis
     ↓
Recommendation Generation
     ↓
Prepare KPI Report
     ↓
Google Sheets Update

📊 KPI Metrics

The system analyzes the following KPIs:

- Schedule
- Scope
- Quality
- Cost
- Resource
- Risk
- Stakeholder
- Governance
- Benefits

Each KPI is scored from 0–100.

🧮 Project Status

The system automatically categorizes projects based on their overall KPI score:

Score| Status
80–100| Excellent
70–79| Good
60–69| Needs Attention
Below 60| Critical

🤖 AI Analysis

The AI Agent evaluates the project and provides:

- Strongest KPI areas
- Weakest KPI areas
- Main project risks
- Possible reasons for weak performance
- Practical recommendations
- Management summary

🧪 Example

Project: Website Development

Overall Score: 79

Status: Good

The AI identified Risk as one of the weakest areas and recommended a risk deep-dive, cost review, and resource optimization.

🛠️ Technologies Used

- n8n
- Google Sheets
- AI Agent
- JavaScript
- Generative AI
- Workflow Automation

🚀 Key Features

- Automated KPI calculation
- AI-powered project analysis
- Risk identification
- Performance classification
- Actionable recommendations
- Automated Google Sheets reporting
- No manual KPI analysis required

📸 Screenshots

n8n Workflow

Add workflow screenshot here.

AI Analysis

Add AI Agent output screenshot here.

Google Sheets Report

Add final Google Sheets screenshot here.

🔮 Future Improvements

- Automatic email reports
- Slack/Telegram notifications
- Project dashboard
- Historical KPI tracking
- KPI trend analysis
- Multiple project comparison
- Scheduled management reports

👨‍💻 Project Type

AI Automation | Business Operations | Project Management
