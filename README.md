# Theta-Tau-Drive-Google-Apps-Script-file-sorter

This project is a **Google Apps Script automation** built for the Theta Tau Engineering Fraternity at Santa Clara University to organize academic resources in our Google Drive.

## Features
- Scans all subfolders within a master academic folder.
- Automatically categorizes files into:
  - Study Guides
  - Labs
  - Exams/Quizzes
  - Notes
  - Homework
- Uses keyword detection in file names to determine category.
- Moves files to the correct subfolder using the Google Drive API.
- Logs all file movements (timestamp, original folder, new folder) to a Google Sheet for transparency.

## Demo Log Sheet
View a sample log of file movements here:  
[📄 Demo Log Sheet](https://docs.google.com/spreadsheets/d/17XmK1hnw1YooRHvnxDkIx2F_0lUBFzZomcS3mSZD8I4/edit?usp=sharing)

## Tech Stack
- Google Apps Script (JavaScript)
- Google Drive API
- Google Sheets API

## How It Works
1. Script scans the master academic folder.
2. Identifies and categorizes files by keywords.
3. Moves them into the correct subfolder.
4. Logs the operation in a Google Sheet.

---
