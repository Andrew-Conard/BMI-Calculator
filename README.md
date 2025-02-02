# BMI Calculator

## Overview
This is a simple BMI (Body Mass Index) calculator implemented in Python using a Jupyter Notebook. The program prompts the user to enter their name, weight (in pounds), and height (in inches), then calculates their BMI and categorizes it based on standard BMI ranges.

## How It Works
- The user enters their **name**.
- The user inputs their **weight in pounds**.
- The user inputs their **height in inches**.
- The program calculates BMI using the formula:
  
  ```python
  BMI = round((weight * 703) / (height ** 2), 2)
  ```
- Based on the BMI value, the user is classified into one of the following categories:
  - **Underweight** (BMI < 18.5)
  - **Normal weight** (BMI 18.5 - 24.9)
  - **Overweight** (BMI 25 - 29.9)
  - **Obese** (BMI 30 - 34.9)
  - **Severely Obese** (BMI 35 - 39.9)
  - **Morbidly Obese** (BMI 40 and above)

## Installation & Usage
### Requirements
- Python 3.x
- Jupyter Notebook (optional, for running the `.ipynb` file)

### Running the Program
1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/your-username/BMI-Calculator.git
   ```
2. Navigate to the project folder:
   ```sh
   cd BMI-Calculator
   ```
3. Open Jupyter Notebook and run the `.ipynb` file:
   ```sh
   jupyter notebook
   ```
4. Run the notebook and enter your details when prompted. The BMI will be calculated and categorized accordingly.

## Example Output
```
Enter your name: John
Enter your weight in pounds: 180
Enter your height in inches: 70
Your BMI is: 25.8
John, you are overweight.
```

## Improvements Implemented
- **Input Validation**: Prevents crashes from non-numeric input.
- **Float Inputs**: Allows decimal values for more accurate BMI calculations.
- **Formatted Output**: Rounds BMI to two decimal places for readability.
- **Refactored BMI Classification**: Simplified logic for categorizing BMI values.

## Possible Future Enhancements
- Create a GUI version using Tkinter or Streamlit.
- Store user BMI history in a database.
- Provide health recommendations based on BMI results.

## Author
- Andrew Conard
