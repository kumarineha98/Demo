Example 6: Scheduled Workflows (Cron Jobs)

📁 Folder Structure
Demo_01/
├── 06-schedule-trigger/
│   └── README.md
└── .github/
    └── workflows/
        └── 06-schedule-trigger.yml

🎯 What You’ll Learn

Automating workflows with on: schedule (cron syntax)
Running nightly, weekly, or hourly tasks
Example: nightly health check or report generation

🔒 Setup Required

No user input needed — just commit the workflow
Uses cron expression like 0 0 * * * (every midnight UTC)

▶️ How to Run

Wait for scheduled time OR temporarily trigger with workflow_dispatch for testing