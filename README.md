Timetable App
A desktop application built with Python and Tkinter for managing course schedules.

Features
Load course data from a CSV file

Filter courses by year and department

Display course list and selected courses

Detect and prevent time conflicts when adding courses

Limit maximum selected courses to 6

Save selected timetable to a CSV file

Clear course selections

Technologies Used
Python 3

Tkinter (for GUI)

CSV module (for reading/writing CSV files)

How to run
Make sure you have Python 3 installed.

Clone the repository.

Run the main script:

bash
Copy
Edit
python timetable.py
Enter the path to your CSV file when prompted.

Select the year and department to filter courses.

Add courses by selecting them from the list.

Save your timetable.

Notes
The app checks for scheduling conflicts and prevents adding overlapping courses.

Maximum of 6 courses can be selected.

If the CSV file is not found, the app will notify you to check the path.
