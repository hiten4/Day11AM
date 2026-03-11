# Day11AM

# Python Data Processing Assignment

## Overview
This project includes solutions for data processing, backup automation, debugging, and an AI-assisted coding task using Python.

---

## Part A — Multi-Source Data Merger
- Read multiple CSV files using `pathlib.glob()`
- Merge data into a single dataset
- Remove duplicate rows
- Calculate revenue per product (`qty * price`)
- Export results:
  - `merged_sales.csv`
  - `revenue_summary.json` with metadata (files processed, total rows, total revenue, generated time)

---

## Part B — Backup Manager
Script: `backup_manager.py`

Features:
- Accepts `source_directory` and `backup_directory`
- Copies `.csv` and `.json` files
- Adds timestamp to backup files
- Keeps only the latest **5 backups**
- Deletes older backups automatically
- Logs operations in `backup_log.txt`

---

## Part C — Interview Questions
- Difference between `json.load()` and `json.loads()`
- Function to find files larger than a given size using `pathlib`
- Debug and fix issues in CSV merge code (missing import, duplicate headers, newline issue)

---

## Part D — AI Task
- Generated Python script using AI
- Automatically detects CSV delimiter
- Converts CSV data to JSON
- Tested with different CSV formats

---

## Technologies Used
Python, pathlib, csv, json, shutil, datetime
