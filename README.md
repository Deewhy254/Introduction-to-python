# What is programming ?

Programming is a way to `instruct the computer to perform various tasks`

# What is python programming?

Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically-typed and garbage-collected. It supports multiple programming paradigms, including structured, object-oriented and functional programming by <span style="color:red"> Wikipedia</span>

# Application of Python Programming Language

 1. Web Development
 2. Game Development
 3. Machine Learning and Artificial Intelligence
 4. Data Science and Data Visualization
 5. Desktop GUI
 6. Web Scraping Applications
 7. Business Applications
 8. Audio and Video Applications
 9. CAD Applications
 10. Embedded Applications

### Python Variable

Variables are containers for storing data values.

## Variable creation

a = "Python"
b = 40.7
x = 2
y = 4

print(a)
print(b)
print(x)
print(y)

3  = "Python"
print(3)

_ = "Python"
print(_)

NUM1 = 23
num2 = 40
total = NUM1 + num2
print(total)

## Rules for Naming Variable in Python
 - A variable name must start with a letter or the underscore character
 - A variable name cannot start with a number
 - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
 - Variable names are case-sensitive (age, Age and AGE are three different variables)
 - A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume).

age = 4
print(age)

Age = 70
print(age)

name_of_student = 'Victor'
print(name_of_student)

## many value to a variable name

a,b,c = 40, 30, 20

print(a)
print(b)
print(c)

## outputing multiple variable 
items1 = 'book '
items2 = 'pen '
items3 = 'bag'

print(items1+items2+items3)
print(items1,items2,items3)

#print(items1)
#print(items2)
#print(items3)

## Built-in Data Type in Python 

In programming, data type is an important concept.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

 - Text Type:	str
 - Numeric Types:	int, float, complex
 - Sequence Types:	list, tuple, range
 - Mapping Type:	dict 
 - Set Types:	set
 - Boolean Type:	True or False 

Name = "Emmanuel"
School = "OAU"
Course_of_study = "Python"
print(Name)
print(type(Name))
print(School)
print(type(School))
print(Course_of_study)
print(type(Course_of_study))

## Numeric type 
 - int
 - float
 - complex

# Integer data type - whole number 
num1 = 34
# decimal - float data type 
num2 = 49.5
num3 = 3 + 5j
print(num1)
print(type(num1))
print(num2)
print(type(num2))
print(num3)
print(type(num3))

# List

numbers = [1,2,3,4,5,6,7,8,9,90,100]
names = ["Miracle", "Oluwaseun", "Victor", "Emmanuel", "Oyindamola"]
print(numbers)
print(names)
print(type(numbers))
print(type(names))

# Tuple

numbers = (1,2,3,4,5,6,7,8,9,90,100)
names = ("Miracle", "Oluwaseun", "Victor", "Emmanuel", "Oyindamola")
print(numbers)
print(names)
print(type(numbers))
print(type(names))

# Range

r = range(1,20)
print(r)
print(type(r))

for i in range(1,20):
    print(i)

# Set

s = {1,2,3,4,4,4,4,'Aderonke', 'victor'}
print(s)

## Dictionary

d = {"name": "Dayo", "AGE": 25, "Course":"Python"}
print(d)
print(type(d))


print(d["name"])

d["name"]="Dayo"

print(d)

## Boolean ( True or False )

print(2 == 2)

print(2 > 3)

print(4<5)

# Python Conditions and If statements

Python supports the usual logical conditions from mathematics:

 - Equals: `a == b`
 - Not Equals: `a != b`
 - Less than: `a < b`
 - Less than or equal to: `a <= b`
 - Greater than: `a > b`
 - Greater than or equal to: `a >= b`
 
These conditions can be used in several ways, most commonly in "if statements" and loops.

An "if statement" is written by using the `if` keyword and other conditional statement are `elif` and `else`

## Example 

## if 
## elif
## else

Bootcamp_Sponsor = input("Enter the name of this Bootcamp Sponsor: ")

if Bootcamp_Sponsor == "Microsoft":
    print(Bootcamp_Sponsor," is the one sponsoring this Bootcamp")
else:
    print("i'm not aware of the name of the Sponsor of this Bootcamp")

colour = input("Enter any traffic light colour of your choice: ")

if colour == 'yellow':
    print("The vehicle should get set")
elif colour == 'green':
    print("The vehicle should move")
elif colour == 'red':
    print("The vehicle should stop")
else:
    print("I'm not familiar with the colour you gave")

original_number = 20

guess = int(input("Guess a number: "))

if guess < original_number:  
    print("Your guess is less than the original number")
elif guess > original_number:
    print("Your guess is greater than the original number")
elif guess == original_number:
    print("You guess right")
else:
    print("ohhh sorry, you really tried but try again")

# Loop In Python
## Type of loop in python
 - for loop
 - while loop

# For loop

fruits = ["apple", "banana", "cherry"]

#print(fruits)

for i in fruits:
    print(i)

for i in range(10):
    print(i)

## While loop

i = 0

while i<=10:
    
    print(i)
    
    i +=3

i = 100 #initialization

while i <= 0:  # condition
    print(i)
    
    i  -= 1 # Increment/ decrement 

print("hello")

i = 2.0

while i <= 20:
    print(i)
    i+=2

password = " "


i = 0 # initialization

while i <= 20: # condition
    print(i)
    
    i  += 3 # Increment or decrement 

# Function in Python

A function is a block of code which only runs when it is called.

You can pass data, known as parameters, into a function.

A function can return data as a result.

### Examples

print("hello world")

### Calling a Function
To call a function, use the function name followed by parenthesis:

def school():
    return ("This is Abayomi from Techy Jaunt")

print(school())

def my_function():
    return("Hello from a function, this is second month of this Techy Jaunt Data analysis class")

print(my_function())

### Arguments
##### Information can be passed into functions as arguments.

Arguments are specified after the function name, inside the parentheses. You can add as many arguments as you want, just separate them with a comma.

The following example has a function with one argument (fname). When the function is called, we pass along a first name, which is used inside the function to print the full name:

num1 = 2
num2 = 4
num3 = 6

total = num1 + num2 + num3

print(total)

def sum_of_three_numbers(num1, num2, num4):
    total = num1 + num2 + num4
    return total

print(sum_of_three_numbers(30,40, 50))

print(sum_of_three_numbers(55,70, 90))

def greet_users(fname):
    return(fname + ", Hello and how are you? ")


print(greet_users("Alexander"))
print(greet_users("Emmanuel"))
print(greet_users("Oyindamola"))
print(greet_users("Abayomi"))
print(greet_users("Gbemiga"))
print(greet_users("Aderonke"))

def student_details(name,age,course):
    details = name + " " , age , " " + course
    return details

print(student_details("Dada",26,"Data Analysis"))

firstname = 'Dayo '
lastname = 'Dada'

fullname = firstname + lastname

print(fullname)

def fullName(fname, lastname):
    full = fname + lastname
    return full

print(fullName("Dayo ", "Dada"))

# Object Oriented Programming 

### Python Classes and Objects

# Python Classes/Objects
Python is an object oriented programming language.

Almost everything in Python is an object, with its properties and methods.

A Class is like an object constructor, or a "blueprint" for creating objects.


# Create a Class


# Example
Create a class named MyClass, with a property named x:

class MyClass:
  x = 69

print(MyClass)

Create an object named p1, and print the value of x:



a = MyClass()
print(a.x)

class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("Abayomi", 40)

print(p1.name)
print(p1.age)

## Python Inheritance
Inheritance allows us to define a class that inherits all the methods and properties from another class.

Parent class is the class being inherited from, also called base class.

Child class is the class that inherits from another class, also called derived class.

# Create a Parent Class
Any class can be a parent class, so the syntax is the same as creating any other class:

## Example
Create a class named `Person`, with `firstname` and `lastname` properties, and a `printname` method

class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)

#Use the Person class to create an object, and then execute the printname method:

x = Person("John", "Doe")
x.printname()

class Student(Person):
  def __init__(self, fname, lname, year):
    super().__init__(fname, lname)
    self.graduationyear = year

  def welcome(self):
    print("Welcome", self.firstname, self.lastname, "to the class of", self.graduationyear)

If you add a method in the child class with the same name as a function in the parent class, the inheritance of the parent method will be overridden.

