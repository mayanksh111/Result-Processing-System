# Result Processing System Using Templates (C++)
🎓 Result Processing System Using Templates (C++)

A menu-driven console application built using C++ Function Templates and Class Templates to process student results efficiently. The project demonstrates generic programming by handling multiple data types (int, float, double, and char) without duplicating code.

📌 Project Overview

Writing separate functions and classes for different data types leads to code duplication and poor maintainability.

This project solves that problem using C++ templates, allowing the same logic to work with different data types.

Users can:

Process integer student scores.
Process floating-point student scores.
Find the largest of three values (int, double, char).
Calculate the average of three scores.
Validate score inputs within the range of 0–100.
✨ Features
Function Templates
largestOfThree<T>() – Finds the largest of three values.
averageOfThree<T>() – Calculates the average of three values.
readScore<T>() – Validates scores between 0 and 100.
processStudents<T>() – Processes student records using templates.
Class Template
StudentResult<T> – Stores student names and scores using a generic data type.
Input Validation
Handles invalid inputs.
Rejects scores outside the 0–100 range.
Prompts users to enter valid values again.
Menu-Driven Interface
Simple console-based navigation.
Handles invalid menu choices.
Supports integer and floating-point scores.
🛠️ Technologies Used
Language: C++
Concepts: Function Templates, Class Templates, OOP, Encapsulation
Compiler: g++
Standard: C++11
📂 Project Structure
text
Result-Processing-System/
│
├── result_processor.cpp
├── README.md
│
└── screenshots/
    ├── output1_integer_scores.png
    ├── output2_floating_point_scores.png
    └── output3_invalid_input_validation.png

🚀 How to Compile and Run
1. Clone the Repository
bash
git clone <your-repository-url>

2. Navigate to the Project Directory
bash
cd Result-Processing-System

3. Compile the Program
bash
g++ -std=c++11 result_processor.cpp -o result

4. Run the Program

Linux / macOS:

bash
./result


Windows:

bash
result.exe

💻 Sample Output
text
===== RESULT PROCESSING SYSTEM =====

1. Process integer scores
2. Process floating-point scores
3. Largest of three (int / double / char demo)
0. Exit

Choice: 1

--- Processing integer scores ---

Enter name of student 1: Aman
Enter score (0-100): 85

Enter name of student 2: Riya
Enter score (0-100): 92

Enter name of student 3: Karan
Enter score (0-100): 78

Results:

Student: Aman         | Score: 85
Student: Riya         | Score: 92
Student: Karan        | Score: 78

Highest score : 92
Average score : 85.00

📸 Screenshots
1. Integer Scores

!Integer Scores

2. Floating-Point Scores

!Floating Point Scores

3. Input Validation

!Input Validation

🧪 Test Cases
Test Case	Input	Expected Output
Integer scores	85, 92, 78	Highest: 92, Average: 85.00
Floating-point scores	72.5, 68.25, 90.75	Highest: 90.75, Average: 77.17
Equal scores	50, 50, 50	Highest: 50, Average: 50.00
Boundary values	0, 100, 50	Highest: 100, Average: 50.00
Invalid input	abc, 150	Error message and re-prompt
🧠 OOP Concepts Used
Concept	Implementation
Function Templates	largestOfThree, averageOfThree, readScore, processStudents
Class Templates	StudentResult<T>
Generic Programming	Reusing code for multiple data types
Encapsulation	Private name and score with public getters and setters
Constructor	StudentResult(string, T) with default arguments
⚠️ Limitations
Student records are not saved to files.
Only three students are processed per run.
No grade calculation or ranking system is currently implemented.
🔮 Future Scope
Save and load student records using file handling.
Support unlimited students using vector<StudentResult<T>>.
Add grade calculation.
Implement sorting and ranking of student results.
Generate detailed student performance reports.
🌍 Sustainable Development Goals (SDG)

SDG 4 – Quality Education: Encourages learning and practical implementation of programming concepts.

SDG 9 – Industry, Innovation and Infrastructure: Promotes efficient software development through reusable and maintainable code.

👨‍💻 Author

Your Name

⭐ If you find this project useful, consider giving this repository a star!

Made with ❤️ using C++
