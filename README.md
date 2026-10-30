JSON Data Processor

Description

This project reads employee information from a JSON file and performs searching, filtering, and summary operations using Python.

Objective

To learn JSON handling and structured data processing in Python.

Tools Used

- Python
- JSON Module
- VS Code

Project Files

- "data.json" – Contains employee information.
- "main.py" – Python script to process JSON data.
- "README.md" – Project documentation.

Features

1. Reads employee information from a JSON file.
2. Searches employees by name.
3. Filters employees based on salary.
4. Calculates total employees.
5. Calculates total and average salary.
6. Validates required JSON keys.

How to Run

1. Create the three project files.
2. Keep all files in the same folder.
3. Open the folder in VS Code.
4. Open the terminal.
5. Run the command:

python3 main.py

Sample Output

JSON data loaded successfully!
Data validation successful!

Enter employee name to search: Pragna

Employee Found:
{'id': 101, 'name': 'Pragna',
 'department': 'IT', 'salary': 30000}

Employees with salary above 30000:
{'id': 103, 'name': 'Sneha',
 'department': 'IT', 'salary': 40000}

{'id': 104, 'name': 'Arjun',
 'department': 'Finance', 'salary': 35000}

----- EMPLOYEE SUMMARY -----
Total Employees: 4
Total Salary: 130000
Average Salary: 32500.0

Concepts Used

- JSON file handling
- "json.load()"
- Lists and dictionaries
- Searching
- Filtering
- Summary calculations
- Data validation

Conclusion

This project demonstrates how to read JSON data and perform searching, filtering, validation, and summary operations using Python.
