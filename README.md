# AI Energy Optimization Agent

## AICTE Generative AI & Agentic System Engineering Internship

### SDG 13 – Climate Action

## Project Overview

The AI Energy Optimization Agent is an AI-powered smart home assistant designed to monitor household electricity consumption, analyze energy usage using Google Gemini AI, and provide personalized recommendations to reduce electricity consumption.

The project also demonstrates Agentic AI automation using n8n by automatically generating AI-based energy reports and sending them via Gmail.

---

## Problem Statement

Many households waste electricity because appliances such as air conditioners, lights, fans, and televisions remain switched on unnecessarily. This increases electricity bills and carbon emissions.

---

## Proposed Solution

The Energy Optimization Agent:

- Monitors household energy usage
- Detects high electricity consumption
- Uses Google Gemini AI for analysis
- Generates energy-saving recommendations
- Supports SDG 13 – Climate Action
- Automatically emails AI-generated reports using n8n

---

## Technologies Used

- Python
- Google Colab
- Google Gemini API (`google-genai`)
- Pandas
- Matplotlib
- n8n
- Gmail Integration
- GitHub

---

## Features

- Sample Smart Home Energy Dataset
- Energy Usage Visualization
- AI Energy Consumption Analysis
- High Energy Consumption Detection
- SDG 13 Sustainability Recommendations
- AI-generated Energy Report
- Agentic AI Workflow using n8n
- Automatic Email Notification

---

## Project Architecture

```text
                    +----------------------+
                    |        User          |
                    +----------+-----------+
                               |
                               v
                 +---------------------------+
                 |   Google Colab Notebook   |
                 +---------------------------+
                 | Sample Energy Dataset     |
                 | Data Visualization        |
                 | AI Analysis (Gemini)      |
                 | Report Generation         |
                 +------------+--------------+
                              |
                              | GitHub
                              v
                 +---------------------------+
                 |     n8n Workflow          |
                 +---------------------------+
                 | Manual Trigger            |
                 | Energy Data               |
                 | Calculate Total Energy    |
                 | Google Gemini AI          |
                 | Gmail Report              |
                 +------------+--------------+
                              |
                              v
                     +-----------------+
                     |      User       |
                     |  Email Report   |
                     +-----------------+
```

---

## n8n Workflow

```text
Manual Trigger
      │
      ▼
Sample Energy Data
      │
      ▼
Calculate Total Energy
      │
      ▼
Google Gemini AI
      │
      ▼
Generate AI Report
      │
      ▼
Send Report via Gmail
```

---

## Project Workflow

Google Colab
↓
Energy Dataset
↓
Gemini AI Analysis
↓
GitHub

n8n
↓
Manual Trigger
↓
Energy Data
↓
Calculate Total Energy
↓
Google Gemini
↓
Email Report

---

## Future Scope

- IoT Smart Meter Integration
- Real-Time Monitoring
- Carbon Footprint Dashboard
- Electricity Bill Prediction
- Mobile Notifications
- Solar Energy Optimization

---

## Author

Name Here

AICTE Generative AI & Agentic System Engineering Internship
