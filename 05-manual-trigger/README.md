Example 5: Manual Workflow Dispatch via GitHub UI

📁 Folder Structure
Demo_01/
├── 05-manual-trigger/
│   └── README.md
└── .github/
    └── workflows/
        └── 05-manual-trigger.yml

🎯 What You’ll Learn

Triggering workflows manually with workflow_dispatch
Passing inputs via GitHub UI (e.g., environment, version)
Using inputs in job steps with ${{ github.event.inputs.<input> }}

🔒 Setup Required

No special setup required, but you can define inputs like:
ENVIRONMENT = dev/test/prod
DEPLOY_VERSION = v1.0.0

▶️ How to Run

Go to GitHub → Actions → Select workflow → Run workflow → Choose inputs