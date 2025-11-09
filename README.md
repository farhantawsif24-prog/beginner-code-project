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
