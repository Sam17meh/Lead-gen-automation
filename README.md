# Lead Gen Automation

A simple n8n workflow for finding clinic leads, scoring them, logging them to Google Sheets, and sending outreach messages.

## What it does

- Searches for local clinic leads
- Pulls place details from Google Places
- Scores each lead
- Saves qualified leads to Google Sheets
- Sends WhatsApp outreach
- Updates lead status in the sheet

## File

- `clinic-lead-outreach-bot.json` - the n8n workflow export

## Setup

1. Import `clinic-lead-outreach-bot.json` into n8n.
2. Set your Google Sheets credential.
3. Connect your WhatsApp outreach credential.
4. Update the search city or location in the config node.
5. Make sure your Google Sheet has matching columns.

## Notes

- This workflow is designed for clinic lead sourcing and outreach.
- If a node fails, check its credentials and sheet/tab names first.
