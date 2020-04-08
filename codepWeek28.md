Friday, April 3rd 2020

## Programming practice with python

# Question I:

Write a Python program that accepts a string and calculate the number of digits and letters. 

Sample Input : Python 3.2
Expected Output :
Letters 6
Digits 2

# Here's the solution:

```.py
s = input("Input your string:\n)
d=l=0
for c in s:
  if c.isdigit():
    d=d+1
  elif c.isalpha():
    l=l+1
  else:
      pass
print("digits", d)
print("letters", l)

```


# Question II:

With a given integral number n, write a program to generate a dictionary that contains (i, i*i) such that i is an integral number between 1 and n (both included). The program should print the dictionary.

Sample Input
8
Expected Output
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}

# SOLUTION:

```.py
#take the user input of number
n = int(input("Write down your integral number"))

#create a dictionary of squares
squares = { i : i*i for i in range (0, n+1)}

#print the dictionary
print(squares)

```


# Question III:

Write a program that accepts a comma separated sequence of words as input and prints the words in a comma-separated sequence after sorting them alphabetically.

Sample Input
without,hello,bag,world

Expected Output
bag,hello,without,world

# Solution of the third question:

```.py
items = [ x for x in input("Write down your data to be sorted").split(',')]
items.sort()
print("Your data sorted look like",','.join(items))

```


# Question IV:

Define a class which has at least two methods: 

getString: to get a string from console input
printString: to print the string in upper case.

Also please include a simple test function to test the class methods by instantiating an object.

# SOlution:

```.py
class ChristPrecieux(object):
self.s = ""

#define the initializer
  def __init__(self):
  self.s = ""
  
  def getString(self):
  self.s = input("Write in the box your message")
  
  def printString(self):
  print("Your message in upper case is",self.s.upper())
  
  StrObj = ChristPrecieux()
  StrObj.getString()
  StrObj.printString()
  
  ```


# Question V:

Write a Python program to calculate a dog's age in dog's years. Go to the editor
Note: For the first two years, a dog year is equal to 10.5 human years. After that, each dog year equals 4 human years.

Sample Input
15                                    
Expected Output
The dog's age in dog's years is 73

# My solution is:

```.py
h_age = input("Include the dog's age in years")

#need the if statements
if h_age < 0:
   print("dog's age must be ≤ 0")
  exit()
elif h_age ≤ 2 :
    d_age = h_age * 10.5
else:
    d_age = 25 + ( h_age -2)*4
    
print("the dog's age in years is", d_age)

```






## Syllabus Questions:
Q1. Outline one usability issue associated with the design of mobile devices.

  Among the usability issue associated with the design of mobile devices,the one I would quote is "Screen light"

Q2. Construct a truth table for the following Boolean expression.

  

Q3. Define the term protocol.

Protocol, in computer science, a set of rules or procedures for transmitting data between electronic devices, such as computers. In order for computers to exchange information, there must be a preexisting agreement as to how the information will be structured and how each side will send and receive it.

Q4. Outline the role of the memory data register in the machine execution cycle. 

Q5. A code for representing colours is used, where each colour is stored using 7 bits. State the number of different colours that can be represented.

