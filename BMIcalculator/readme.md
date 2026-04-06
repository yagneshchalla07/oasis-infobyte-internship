BMI Calculator (Python)

A simple Body Mass Index (BMI) Calculator written in Python. This program takes user input for weight and height, calculates BMI, and categorizes the result while handling invalid inputs.

📌 Features
Accepts user input for:
Weight (in kilograms)
Height (in meters)

Calculates BMI using the formula:

𝐵
𝑀
𝐼
=
𝑤
𝑒
𝑖
𝑔
ℎ
𝑡
ℎ
𝑒
𝑖
𝑔
ℎ
𝑡
2
BMI=
height
2
weight
	​

Displays BMI rounded to 2 decimal places
Classifies BMI into categories:
Underweight
Normal weight
Overweight
Obese
Includes error handling:
Prevents negative or zero values
Handles non-numeric input
🚀 How to Run
Make sure Python is installed on your system.
Clone this repository or download the file.
Open a terminal or command prompt.
Run the program:
python bmi_calculator.py
💻 Example Output
Enter your weight in kg: 70
Enter your height in meters: 1.75
Your BMI is: 22.86
Category: Normal weight
⚠️ Error Handling

The program handles common input errors:

 Non-numeric input → Shows: Invalid input! Please enter numbers only.
 Zero or negative values → Shows: Please enter positive values only.
 File Structure
bmi-calculator/
│── bmi_calculator.py
│── README.md
📖 BMI Categories
BMI Range	Category
< 18.5	Underweight
18.5 – 24.9	Normal weight
25 – 29.9	Overweight
≥ 30	Obese
🛠️ Technologies Used
Python (Basic Input/Output, Exception Handling)
✨ Future Improvements
Add GUI using Tkinter
Support unit conversion (lbs, feet/inches)
Save results to a file
Add multiple user tracking
