# Employee Productivity Snapshot

## What it does
It displays task completed by 15 employees. It also shows the average time-to-completion per task as well.

**Live dashboard:** https://gbordjuerpriscilla.github.io/employee_snapshot_productivity/

## What it shows
- Tasks completed per employee, per week
- Average time-to-completion per task

## Top insight
One employee's average time per task was completely normal (2.4 hours), but their weekly task count dropped to zero over the final two weeks. A manager checking only the average would have missed it entirely; only the weekly trend caught it.

## How it was built
Python (pandas, matplotlib) in Google Colab for the analysis. HTML + Chart.js for the dashboard, hosted on GitHub Pages.

## Note on the data
The dataset is simulated (15 employees, 6 weeks), with one employee's activity deliberately dropped so the trend chart had something real to catch.

# employee_snapshot_productivity
The hardest part of this project was creating making sure the weekly trend caught what someone else would have missed.
