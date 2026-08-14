# AI Scrum Retrospective Assistant

## Overview

The AI Scrum Retrospective Assistant is an AI-powered automation built with n8n.

It analyzes Sprint Retrospective feedback and automatically identifies important insights, including the category, main theme, priority, summary, and recommended action item.

The results are automatically stored in Google Sheets, making it easier to track retrospective insights and identify areas for continuous improvement.

## Features

- AI-powered retrospective feedback analysis
- Automatic categorization of feedback
- Theme identification
- Priority classification
- Automatic summaries
- Recommended action items
- Structured AI output
- Automatic storage in Google Sheets

## Workflow

Manual Trigger → Edit Fields → AI Agent → Google Sheets

The AI Agent uses:

- OpenRouter Chat Model
- Structured Output Parser

## AI Output

The workflow generates:

- Category
- Theme
- Priority
- Summary
- Action Item

Example:

```json
{
  "category": "what_didnt_go_well",
  "theme": "Unclear Requirements",
  "priority": "high",
  "summary": "The Sprint experienced delays because some requirements were unclear.",
  "action_item": "Improve backlog refinement before the next Sprint."
}


Technologies Used
n8n
OpenRouter
AI Agent
Structured Output Parser
Google Sheets
Google OAuth 2.0
Use Case

This automation helps Scrum Masters and Scrum Teams process Sprint Retrospective feedback more efficiently.

Instead of manually reviewing and organizing feedback, the workflow uses AI to identify themes, classify priorities, and generate actionable improvement suggestions.

Future Improvements

Possible future improvements include:

Accepting feedback through a form
Processing multiple retrospective responses automatically
Slack integration
Email notifications
Automatic Sprint reports
Dashboard for retrospective trends
Sentiment analysis
Screenshots

Screenshots of the n8n workflow, AI output, successful execution, and Google Sheets results are included in this repository.
