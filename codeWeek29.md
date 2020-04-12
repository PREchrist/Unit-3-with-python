Happy Easter
The Christ is risen, hope everything gonna change in the time.


Sunday, April 12th 2020

Coding Practice

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
