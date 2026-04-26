# Form to Notion Pipeline — n8n Workflow

## What It Does
Captures client inquiry form submissions instantly, creates 
a structured entry in a Notion database, and sends a 
real-time Telegram notification to the business owner.
Zero manual data entry required.

## Workflow
Tally Form → Webhook → n8n → Notion Database + Telegram

## Tech Stack
- n8n
- Tally (form)
- Notion API
- Telegram Bot API

## Features
- Real-time webhook trigger on form submission
- Dropdown field mapping (ID to label)
- Structured Notion database entry with status tracking
- Instant Telegram notification with lead details

## Setup
1. Import the workflow JSON into your n8n instance
2. Connect your Notion credential and share database with integration
3. Connect your Telegram Bot credential
4. Create your Tally form and paste webhook URL into Tally integrations
5. Activate the workflow

## Use Case
Small business owners who want to automatically capture 
and organize client inquiries without manual copy-pasting.

## Result
- Zero leads lost — every submission captured automatically
- Business owner notified within seconds of submission
- Clean Notion database for tracking lead status

## Additional Features
- Automatic error monitoring with Telegram alerts
