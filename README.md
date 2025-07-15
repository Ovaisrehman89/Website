# UpWork Agency Management System

A Flask-based internal tool for agencies working on UpWork. It automates job collection, proposal creation, task assignment, and team performance tracking.

## Features

- Job discovery via UpWork scraping/API
- Proposal generation with Google Gemini
- Email notifications
- Task and workload management
- Role-based user access
- Dashboards and reporting

## Tech Stack

- Flask (Backend)
- MySQL (Database)
- Google Gemini (AI API)
- Outlook (Emails)

## Setup

```bash
pip install -r requirements.txt
python wsgi.py
```

Make sure MySQL is running and your `.env` is properly configured.