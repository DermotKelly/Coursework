# Dermot Kelly
# Coursework
# Higher Diploma Data Analytics GMIT

# This is a program that asks the user to input any positive integer and outputs the sum of all numbers between one and that number.


x = int(input('Please enter a posative number: '))   # Asks user to input posative number and int converts string to integer

answer = 0

for i in range(x,0,-1):                             # start value is user input ending value is 0 and step is -1
    answer = answer + i

print ("The sum of all numbers between 1 and",x,"=",answer,)         # Prints out the answer
