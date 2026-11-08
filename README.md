# Library Management System

A Python-based library management application developed using Tkinter and SQLite. It provides a graphical interface for managing books and student borrowing records.

## Features

- View available books and quantities.
- Register student book borrowing records.
- Track borrowing and return dates.
- Calculate overdue fines at 5.00 per day.
- Search records by student name or book title.
- Delete borrowing records and restore book quantities.
- Store data using an SQLite database.

## Technologies Used

- Python
- Tkinter
- SQLite
- tkcalendar
- Jupyter Notebook

## Installation and Setup

1. Install Python.
2. Clone or download this repository.
3. Install the required dependency:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `library_management_system.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

## Database

The application automatically creates a local SQLite database named `library.db` when the setup cell is executed.

The database file is generated locally and is not included in this repository.
