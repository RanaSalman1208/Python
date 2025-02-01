# Loops
it is used to repeat instructions.

# while loop
c = 1
# firts it check the condition it will run until condition remains true
while c <= 5:
    print("Hello")
    c += 1

# print numbers 1 to 100
c = 1
while c <= 100:
    print(c)
    c += 1   
    
# print numbers from 100 to 1
c = 100
while c >= 1:
    print(c)
    c -= 1 
    
# print a multiplication table on number n
n = int(input("Enter number:"))
i = 1
while i<=10:
    print(f"{n} X {i} = {n*i}")
    i += 1
# print the following numbers
num = [1,2,9,16,25,36,49,64,81,100]
idx = 0
while idx < len(num):
    print(num[idx])
    idx += 1
# break statement
it is used to terminate the loop when encountered
i = 1
while i <= 5:
    print(i)
    if(i==4):
        break
    i += 1

# Continue statement
it terminates execution in current iteration and continue the execution with the next iteration.
i = 0
while i <= 5:
    if(i==3):
        i+=1
        continue
    print(i)
    i+=1

# print odd number    
i = 1
while i <= 20:
    if(i%2 != 0):
        i+=1
        continue
    print(i)
    i+=1    

 # print even number
 i = 1
while i <= 20:
    if(i%2 == 0):
        i+=1
        continue
    print(i)
    i+=1


# For loop
it is used for seqeuntial traversal,for traversing list,string and tuples etc

# Example
for items in list:
    print(items)

tup = ("shan",23,456,5.43)
for val in tup:
    print(val)

str = "Apnacollege"
for char in str:
    print(char)    

    
# print the elements of the following list using loop 
list = [1,4,9,16,25,36,49,64,81,100]
for val in list:
    print(val)

# found the value from the list
list = [1,4,9,16,25,36,49,64,81,100]
x = 25
idx = 0
for val in list:
    if(val == x):
        print("Value Found At",idx)
        break
    idx += 1   
    print(val)  

# Range
range function returns a seqeunce of numbers.start from zero(by default) and increment by 1(by default) and stops before a specified number.
(start,stop)
for i in range(2,10):
 print(i) 
 
(start,stop,stepsize)
for i in range(2,10,2):
 print(i) 


# practice
# using for and range()
# print numbers from 1 to 100

for i in range(1,101):
    print(i) 

# print numbers from 100 to 1
for i in range(100,0,-1):
    print(i) 

# WAP to find the sum of first n numbers
n = 6
sum = 0
for i in range(1,n+1):
    sum += i
    
print("sum is:",sum)

# WAP to find the sum of first n numbers(using while loop)
n = 6
sum = 0
i = 1
while i<=n:
    sum += i
    
print("sum is:",sum)

# WAP to find factorial of first n natural numbers(using while loop)

n = 5
f = 1
i = 1
while i<=n:
    f *= i
    i += 1
print(f)  

# WAP to find factorial of first n natural numbers(using for loop)
n = 5
fac = 1
for i in range(1,n+1):
    fac *= i

print(fac)    
