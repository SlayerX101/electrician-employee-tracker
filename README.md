# Tsumaki Electrical Tracker

Tsumaki Electrical Tracker is a browser-based employee workrate and payroll system for managing electrical company staff, hours, rates, deductions, repayments, rankings, and month-end paychecks.

## Current App

The main live app is:

- `index.html`

Open `index.html` in a browser to use the current tracker.

## Version History

This repository keeps a clean version history so people can see how the app improved over time.

- `versions/v1-basic.html` - first working version with employees, hours, rates, deductions, payroll totals, and rankings.
- `versions/v2-company-dashboard.html` - upgraded company dashboard with categorized sections, cleaner layout, filters, reports, backup, export, printable payroll, employee management, and money tracking.

GitHub commits also show the development progress step by step.

## Main Features

- Add and delete employees
- Log daily work hours and pay rates
- Track job sites, notes, work types, overtime, and approval status
- Add company deductions and repayments
- Subtract deductions from employee paychecks
- Show month-end payroll totals
- Rank employees by most hours worked and most days worked
- Filter by month, employee, work type, and search text
- Export work records to CSV
- Download a JSON backup
- Print payroll reports

## Data Storage

The app stores data in the browser using `localStorage`. That means it works without a backend server, but the saved data stays on the browser and device where it was entered.

## Project Goal

The goal is to grow this from a simple employee workrate calculator into a clean company dashboard that small electrical businesses could use to track payroll activity and staff performance.
