# Survey-Based Phishing Awareness & Behavioral Analysis Platform

## Overview

Phishing attacks continue to exploit human behavior as one of the weakest links in cybersecurity. This project is a survey-based behavioral analysis platform designed to assess phishing susceptibility by evaluating how users classify phishing and legitimate email scenarios.

Unlike traditional phishing simulators that focus only on user decisions, this platform also captures behavioral and cognitive metrics such as response time (decision latency) and qualitative reasoning behind each verdict. The collected data supports behavioral cybersecurity research and helps identify high-risk user groups for targeted security awareness initiatives.

The platform was developed as a research-oriented full-stack application for collecting and analyzing responses from different organizational demographics such as students, faculty, and staff.

---

## Research Objective

The project aims to:

- Measure phishing susceptibility across different user groups
- Analyze decision-making behavior during phishing detection
- Capture reasoning patterns behind user classifications
- Identify impulsive or high-risk behavioral trends
- Support data-driven cybersecurity awareness programs

---

## Core Features

- Interactive phishing awareness survey with 10 email scenarios
- Users classify each email as **Phishing** or **Legitimate**
- Behavioral metric tracking using response time analysis
- Mandatory reasoning input for qualitative behavioral analysis
- Role-based participant segmentation:
  - Student
  - Faculty
  - Staff
- Introductory awareness page explaining phishing concepts
- Anti-duplication mechanism to prevent multiple submissions ensuring dataset integrity
- CSV export support for statistical and research analysis

---

## Technical Stack

- Frontend: HTML5, CSS3, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB Atlas
- Data Export: json2csv
- Deployment Platform: Render

---

## System Workflow

1. User accesses the phishing awareness platform
2. Introductory page explains phishing indicators and survey instructions
3. User provides demographic information
4. The platform displays 10 static email scenarios
5. User classifies each email as phishing or legitimate
6. Response time for each decision is automatically recorded
7. User provides reasoning for every classification
8. Responses are securely stored in MongoDB

---

## Behavioral Metrics Collected

The platform records multiple behavioral indicators for research analysis:

- User verdicts for each email scenario
- Decision latency (time-to-verdict)
- Qualitative reasoning responses
- Demographic segmentation data
- Overall phishing susceptibility patterns

---

## Dataset Structure

The application exports a flattened CSV optimized for ingestion into analytical tools (e.g., Python, R, Excel). Data attributes include:

- Demographics: Student_Name_ID, Role, Age, Gender
- Scenario Data: Q1_Image through Q10_Image
- User Verdicts: Q1_Verdict through Q10_Verdict
- Qualitative Reasoning: Q1_Reason through Q10_Reason
- Cognitive Latency: Q1_Time(sec) through Q10_Time(sec)

---

## Screenshots

### Introduction & Awareness Page

![Intro Page](./screenshots/intro_page.png)

---

### Email Classification Interface

![Survey Interface](./screenshots/survey_interface.png)

---

## Challenges Faced

- Designing realistic phishing and legitimate email scenarios
- Capturing accurate behavioral timing metrics in real time
- Preventing duplicate submissions while maintaining usability
- Structuring large survey datasets for analysis and export
- Balancing research data collection with user privacy considerations

---

## Research Applications

- Phishing awareness assessment
- Human-factor cybersecurity research
- Behavioral security analysis
- Security awareness training optimization
- Demographic risk profiling

---

## Ethical Use Notice

This platform was developed strictly for educational research, phishing awareness assessment, and authorized cybersecurity studies.

No real phishing campaigns, credential collection, or malicious activity are involved in the system.

All collected data is intended solely for behavioral analysis and security awareness research.

---

## Authors

- Sahiti M  
- Kiranmai Meghana
