# Consider two numbers a and b.The value should be taken by the user. Now write a program to compute if a to the power b (a^b) is even or odd.
a = int(input("Enter a number: "))
b = int(input("Enter another number: "))
c = a ** b
if c%2 == 0:
  print("Even")
else:
  print("Odd")
