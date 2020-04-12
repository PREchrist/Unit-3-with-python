## Happy Easter
## The Christ is risen, hope everything gonna change in the time.


## Sunday, April 12th 2020

# Coding Practice

## Question 1:

## Write a Python program that asks the user for his first name and last name and a number (1, 100]. The output is a text file with as email addresses for the user:

Sample Input
John, Coe, 3
Expected Output

output.txt
john.coe1@uwcisak.jp
john.coe2@uwcisak.jp
john.coe3@uwcisak.jp

# Solution to this question:

```.py
#this program asks the user his coordinates

# get the user input
check = 0

#
doc= open("week29.txt","w+")

first_name = input('What is your first name ?\n')
last_name = input('What is your last name ?\n')
number = int(input('enter your number between 1-100:\n'))


while check == 0:

    if 0 < number <= 100:
        for x in range(1, number+1):
            s='\n'+'{0}.{1}.{2}@uwcisak.jp'.format(first_name, last_name, x)
            doc.write(s)
            print(s)
        break
    else:
        number = int(input('The imput number was not in the range, please enter a number between 1-100:\n'))
```

## Question 2:

## Write a Python program that generates random passwords of length 20. The user provides how many passwords should be generated

Sample Input:
3

Expected Output
Password 1: 4)uLyPr-8`w2)H5z2;4}
Password 2: <FZ}Z?~Lj<k4#5m]WBAq
Password 3: {s=AS2=xJ;#5*F~s(EQ#

```.py
import random

chars = 'abcdefghijklmnopqrstuvwxyz1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@&%#*+¥<>-='

number = int(input('How many password do you want:\n'))
#number = int(number)

#length = input('Which length is better for your password')
length = int(20)

for p in range(number):
    password = ''
    for c in range(length):
        password += random.choice(chars)
    print(password)
```

## Syllabus Questions:

## You have been given 5000 USD to build your dream computer. The only condition is that you cannot buy a prebuilt computer. Describe what parts you would buy, and Explain how they work as a system to create a computer.

- CPU : 
- RAM :
- Power supply :
- Hard Drive :
- Graphics card :
- System fan : 
- MotherBroad : 



## Great done ! 
