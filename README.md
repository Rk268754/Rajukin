def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
num = int(input("Enter a number to calculate its factorial: "))
if num < 0:
    print("Factorial cannot be calculated for negative numbers.")
else:
    print("Factorial of", num, "is", factorial(num))
