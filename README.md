# Akech Dau Atem
# SCT211-0535/2022

# SimpleCalculator 

import datetime
# Input two integers
num1 = int(input("Enter the first integer: "))
num2 = int(input("Enter the second integer: "))

# Perform arithmetic operations
sumResult = num1 + num2
difference = num1 - num2
product = num1 * num2
division = num1 / num2 

# Display results
print(f"Sum: {sum}")
print(f"Difference: {difference}")
print(f"Product: {product}")
print(f"Division: {division}")

# Input the year of birth
year_of_birth = int(input("Enter your year of birth: "))

# Get the current date
current_date = datetime.date.today()

# Calculate the age
age_in_years = current_date.year - year_of_birth
age_in_months = (current_date.year - year_of_birth) * 12 + current_date.month
age_in_days = (current_date - datetime.date(year_of_birth, current_date.month, current_date.day)).days

# Display the age
print(f"Your age is {age_in_years} years.")
print(f"Your age is {age_in_months} months.")
print(f"Your age is {age_in_days} days.")
