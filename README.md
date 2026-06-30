# n8n-workflow-newsletter-to-gmail
An n8n workflow that automatically generates AI-summary of tech newsletter and sends it to Gmail, streamlining email communication and content distribution.
# 📧 n8n Workflow - Newsletter to Gmail

## Overview

This project demonstrates how to automate newsletter creation and email delivery using **n8n**.

The workflow generates or receives newsletter content, formats it into an email, and sends it through Gmail. It showcases how workflow automation can simplify business communication by eliminating repetitive manual tasks.

This project is part of my journey in building AI-powered business automation solutions using n8n.

---

## Business Problem

Organizations regularly send newsletters to employees, customers, or stakeholders. Creating and sending these emails manually is time-consuming and prone to inconsistencies.

This workflow automates the process by generating or preparing newsletter content and delivering it through Gmail.

---

## Solution

The workflow performs the following steps:

1. Trigger the workflow manually or on a schedule.
2. Generate or retrieve newsletter content.
3. Format the email body.
4. Send the newsletter using Gmail.
5. Log the execution for monitoring.

---

## Workflow

Trigger
    │
    ▼
Add the URL of newsletter
    │
    ▼
Read top 5 articles and summarise
    │
    ▼
Send Gmail
    │
    ▼
Success


---

## Features

- Automated newsletter generation
- Gmail integration
- Customizable email subject and content
- Manual or scheduled execution
- Easy to extend with AI-generated content
- Low-code workflow using n8n

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation |
| Gmail API | Email delivery |
| Docker | Local deployment | Prompt |
| JavaScript Expressions | Dynamic content generation |
| AI LLM (ollama) | Newsletter generation and summarization |

---

## Prerequisites

- Docker Desktop
- n8n
- Gmail account
- Gmail OAuth credentials
- Internet connection

---

## Future Enhancements

- AI-generated newsletters using Ollama or OpenAI
- RSS feed integration
- Company branding templates
- HTML email formatting
- Scheduled daily or weekly newsletters
- Slack or Microsoft Teams notifications
- Analytics and delivery reporting

---

## Repository Structure

```
.
├── workflow.json
├── README.md

```

---

## Learning Outcomes

This project helped me understand:

- Workflow orchestration with n8n
- Gmail integration
- API authentication
- Business process automation
- AI-assisted workflow design

---

## Author

**Chaitra T**

AI Automation | Workflow Automation | Python | n8n | Generative AI
