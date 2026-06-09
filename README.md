# shiori-ai-personal-assistant

AI-powered personal assistant that reviews calendar events, detects scheduling conflicts, tracks recurring schedules, and delivers automated daily briefings using Google Apps Script, Gmail, Google Calendar, and OpenAI.

## Overview

Shiori is a personal assistant designed to reduce the time spent manually reviewing calendars and upcoming commitments.

The assistant automatically gathers information from Google Calendar, identifies important upcoming events, detects scheduling conflicts, tracks recurring schedules, and generates a daily AI-powered briefing delivered by email.

## Features
- Daily AI-generated schedule briefings
- Google Calendar integration
- Scheduling conflict detection
- Recurring schedule tracking
- Automated email delivery
- OpenAI-powered natural language summaries
- Time-driven automation using Google Apps Script

## Example Briefing
```text
Good morning, User.
Today:
9:00 AM Client Strategy Meeting
2:00 PM Project Review
Upcoming:
Tuesday, June 10 — 11:00 AM
Quarterly Planning Session
Location: Zoom
Wednesday, June 11 — 3:00 PM
Mentorship Meeting
Location: Virtual
⚠️ Scheduling Conflict Detected

Friday, June 13 — 1:00 PM
Vendor Presentation
and
Team Retrospective
You may need to reschedule one.
```

## Tech Stack
- Google Apps Script
- Google Calendar
- Gmail (MailApp)
- OpenAI GPT-4.1 Mini
- JavaScript


## Workflow
1. Retrieve upcoming events from Google Calendar.
2. Filter for important appointments and upcoming commitments.
3. Detect overlapping events and scheduling conflicts.
4. Generate a structured daily briefing using OpenAI.
5. Deliver the briefing automatically by email using Gmail.
6. Run automatically through scheduled Apps Script triggers.


## Business Value
- Automates daily schedule reviews and calendar monitoring.
- Provides visibility into upcoming commitments and deadlines.
- Identifies scheduling conflicts before they become disruptions.
- Consolidates calendar information into a single AI-generated briefing.
- Reduces manual effort required to manage appointments and schedules.


## Future Improvements
Enhanced attendee extraction and meeting summaries.
Daily task and reminder management.
Priority scoring for upcoming events.
Multi-channel notification delivery.
Integration with task management systems.


## Author
Leonard Klein
LinkedIn: linkedin.com/in/leonardjacobklein

## Screenshots

### Daily Briefing Email
[image]

### Apps Script Automation
[image]

### Trigger Configuration
[image]
