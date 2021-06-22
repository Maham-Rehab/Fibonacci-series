# Fibonacci-series
WAP to print a Fibonacci series
num1 = 0
num2 = 1
print(num1)
print(num2)
for x in range(10):
    num3 = num1+num2
    print(num3)
    num1=num2
    num2=num3
