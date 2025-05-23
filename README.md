# Student Data Tracker CLI Tool
Building a command-line application using Python to manage student records.

🎯 **Objective**

Develop a command-line application using Python to manage student records efficiently. The tool allows users to input student details, compute average marks, display records, and save data to a CSV file.

🛠️ **Features**

* Add Student Records: Input student name, roll number, and marks for three subjects with validation.

* Display All Records: View all stored student information in a structured format.

* Calculate Average Marks: Compute and display the average marks for each student.

* Save to CSV: Export all student records to a student_records.csv file for external use.

* Robust Error Handling: Ensures smooth user experience with comprehensive input validations and exception handling.

📝 **Code Overview**
  
* The application is structured with modular functions:

* add_student(): Handles input and validation for new student records.

* display_students(): Displays all current student records.

* calculate_averages(): Calculates and displays average marks.

* save_to_csv(): Exports records to a CSV file.

* main(): Controls the program flow and user interaction.
  
📄 **CSV Output**

The student_records.csv file will have the following structure:

* Name,Roll Number,Subject 1,Subject 2,Subject 3
  
* John Doe,101,85,90,78
  
* Jane Smith,102,92,88,95
  
  ...
