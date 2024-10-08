# Code-Bug-Week-7

def greet(name): 
    print("Hello, "  + "name" + "!")
          
def add_numbers(a, b): 
    return a+ b

#MAIN stuff and variables
name = input("Enter your name: ") 
greet(name)

num1 = int(input("Enter the first number "))
num2 = int(input("Enter the second number: "))
          
result = add_numbers(num1, num2)
print("The sum is: " , result)
