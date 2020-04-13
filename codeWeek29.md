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


## Preliminaries:

# What is a Hash: 
    Hash is a function that converts one value to another. In others words, hashing is a process of converting an input of any length into a fixe size string of text, using a mathematical function; this means any text, no matter how long it is can be converted into an array of letters and numbers through an algorythm. Hashing data is a common practice in computer science and is used for several different purposes. 

# What is a byte and a bit?
    A bit (short for "binary digit") is the smallest unit of measurement used to quantify computer data. It contains a single binary value of 0 or 1. Whereas byte contains eight bits that each have two possible values, a single byte may have 28 or 256 different values. 
       [The terms "bits" and "bytes" are often confused and are even used interchangeably since they sound similar and are both abbreviated with the letter "B." However, when written correctly, bits are abbreviated with a lowercase "b," while bytes are abbreviated with a capital "B." It is important not to confuse these two terms, since any measurement in bytes contains eight times as many bits. For example, a small text file that is 4 KB in size contains 4,000 bytes, or 32,000 bits, Generally, files, storage devices, and storage capacity are measured in bytes, while data transfer rates are measured in bits. For instance, an SSD may have a storage capacity of 240 GB, while a download may transfer at 10 Mbps. Additionally, bits are also used to describe processor architecture, such as a 32-bit or 64-bit processor.]
 
# What is ascii?
    ASCII, abbreviated from American Standard Code for Information Interchange, is a character encoding standard for electronic communication. ASCII codes represent text in computers, telecommunications equipment, and other devices

# What is Unicode and UTF-8?
    Unicode is an information technology standard for the consistent encoding, representation, and handling of text expressed in most of the world's writing systems.
    UTF-8 is a variable width character encoding capable of encoding all 1,112,064 valid code points in Unicode using one to four one-byte code units.

# What is hexadecimal?
    In mathematics and computing, hexadecimal is a positional system that represents numbers using a base of 16. Unlike the common way of representing numbers with ten symbols, it uses sixteen distinct symbols, most often the symbols "0"–"9" to represent values zero to nine, and "A"–"F" to represent values ten to fifteen.



## Great done ! 
