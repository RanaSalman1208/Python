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
