# n8n Automation Projects

This repository contains **multiple automation workflows built using n8n**.
These projects demonstrate how different services such as **Telegram, OpenAI (ChatGPT), Gmail, APIs, and Google Sheets** can be connected to build real-world automation systems.

The goal of this repository is to learn and demonstrate **AI-powered automation and workflow orchestration using n8n**.

---

# Workflows in this Repository

## 1. Telegram + ChatGPT Bot

This workflow connects **Telegram with OpenAI (ChatGPT)**.

### Features

* Telegram bot receives user messages
* Sends the message to ChatGPT API
* ChatGPT generates a response
* The response is sent back to the Telegram user automatically

### Technologies Used

* Telegram Bot API
* OpenAI API
* n8n Webhook and HTTP nodes

### Use Case

This automation can be used to create:

• AI chat assistants
• automated support bots
• personal AI helpers inside Telegram

---

## 2. Weather Report Automation (API Integration)

This workflow fetches **weather information using a weather API** and processes the data in n8n.

### Features

* Calls external weather API
* Retrieves real-time weather data
* Processes temperature and conditions
* Sends formatted output

### Technologies Used

* Weather API
* HTTP Request Node
* n8n workflow automation

### Example Use Case

• Daily weather alerts
• automated weather reports
• smart home weather notifications

---

## 3. AI Gmail Auto Sorter

This project uses **AI to automatically analyze and categorize emails**.

### Features

* Connects to Gmail inbox
* Reads incoming emails
* Uses AI to classify emails
* Stores categorized data in Google Sheets
* Sends reminders for important emails

### Workflow Process

New Email Received
↓
n8n Gmail Trigger
↓
AI analyzes email content
↓
Email category stored in Google Sheets
↓
Reminder email sent if needed

### Integrations Used

* Gmail API
* Google Sheets
* AI text classification
* n8n automation

### Example Categories

* Important
* Work
* Personal
* Promotions

---

# Technologies Used

This repository demonstrates automation using:

* **n8n Workflow Automation**
* **OpenAI API**
* **Telegram Bot API**
* **Weather API**
* **Gmail API**
* **Google Sheets**

n8n is an open-source workflow automation platform that allows developers to connect different services and automate tasks without building full backend systems.

---

# How to Use

### 1 Install n8n

Run locally:

```
npx n8n
```

Or using Docker:

```
docker run -it --rm -p 5678:5678 n8nio/n8n
```

---

### 2 Import Workflows

1. Open n8n dashboard
2. Go to **Workflows**
3. Click **Import**
4. Upload the workflow JSON file

---

### 3 Configure Credentials

Connect the required services:

* OpenAI API Key
* Telegram Bot Token
* Gmail Account
* Google Sheets

---

# Learning Outcomes

These projects demonstrate how to:

* Build AI-powered automation systems
* Connect multiple APIs in a single workflow
* Use AI for decision making in automation
* Build low-code integrations with n8n

---

# Future Improvements

Possible improvements for this repository:

• AI-based email priority scoring
• automated meeting scheduling
• advanced analytics dashboards
• multi-platform chatbot integrations

---

# Author

Sanjay Kumar
GitHub: https://github.com/sanjay-jetx

---

# License

This project is open source and available under the MIT License.
