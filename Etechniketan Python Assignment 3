# ===========================================================
#               ETECHNIKETAN PYTHON ASSIGNMENT 3
#                 Coding Questions (8 - 18)
# ===========================================================


# ===========================================================
# Question 8
# Create a function named 'introduce' that takes:
# 1. name - positional argument
# 2. age - default argument with value None.
#
# If age is provided:
# introduce("John",20)
# Output:
# My name is John. I am 20 years old.
#
# If age is not provided:
# introduce("John")
# Output:
# My name is John. My age is secret.
# ===========================================================

print("\n========== Question 8 ==========")

def introduce(name, age=None):
    if age is None:
        print(f"My name is {name}. My age is secret.")
    else:
        print(f"My name is {name}. I am {age} years old.")

introduce("John",20)
introduce("John")


# ===========================================================
# Question 9
# Create a function drop_minimum() that takes variable length
# arguments (*args). Remove the minimum value and return the list.
# ===========================================================

print("\n========== Question 9 ==========")

def drop_minimum(*args):
    numbers=list(args)
    numbers.remove(min(numbers))
    return numbers

print(drop_minimum(5,-2,8,4,-5,7,10))


# ===========================================================
# Question 10
# Create find_max(a,b,c) using max().
# Create main() that accepts three integers
# and prints the maximum value.
# ===========================================================

print("\n========== Question 10 ==========")

def find_max(a,b,c):
    return max(a,b,c)

def main():
    x=int(input("Enter first number: "))
    y=int(input("Enter second number: "))
    z=int(input("Enter third number: "))

    print("Maximum Value =",find_max(x,y,z))

main()


# ===========================================================
# Question 11
# Write a lambda function to add two numbers.
# ===========================================================

print("\n========== Question 11 ==========")

add=lambda a,b:a+b

print("Addition =",add(10,20))


# ===========================================================
# Question 12
# Write a lambda function that converts Celsius
# to Fahrenheit.
#
# Formula:
# Fahrenheit = Celsius * 9/5 + 32
# ===========================================================

print("\n========== Question 12 ==========")

fahrenheit=lambda c:c*9/5+32

print("25°C =",fahrenheit(25),"°F")


# ===========================================================
# Question 13
# Create student.txt
# Write three lines into it.
# Use exception handling.
# ===========================================================

print("\n========== Question 13 ==========")

try:
    with open("student.txt","x") as file:
        file.write("Python is easy to learn.\n")
        file.write("File handling is important.\n")
        file.write("Practice makes perfect.")

    print("student.txt created successfully.")

except FileExistsError:
    print("student.txt already exists.")

except Exception as e:
    print("Error:",e)


# ===========================================================
# Question 14
# Read student.txt
# (a) Print all contents
# (b) Print line by line
# ===========================================================

print("\n========== Question 14 ==========")

with open("student.txt","r") as file:
    print(file.read())

print("\nLine by Line:")

with open("student.txt","r") as file:
    for i,line in enumerate(file,start=1):
        print(f"Line {i}: {line.strip()}")


# ===========================================================
# Question 15
# Count total words in student.txt
# ===========================================================

print("\n========== Question 15 ==========")

with open("student.txt","r") as file:
    words=file.read().split()

print("Total words =",len(words))


# ===========================================================
# Question 16
# Append the following line:
# Python file handling becomes simple with practice.
# ===========================================================

print("\n========== Question 16 ==========")

with open("student.txt","a") as file:
    file.write("\nPython file handling becomes simple with practice.")

print("Line added successfully.")


# ===========================================================
# Question 17
# Create a list:
# numbers=[7,4,0,-2,3]
#
# Ask user for an index.
# Handle IndexError.
# ===========================================================

print("\n========== Question 17 ==========")

numbers=[7,4,0,-2,3]

print(numbers)

try:
    index=int(input("Enter index: "))
    print("Value =",numbers[index])

except IndexError:
    print("Invalid Index!")

except ValueError:
    print("Please enter a valid integer.")


# ===========================================================
# Question 18
# Create calculator functions:
# add()
# subtract()
# multiply()
# divide()
#
# (Normally these functions are written in calculator.py
# and imported into main.py. They are included together
# here because this is a single-file version.)
# ===========================================================

print("\n========== Question 18 ==========")

def add(a,b):
    return a+b

def subtract(a,b):
    return a-b

def multiply(a,b):
    return a*b

def divide(a,b):
    return a/b

print("Addition =",add(20,10))
print("Subtraction =",subtract(20,10))
print("Multiplication =",multiply(20,10))
print("Division =",divide(20,10))


print("\n========== Assignment Completed ==========")
