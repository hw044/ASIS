# ASIS
An SQL Injection Scanner

![Screenshot 2024-06-20 223632](https://github.com/user-attachments/assets/bd8ee34d-8727-4f3b-9b4f-b13af45e512a)

System Requirements

•	Operating System: Windows or Kali Linux
•	Python Version: Python 3.6+
•	Python Libraries: Tkinter, OS, re

Installation

1.	Install Python: Ensure Python 3.6+ is installed on your system. You can download it from Python's official website.
2.	Download ASIS: Download the asis.py file and save it to a directory of your choice.
3.	Install Required Libraries: Open a terminal or command prompt and run the following commands to install the required Python libraries: ‘pip install tk’.

Usage

Launching the Application
1.	Open a terminal or command prompt.
2.	Navigate to the directory where you saved asis.py.
3.	Run the following command: ‘python asis.py’

Selecting a Directory
1.	Upon launching the application, you will see the main interface.
2.	Click the "Browse" button to open a file dialog.
3.	Select the directory containing the source code files you want to scan.

Scanning for Vulnerabilities
1.	After selecting the directory, click the "Scan" button to start the scanning process.
2.	The application will recursively scan each file in the selected directory for predefined SQL injection patterns.

Results
1.	The results of the scan will be displayed in the large grey box on the main interface.
2.	If vulnerabilities are detected, they will be listed with the file names and specific line numbers where issues were found.
3.	If no vulnerabilities are found, a corresponding message will be displayed.
