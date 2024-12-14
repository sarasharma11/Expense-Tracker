# Expense-Tracker
## Overview
This Expense Tracker utilizes Python, SQLite, and AWS to manage income and expenses, track budgets, and generate comprehensive financial reports. It is integrated with AWS SNS to provide real-time alerts when spending nears budget limits.

## Features

-Income & Expense Tracking: Track and categorize income and expenses.

-Budget Management: Set and monitor budget thresholds.

-Financial Reports: Generate comprehensive financial reports.

-Real-time Alerts: Receive notifications via AWS SNS when spending nears the budget limit.

-Secure Data Storage: Uses SQLite for efficient, secure transaction history management.

## Installation
### Prerequisites:

-Python 3.x

-SQLite (pre-installed with Python)

-Boto3 (AWS SDK for Python)

### Steps:
1. Clone the repo:
```bash
git clone https://github.com/<your-username>/expense-tracker.git
cd expense-tracker
```

2. Install required libraries:
```bash
pip install boto3
```

3. Set up AWS SNS (follow the AWS SNS documentation to configure SNS for alerts).

4. Run the application:
```bash
python main.py
```
