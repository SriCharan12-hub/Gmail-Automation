🚀 AI-Powered Gmail Automation System (n8n + OpenAI)

An AI-driven email automation system built using n8n and OpenAI to intelligently process Gmail messages, automate actions, and ensure reliability with a fault-tolerant error handling workflow.

📌 Project Overview

This project consists of two main workflows:

MyWorkFlow.json → Handles email processing and automation
ErrorFlow.json → Manages error handling, logging, and alerts

Together, they form a scalable, event-driven automation system.

⚙️ Core Features

💬 Email Automation Workflow (MyWorkFlow.json)
AI-based email classification using OpenAI
Deletes spam/transactional emails automatically
Routes emails based on content type
Schedules meetings using Google Calendar
Supports scheduled triggers for inbox cleanup

🚨 Error Handling Workflow (ErrorFlow.json)

Centralized error handling system
Logs errors into a data table for monitoring
Automatically retries failed workflows
Sends real-time alerts via Slack and Email
Ensures fault-tolerant and reliable automation

🔄 Workflow Architecture

Gmail Trigger → AI Processing → Routing → Action
                     ↓
              Error Handling Flow

🛠️ Tech Stack

Automation: n8n
AI: OpenAI API
Email: Gmail API
Scheduling: Google Calendar API
Notifications: Slack API

📂 Project Structure

GMAIL-AUTOMATION/
│── MyWorkFlow.json     # Main email automation workflow  
│── ErrorFlow.json      # Error handling & retry workflow  
│── README.md  

🚀 How to Use

Import MyWorkFlow.json into n8n
Import ErrorFlow.json into n8n
Connect required credentials:
Gmail API
OpenAI API
Slack (optional)
Google Calendar
Activate workflows

🧠 Key Learnings

Designed AI-powered automation pipelines
Built event-driven workflows with real-time processing
Implemented fault-tolerant systems with retries & logging
Integrated multiple APIs into a unified workflow


