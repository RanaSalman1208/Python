# List & Tuple

# List:
A list is a built-in data type that can store value of different data types(Integers,float,string etc).it is mutuable(It can be change)

# Example
marks = [98,"Salman",48,"Imran",45,"Mehboob"]
print(marks)
print(type(marks))

# List Methods

list=[2,34,5,6,7]

# Append Method
# it adds one element at the end
list.append("Salman")

# Sort Method
# it sort list in ascending order
print(list.sort())

# reverse sort Method
# it sort list in descending order
list.sort(reverse=True)

# reverse method
# it reverse the list
list.reverse()

# insert method
# it insert element at index

list.insert(3,"Harry")
print(list)

list1 = [1,2,3,4,5,6,7,4,4,48,9]

# remove method
# it remove first occurence of element
list1.remove(4)

# Pop method
# remove element at index
list1.pop(0)

print(list1)


# Tuple:
it is a built-in data type.it also work same as list.it let us to create immutable(Cannot Change) 
sequence of values.we use parenthesis to create tuple.

# Example
tup = (1,2,3,5,6,7,8)
print(tup)

# Tuple
tup = (1,2,3,5,6,7,8,2,2)
print(type(tup))

# tuple method

# index method
# it returns index of first occurence
print(tup.index(2))

# Count method
# it count the occurences of element
print(tup.count(2))


# WAP to ask user to enter names of their 3 favourite movies & store them in a list

Movies=[]
mov1 = input("Enter 1st Movie:")
mov2 = input("Enter 2nd Movie:")
mov3 = input("Enter 3rd Movie:")

Movies.append(mov1)
Movies.append(mov2)
Movies.append(mov3)

print(Movies)

# WAP to check if a list contains a palindrome of elements.

palindrome = [1,2,1]
palindrome1 = palindrome.copy()
palindrome1.reverse()

if(palindrome1==palindrome):
    print("Palindrome")
else:
    print("Not Palindrome")

list = ["m","a","a","m"]
list1=list.copy()
list1.reverse()
if(list1==list):
    print("Palindrome")
else:
    print("Not Palindrome")

    
# WAP to count number of students with A grade in the following and Also sort them in A to D

grade = ["C","D","A","A","B","B","B"]
grade.sort()
print(grade.count("A"))    
print(grade)
