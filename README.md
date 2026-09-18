# java-project-23bce11798
a calorie tracker app built using java.
NAME: SAI VIGNESH S
REG NO. 23BCE11798

# Calorie Needs Calculator (Java Console App)

A simple Java-based console application that helps you calculate your daily calorie needs based on your age, gender, weight, height, and activity level using the Basal Metabolic Rate (BMR) formula.

---

## Features

- Calculates Basal Metabolic Rate (BMR) using gender-specific formulas
- Adjusts daily calorie requirements based on activity levels:
  - Sedentary
  - Moderate
  - Active
- Validates all user inputs for accuracy and reliability
- Easy-to-use console interface

---

## How It Works

1. The user is prompted to enter:
   - Age (in years)
   - Gender (Male/Female)
   - Weight (in kilograms)
   - Height (in centimeters)
   - Activity level (Sedentary, Moderate, Active)

2. The app calculates your Basal Metabolic Rate (BMR) using the Harris-Benedict equation:

### BMR Formulas:

- For Men:  
  `BMR = 88.362 + (13.397 × weight in kg) + (4.799 × height in cm) − (5.677 × age in years)`

- For Women:  
  `BMR = 447.593 + (9.247 × weight in kg) + (3.098 × height in cm) − (4.330 × age in years)`

3. Your Total Daily Energy Expenditure (TDEE) is calculated by multiplying the BMR with an activity multiplier:

### Activity Multipliers:

| Activity Level | Multiplier |
|----------------|------------|
| Sedentary      | × 1.2      |
| Moderate       | × 1.55     |
| Active         | × 1.725    |

4. The app outputs your estimated daily calorie needs to maintain your current weight.

---

## Technologies Used

- Java
- Java Scanner (for reading console input)
- Command-line Interface (CLI)

---


### Requirements:
- Java 8 or higher
- Any Java IDE or terminal with `javac` and `java` installed

### To Run the Application:

1. Clone or download the repository.
2. Navigate to the project directory in the terminal.
3. Compile the program:

```bash
javac CalorieCalculator.java
