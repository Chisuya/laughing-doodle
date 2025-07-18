This application is a time tracker that automatically detects the usage of apps and websites by the user. The user can implement their planned schedule and get feedback/recommendations from AI to determine what changes to make to their schedule.
Tracking time when active would help with this and will try to implement.

## How It's Made:

**Tech used:** What we used

How it works blah blah

## Instructions to Build/Run:

blah blah

## Link to Bug Tracker:
https://lakdjskfj

## Optimizations
*(optional)*

## Changes

## Init project tree
time_manager_project/
│
├── app/                         # Core application code
│   ├── __init__.py              # App initialization (Flask setup)
│   ├── models/                  # Database models
│   │   └── task.py              # Task and tracking data models
│   ├── routes/                  # API routes or views
│   │   └── tasks.py             # Routes to handle task creation, tracking, etc.
│   ├── services/                # Business logic
│   │   ├── scheduler.py         # Time recommendation engine
│   │   └── tracker.py           # Logic to compare actual vs planned
│   ├── ml/                      # Learning and prediction
│   │   └── estimator.py         # Adaptive learning model (e.g., adjust estimates)
│   ├── utils/                   # Utility functions (e.g., time parsing)
│   │   └── helpers.py
│   └── templates/               # (Optional) Jinja2 templates if using server-side rendering
│
├── data/                        # Local database or cached training data
│   └── tasks.db                 # SQLite DB
│
├── tests/                       # Unit and integration tests
│   └── test_scheduler.py
│
├── scripts/                     # One-off scripts (e.g., migration, data analysis)
│   └── seed_data.py
│
├── static/                      # Static files for frontend (CSS, JS)
│
├── .env                         # Environment variables
├── requirements.txt             # Python dependencies
├── config.py                    # Configuration settings (dev, prod)
├── run.py                       # Entry point for Flask app
└── README.md                    # Project documentation
