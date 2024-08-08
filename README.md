#Exercise 1 - prompt the user to enter string

user_input = input("Please enter a string:")
print("You have now entered:")

#Exercise 2 - Prompt the user to enter a number. After the user enters a number, add 1 to the number and output it back to the console.

num1 = float(input("Please enter the first number: "))
num2 = float(input("Please enter the second number: "))
sum_of_numbers = num1 + num2
result = user_input + 1
print("The sum is", num1, "and", num2, "is", sum_of_numbers)

#Exercise 3: Adding a number to a float - Prompt the user to enter a number. After the user enters a number, add .5 to the number and output it back to the console.

user_input = float(input("Please enter a number: "))
result = user_input + .5
print("The number plus .5 is:", result)

#Exercise 4: Adding Two Floats - Prompt the user to enter two numbers. After the user enters the numbers, add them together and output the sum back to the console.
num1 = float(input("Please enter the first number: "))
num2 = float(input("Please enter the second number: "))
sum_of_numbers = num1 + num2
print("The sum of", num1, "and", num2, "is", sum_of_numbers)

#Exercise 5: Multiplying Floats - Prompt the user to enter two numbers. After the user enters the numbers, multiply them and output the product back to the console.
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
product = num1 * num2
print("The product of", num1, "and", num2, "is", product)

#Exercise 6: Dividing integers - Use the int type here. Prompt the user to enter two numbers. After the user enters the numbers, divide them and output the result back to the console.
Prompt the user to enter the first number
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
    
result = int(num1) // int(num2)
print("The result of dividing", int(num1), "by", int(num2), "is", result)
except ValueError:
print("Invalid input. Please enter valid numbers.")
except ZeroDivisionError:
print("Error: Division by zero is not allowed.")

