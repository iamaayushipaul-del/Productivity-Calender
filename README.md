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
## Usage
Run the program:
python productivity_calendar.py

You’ll see a menu like this:
--- PRODUCTIVITY CALENDAR ---
1. Add Task
2. View All Tasks
3. Delete Task
4. Mark Task as Completed
5. Edit Task
6. Search by Date

## File Structure
Productivity_Calendar/
│
├── tasks.json             # Automatically created to store your tasks
├── productivity_calendar.py  # Main Python script

## Notes
All data is stored in tasks.json inside your Google Drive path.
If the file doesn’t exist, it will be created automatically.
The app uses simple JSON for easy backup and manual editing if needed.

## Authors
Aayushi Paul, Arya Sharma, Sia Oberoi
8. Exit
