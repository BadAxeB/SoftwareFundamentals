## Python
Python is a popular general-purpose programming language. In contrast to scracth this language is more binary and text based than visual.It is used in machine learning, web development, desktop applications, and many other fields. For beginners, Python has a simple, easy-to-use syntax.

Python has a very user-friendly and easy to use coding, combined with Visual Code for writing the code.
I was able to make a dog age in dog years calculator using python.

The problem: Write a Python console program that calculates a dog's age in dog's years given human years.
Note: For the first two years, a dog year is equal to 10.5 human years. After that, each dog year equals 4 human years.
Your program should look as follows:
Input a dog's age in human years: 15
The dog's age in dog's years is 73.

'''
Problem: Write a Python console program that calculates a dog's age in dog's years given human years.

Note: For the first two years, a dog year is equal to 10.5 human years. After that, each dog year equals 4 human years.

Your program should look as follows:

Input a dog's age in human years: 15

The dog's age in dog's years is 73.

psudo-code
0. Ask Input a dog's age in Human Years
1. If it is 1 or 2 then multiply the by 10.53
2. If it is 3 and over then subtract 2 out of the variable
3. Multiply that variable by 4 + 21
4. Print Dog's Age

'''

num1 = int(0)

num2 = 10.5

num3 = 2

num4 = 4

num1 = int(input("Enter a dog's age in Human Years "))

if (num1 <= 2):
    Result =  num1 * num2
elif (num1 > 2):
    Result = (num1 - num3)* num4 + (2 * num2)


print("Dog's Age in Dog's Years is", Result)

'''
