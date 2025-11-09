#1 Consider two numbers a and b.The value should be taken by the user. Now write a program to compute if a to the power b (a^b) is even or odd.
a = int(input("Enter a number: "))
b = int(input("Enter another number: "))
c = a ** b
if c%2 == 0:
  print("Even")
else:
  print("Odd")

#2 Write a program which takes three 4 digits numbers as inputs and the program prints the maximum number of those numbers as output.
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
num3 = int(input("Enter the third number: "))
if num1>num2 and num1>num3:
  print(f"{num1} is the maximum number ")
elif num2>num1 and num2>num3:
  print(f"{num2} is the maximum number ")
elif num3>num2 and num3>num1:
  print(f"{num3} is the maximum number ")

#3 Write a Python program which takes a number as input and check if the number is positive, negative or zero.
num = float(input("Enter a number: "))
if num>0:
  print("The number is positive. ")
elif num<0:
  print("the number is negative. ")
else:
  print("The number is zero. ")

  #4 Write a Python program to take a character as input and check if the character is a vowel or consonant.
user_input = input("Enter a character: ")
if user_input == "a" or user_input == "e" or user_input == "i" or user_input == "o" or user_input == "u" or user_input =="A" or user_input =="E" or user_input =="I" or user_input =="O" or user_input =="U":
 print("Vowel")
else:
  print("Consonant")

  #5 For this problem, you will need to take two integers a, b and a caracter c to represent an operation. The caracter can be +, -, *, / or % (for modulus). You will need to perform the operation on a and b and print the result. If the operation is not one of the above, print "Invalid operation"
  #It's a calculator
a = int(input("Enter a number: "))
b = int(input("Enter another number: "))
c = input("Enter an operator: ")
if c == '+':
  result = a + b
  print(result)
elif c == '-':
  result = a - b
  print(result)
elif c == '*':
  result = a * b
  print(result)
elif c == '/':
  result = a / b
  print(result)
elif c == '%':
  result = a % b
  print(result)
else:
  print("Invalid")
