# Automated Backup Script (with Logging)

A Python automation script to back up files or folders into timestamped compressed archives, with proper logging for tracking all backup activity.

## Features
- Backup any directory or file to a `.zip` archive
- Timestamp-based naming system
- Keeps logs of every backup (success/failure)
- Customizable source and destination paths

## Tech Stack
- Python
- shutil
- os, time, datetime
- logging
- zipfile

## How to Run
1. (Optional) Add source/destination to `config.json`

2. Run the script:  
