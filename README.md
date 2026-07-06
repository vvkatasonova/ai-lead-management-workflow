# AI Lead Response Automation with n8n

## Overview

AI-powered lead management workflow that automatically processes incoming customer requests, evaluates their priority, and notifies a manager with actionable insights.

The system receives lead information from Google Forms, analyzes the request using AI, stores structured data in Google Sheets, and delivers a complete summary to Telegram.

## Business Problem

Businesses often lose potential customers because new requests are processed manually, without prioritization, or with delayed responses.

Managers need to quickly understand:

- what the customer is requesting;
- how important the lead is;
- whether immediate action is required;
- what response should be sent.

## Solution

This project automates the complete lead processing workflow.

The system can:

- receive customer requests from Google Forms;
- save all lead information to Google Sheets;
- analyze the request using AI;
- determine the lead priority;
- generate a suggested response;
- notify a manager in Telegram with all relevant information.

## Workflow

1. A customer submits a Google Form.
2. The automation receives the form data.
3. Lead information is saved to Google Sheets.
4. AI analyzes the request.
5. AI determines the priority level.
6. AI generates a suggested reply.
7. A Telegram notification is sent to the manager containing:
   - customer request;
   - priority level;
   - AI-generated response suggestion.

## My Role

Designed and implemented the entire automation workflow independently.

Responsibilities included:

- workflow architecture;
- Google Forms integration;
- Google Sheets integration;
- AI prompt engineering;
- lead prioritization logic;
- Telegram Bot integration;
- testing and optimization.

## Technologies

- n8n
- OpenAI API
- Google Forms
- Google Sheets
- Telegram Bot API
- Prompt Engineering
- Workflow Automation

## Future Improvements

- CRM integration;
- automatic lead assignment;
- manager approval buttons in Telegram;
- automatic customer response after approval;
- lead analytics dashboard.

## Note

This is a personal practice project created to explore AI-powered business automation workflows.
