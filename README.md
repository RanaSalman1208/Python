# Dictionary 
It is used to store data value in  key:value pairs.it is unordered and mutubale(Changeabe) and dont allow duplicate keys

# Example
dict = {
"Name":"Salman",
    "age" : 23,
    "Marks":[76,78,74]
}
print(dict)

# Dictionary is mutable(Changeable)
dict = {
    "Name":"Salman",
    "age" : 23,
    "Marks":[76,78,74]

}
dict["Name"] = "Faiq"
print(dict)
print(type(dict))

# Nested Dictionary

student = {
    "Name":"Saim",
    "Marks":{
        "DSA":73,
        "ITC":82,
        "SE":78
    }
}
print(student)

# Dictionary Methods

info = {
    "Name":"Salman",
    "Roll-no":"B-26997",
    "Dep":"CS",
    "Sem":7 
}
# Key Method
# it returns all the key in Dictionary
print(info.keys())

# Value Method
# it returns all the value in Dictionary
print(info.values())

# item method
# it returns all the key,values pairs as tuple
print(info.items())

# get method
# it returns the key according to value
print(info.get("Name"))

# Update method
# it insert specified items to the dictionary
new_dict = {"City":"Lahore"}
info.update(new_dict)
print(info)

# Practice

# store the following "table":"a piece of furniture","cat":"a small animal"in a dictionary
doc = {
    "table":["a piece of furniture","list of facts & figures"],
    "cat":"a small animal"
}
print(doc)

# wap to enter marks of 3 subjects from the user and store them in a dictionary.
# start with an empty dictionary & add one by one.use subject name as key & marks as value

marks = {}
a = int(input("enter phy:"))
marks.update({"phy": a})
b = int(input("enter chem:"))
marks.update({"chem": b})
c = int(input("enter comp:"))
marks.update({"comp": c})
print(marks)


# Sets
it is a collection of unordered items.each element in the set must be unique and mutable.

# example
num = {1,22,4,5,4,56}
print(type(num))
print(num)

# set method

# Add method
# it adds an element

collection = set()
collection.add(1)
collection.add("Salman")
collection.add(7.878)
print(collection)

# remove mwthod
# it remove the element

collection = set()
collection.add(1)
collection.add("Salman")
collection.add(7.878)

collection.remove(1)
print(collection)


# clear method
# it empties the set

collection = set()
collection.add(1)
collection.add("Salman")
collection.add(7.878)

collection.clear()
print(len(collection))


# pop method
# it removes a random value

col = {"Hi","salman","how are you"}
print(col.pop())
print(col.pop())

# union method
# combines both set values and returns new

u1 = {1,2,3,4,5,}
u2 = {6,7,8,9,}
print(u1.union(u2))

# intersection method
# combines common value and returns new

set1 = {1,2,3,4,5,}
set2 = {6,7,8,9,4,6,9,8}
print(set1.intersection(set2))

# you are given a list of subjects fr student.assume one classroom is required for 1 subject how many classroom are needed by all students.

subjects = {
    "python","java","c++","python","javascript"
    "python","java","c++","c"
}
print(len(subjects))
print(subjects)
