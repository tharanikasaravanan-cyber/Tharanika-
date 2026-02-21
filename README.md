(1):
Name: Tharanika.S
Register Number:712525205079
class:B.Tech-IT(B)
Subject: python For Data Science And Visualization

(2):
# Function to check if a number is even or odd
def check_even_odd(number):
    if (number % 2) == 0:
        return "even"
    else:
        return "odd"

# Main part of the program to handle user input
if __name__ == "__main__":
    # Take integer input from the user
    try:
        user_input = int(input("Enter an integer: "))
        
        # Check the number and get the result
        result = check_even_odd(user_input)
        
        # Display the result
        print(f"The number {user_input} is {result}.")
    except ValueError:
        print("Invalid input. Please enter a valid integer.")

  (3):
  # Python program to find the largest of three numbers
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number: "))

# Conditional logic
if (num1 >= num2) and (num1 >= num3):
    largest = num1
elif (num2 >= num1) and (num2 >= num3):
    largest = num2
else:
    largest = num3

print("The largest number is:", largest)


(4):
# Program to calculate the factorial of a number using a loop

# Take a number as input from the user
number = int(input("Enter an integer: "))

# Initialize factorial to 1
factorial = 1

# Check if the number is negative, zero, or positive
if number < 0:
    print("Factorial does not exist for negative numbers.")
elif number == 0:
    print("The factorial of 0 is 1.")
else:
    # Calculate factorial using a for loop
    for i in range(1, number + 1):
        factorial = factorial * i
    print(f"The factorial of {number} is {factorial}.")

