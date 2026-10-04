🚗 Car Parking Fee Calculator

A simple Python project that calculates car parking fees based on parking duration and applies a 10% discount when the total fee exceeds ₹200.

This project is part of my Problem Solving & Logic Building practice, where I am improving my programming fundamentals through practical problems.

📌 Problem Statement

Create a program that calculates the parking fee according to the number of hours a car is parked.

💰 Fee Structure

Parking Duration| Fee
First 2 hours| ₹30
3rd–4th hour| ₹20/hour
5th hour onwards| ₹10/hour
Total above ₹200| 10% discount

🛠️ Technologies Used

- Python 3
- Conditional Statements
- User Input
- Arithmetic Operations
- Basic Problem-Solving Logic

💻 Implementation

rate = 30
h = 20
n = 10

hours = int(input("Enter your hour: "))

if hours == 2:
    print("Fees:", rate)

elif hours >= 3 and hours < 5:
    rate = rate + (hours - 2) * h
    print("Fees:", rate)

elif hours >= 5:
    rate = rate + h + (hours - 5) * n
    print("Fees:", rate)

if rate > 200:
    discount_p = rate * 10 / 100
    rate = rate - discount_p

    print("Discount:", discount_p)
    print("Total price:", rate)

🎯 Learning Objectives

Through this problem, I am practicing:

- Writing conditional logic using "if", "elif"
- Taking and processing user input
- Applying mathematical calculations
- Understanding real-world programming problems
- Building a strong foundation in Python
- Improving logical and problem-solving skills

📂 Project Structure

Problem-solving-/
│
├── README.md
└── problem1.py

🚀 Future Improvements

I plan to improve this project by adding:

- Input validation
- Support for parking durations below 2 hours
- Functions for better code organization
- More parking-related problems
- Additional problem-solving exercises

👨‍💻 About This Repository

This repository contains my Python problem-solving and logic-building exercises. Each problem is designed to help me strengthen my programming fundamentals through hands-on practice.

More problems and solutions will be added as I continue learning.

---

⭐ If you find this project useful, feel free to explore the repository and follow my learning journey.# Problem-solving-