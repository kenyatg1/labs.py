# labs.py
Lab 1 Exercise
#Exercise 1 - prompt the user to enter string
user_input = input("Please enter a string:")
print("You have now entered:")

#Exercise 2 - Prompt the user to enter a number. After the user enters a number, add 1 to the number and output it back to the console.
#Prompt the user to enter the first number
num1 = float(input("Please enter the first number: "))
# Prompt the user to enter the second number
num2 = float(input("Please enter the second number: "))
# Calculate the sum of the two numbers
sum_of_numbers = num1 + num2
result = user_input + 1
# Output the sum back to the console
print("The sum is", num1, "and", num2, "is", sum_of_numbers)

#EXERCISE 3: Adding a number to a float - Prompt the user to enter a number. After the user enters a number, add .5 to the number and output it back to the console.
#Prompt the user to enter a number
user_input = float(input("Please enter a number: "))
# Add .5 to the entered number
result = user_input + .5
# Output the result back to the console
print("The number plus .5 is:", result)

#EXERCISE 4: Adding Two Floats - Prompt the user to enter two numbers. After the user enters the numbers, add them together and output the sum back to the console.
# Prompt the user to enter the first number
num1 = float(input("Please enter the first number: "))
# Prompt the user to enter the second number
num2 = float(input("Please enter the second number: "))
# Add the two numbers
sum_of_numbers = num1 + num2
# Output the sum
print("The sum of", num1, "and", num2, "is", sum_of_numbers)

#EXERCISE 5: Multiplying Floats - Prompt the user to enter two numbers. After the user enters the numbers, multiply them and output the product back to the console.
# Prompt the user to enter the first number
num1 = float(input("Enter the first number: "))
# Prompt the user to enter the second number
num2 = float(input("Enter the second number: "))
# Multiply the two numbers
product = num1 * num2
# Output the product
print("The product of", num1, "and", num2, "is", product)
