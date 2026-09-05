# Cybersecurity News Automation

An n8n automation workflow that collects cybersecurity news from multiple sources, processes the articles using an AI model, and stores the structured results in an n8n Data Table.

## Overview

This project was built while learning and exploring n8n automation for cybersecurity use cases.

The workflow currently integrates two cybersecurity news sources:

- SecurityWeek
- BleepingComputer

The collected news is normalized, checked for duplicates, analyzed using an AI model, and converted into structured information before being stored in an n8n Data Table.

## Workflow

RSS Feeds
   ↓
Normalize News Data
   ↓
Merge Sources
   ↓
Remove Duplicates
   ↓
AI Analysis
   ↓
Structured Output
   ↓
Prepare News Data
   ↓
n8n Data Table





Features:

Collects cybersecurity news through RSS feeds
Supports multiple news sources
Normalizes data from different sources
Removes duplicate articles
Uses AI to analyze cybersecurity articles
Generates structured output
Categorizes news and assigns severity
Stores processed news in an n8n Data Table

Technologies Used:
n8n
RSS Feeds
AI / LLM
Structured Output Parser
n8n Data Tables
News Sources

Currently integrated sources:

SecurityWeek
BleepingComputer

More sources can be added in future versions.

AI Processing

The AI model analyzes each cybersecurity article and produces structured information including:

Title
Source
Publication Date
Category
Severity
Summary
Screenshots

Screenshots of the workflow are included in this repository to show the n8n workflow structure and implementation.

How to Use
Import workflow.json into n8n.
Configure your own AI credentials.
Configure the required RSS feeds.
Configure the Data Table.
Execute the workflow.

Note: Credentials are not included in this repository. Configure your own credentials after importing the workflow.

Future Improvements

Possible future improvements include:

Adding more cybersecurity news sources
Automated scheduling
Telegram notifications
Advanced filtering
Cybersecurity threat intelligence integration
More advanced AI-based analysis
