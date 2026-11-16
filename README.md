🎓 Result Processing System Using Templates (C++)

A menu-driven console application built using C++ Function Templates and Class Templates to process student results efficiently.

📌 Project Overview

This project demonstrates generic programming in C++ by processing student scores using templates. The same code works with multiple data types without code duplication.

✨ Features
Process integer student scores.
Process floating-point student scores.
Find the largest of three values (int, double, char).
Calculate the average of three values.
Validate scores between 0 and 100.
Handle invalid user inputs.
Menu-driven console interface.
🛠️ Technologies Used
Language: C++
Compiler: g++
Standard: C++11
Concepts: Function Templates, Class Templates, OOP, Encapsulation.
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

1. Clone the repository

bash
git clone <your-repository-url>


2. Open project folder

bash
cd Result-Processing-System


3. Compile

bash
g++ -std=c++11 result_processor.cpp -o result


4. Run

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
Integer Scores

!Integer Scores

Floating-Point Scores

!Floating Point Scores

Input Validation

!Input Validation

🧪 Test Cases
Test Case	Input	Expected Output
Integer scores	85, 92, 78	Highest: 92, Average: 85.00
Floating-point scores	72.5, 68.25, 90.75	Highest: 90.75, Average: 77.17
Equal scores	50, 50, 50	Highest: 50, Average: 50.00
Boundary values	0, 100, 50	Highest: 100, Average: 50.00
Invalid input	abc, 150	Error and re-prompt
🧠 OOP Concepts Used
Concept	Implementation
Function Templates	largestOfThree, averageOfThree, readScore, processStudents
Class Templates	StudentResult<T>
Generic Programming	Reusing code for multiple data types
Encapsulation	Private data members with public getters and setters
Constructor	StudentResult(string, T)
⚠️ Limitations
Records are not saved to files.
Only three students are processed per run.
No grade calculation or ranking system.
🔮 Future Scope
Save and load records using file handling.
Support multiple students using vectors.
Add grade calculation.
Implement sorting and ranking.
Generate student performance reports.
🌍 Sustainable Development Goals
SDG 4 – Quality Education: Promotes programming knowledge and practical learning.
SDG 9 – Industry, Innovation and Infrastructure: Encourages reusable and maintainable software development.
👨‍💻 Author

Mayank sharma

⭐ If you find this project useful, don't forget to give this repository a star!

Made with ❤️ using C++
