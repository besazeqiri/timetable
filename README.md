# Timetable App

A desktop application built with Python and Tkinter for managing course schedules.

## Features

- Load course data from a CSV file
- Filter courses by year and department
- Display course list and selected courses
- Detect and prevent time conflicts when adding courses
- Limit maximum selected courses to 6
- Save selected timetable to a CSV file
- Clear course selections

## Technologies Used

- Python 3
- Tkinter (for GUI)
- CSV module (for reading/writing CSV files)

## How to run

1. Make sure you have Python 3 installed.
2. Clone the repository.
3. Run the main script:


   ```bash
   python timetable.py

4. Enter the path to your CSV file when prompted.
5.  Select the year and department to filter courses.
6.  Add courses by selecting them from the list.
7.  Save your timetable.


## Notes

- The app checks for scheduling conflicts and prevents adding overlapping courses.
- Maximum of 6 courses can be selected.
- If the CSV file is not found, the app will notify you to check the path.
