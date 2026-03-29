# smart-student-expense-tracker
A Java-based CLI application to track and manage daily student expenses.
#  Smart Student Expense Tracker using Java



##  Project Overview

The **Smart Student Expense Tracker** is a command-line based Java application designed to help students manage and monitor their daily expenses. The system provides a simple and efficient way to record spending, view expense history, and calculate total expenditure.

In student life, managing finances is often challenging due to multiple daily expenses such as food, travel, and study materials. This project addresses that problem by offering a lightweight and easy-to-use expense tracking solution.



##  Problem Statement

Students often face difficulties in managing their daily expenses due to:

* Lack of proper tracking methods
* Poor financial planning
* Unawareness of spending habits
* Overspending on non-essential items

Existing solutions are often complex or require internet connectivity. Therefore, a simple offline solution is required.



##  Objectives

The main objectives of this project are:

* To develop a simple expense tracking system
* To allow users to record daily expenses
* To categorize expenses for better understanding
* To calculate total spending
* To improve financial awareness among students



##  Features

*  Add Expense (Category + Amount)
*  View All Expenses
*  Calculate Total Spending
*  Delete Expense
*  Simple Menu-Driven Interface



##  Technologies Used

* **Programming Language:** Java
* **Interface:** Command Line Interface (CLI)
* **Data Structure:** ArrayList
* **Input Handling:** Scanner Class



##  Working of the System

The application follows a menu-driven approach:

1. The program starts and displays a menu
2. The user selects an option
3. Based on the input, the system performs the required operation
4. The process repeats until the user exits

### Operations:

* **Add Expense:** Stores category and amount
* **View Expenses:** Displays all stored records
* **Total Spending:** Calculates total amount
* **Delete Expense:** Removes selected entry



##  Algorithm

1. Start program
2. Initialize expense list
3. Display menu
4. Take user input
5. Perform selected operation
6. Update data
7. Repeat until exit
8. End program



##  Output (Sample Execution)

C:\Users\Student>java Main

===== Student Expense Tracker =====
1. Add Expense
2. View Expenses
3. Total Spending
4. Delete Expense
5. Exit

Enter choice: 1
Enter category: Food
Enter amount: 100
Expense added successfully

Enter choice: 2
1. Food - ₹100

Enter choice: 3
Total Spending: ₹100




##  Project Structure

student-expense-tracker/
│── Main.java
│── README.md
│── screenshots/
│── report.pdf




##  How to Run

### Step 1: Compile the Program


javac Main.java


### Step 2: Run the Program


java Main




##  Challenges Faced

* Handling invalid user input
* Designing a simple interface
* Managing data efficiently



## Advantages

* Easy to use
* Lightweight application
* No internet required
* Helps track spending effectively



##  Limitations

* No graphical interface
* Data not permanently stored
* Limited features



##  Future Scope

* Add GUI using Java Swing
* Implement database storage
* Add expense reports and analytics
* Develop mobile/web version



## Learning Outcomes

* Understanding Java fundamentals
* Working with ArrayList
* Implementing OOP concepts
* Developing real-world applications



## 

** Name: Rasika Jain**
Registration Number: 24BCE10029



##  References

* Java Official Documentation
* Course materials and tutorials



## Conclusion

The Smart Student Expense Tracker is a simple yet effective application that helps students manage their daily expenses. It demonstrates how basic programming concepts can be applied to solve real-world problems in an efficient manner.

