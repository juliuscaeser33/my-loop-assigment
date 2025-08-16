
# Task 1
# The user types in two numbers (start and end points of the range).
#  Analyze all the numbers in this range as follows: if the number is a multiple of 7,
#  print it.
num1=int(input("enter the number:"))
num2=int(input("enter the number:"))
for number in range(num1,num2+1):
    if number%7==0:
        print(number)


# Task 2
# The user types in two numbers (start and end points of the range).
#  Analyze all the numbers in this range. Print the following:

# All numbers in the range;
# All numbers in the range in descending order;
# All numbers that are multiples of 7;
# How many numbers are multiples of 5.
num1=int(input("enter the number:"))
num2=int(input("enter the number:"))
for number in range(num1,num2+1):
    print(number)
for number in range(num2,num1-1,-1):
    print(number)

for number in range(num1,num2+1):
  if number%7==0:
    print(number)
for number in range(num1,num2+1):
  if number%5==0:
   print(f"Total numbers that are multiples of 5: {number}")



# Task 3
# The user types in two numbers (start and end points of the range).
#  Analyze all the numbers in this range. 
# The output should be according to the rules specified below.
# If the number is a multiple of 3 (divisible by 3 without remainder), print the word Fizz.
#  If it is a multiple of 5, print Buzz.
#  If it is a multiple of 3 and 5, print Fizz Buzz.
#  If the number is not a multiple of 3 or 5, print the number its
num1=int(input("enter the number:"))
num2=int(input("enter the number:"))
for number in range(num1,num2+1):
 if number%3==0 and number%5==0:
    print("Fizz Buzz")
 elif number%3==0:
    print("Fizz")
 elif number%5==0:
    print("Buzz")
else:
    print(number)



