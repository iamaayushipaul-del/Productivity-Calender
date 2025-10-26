# Productivity-Calender
This is a python app development project. We have worked on making a productivity calender for daily use. It'll help us track and update our daily activities. It is a simple command-line based task manager that helps staying organized by saving and tracking  daily tasks.  

## Features
- Add, view, edit, and delete tasks  
- Organize tasks by date (YYYY-MM-DD)  
- Mark tasks as completed or pending  
- Search tasks by date  
- Automatically saves data to Google Drive (`tasks.json`)

## Requirements
- Python 3.7 or above  
- Access to Google Drive (if using in Google Colab)

## Installation
1. Open Google Colab or your local Python environment.
2. Mount your Google Drive if using Colab:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
