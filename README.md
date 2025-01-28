# Conditional statements 
(if, else, and elif) are fundamental programming constructs that allow you to control the flow of your program based on conditions that you specify.

age = int(input("Enter Your Age:"))

if(age>=18):
    print("You can vote and apply for liscense")
else:
    print("Sorry!You are not eligible")    


# Students Grade based on marks
marks = int(input("Enter Your Marks:"))
if(marks>=90 and marks==100):
    print("Grade is A")   
elif(marks>=80 and marks<90):
    print("Grade is B")   
elif(marks>=70 and marks<80):
    print("Grade is C")   
elif(marks>=60 and marks<70):
    print("Grade is D")   

# WAP to check if a number entered by user is odd or even
Number =int(input("Enter the number:"))
if(Number%2==0):
    print(f"This is even number:{Number}") 
else:
    print(f"This is odd number:{Number}")

# WAP to find greatest of 3 numbers entered by user
a = int(input("Enter the number:"))
b = int(input("Enter the number:"))
c = int(input("Enter the number:"))

if(a>b and a>c):
    print(f"This is greatest number:{a}")
elif(b>a  and b>c):
    print(f"This is greatest number:{b}")
elif(c>a and c>b):
    print(f"This is greatest number:{a}")     

