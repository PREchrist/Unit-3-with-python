## Codin Game solutions

# Onboarding Puzzle
```.py
while 1:
    enemy_1 = input() 
    dist_1 = int(input()) 
    enemy_2 = input()  
    dist_2 = int(input())  

    # Enter the code 
    
    if dist_1 < dist_2:
        print(enemy_1)
    else:
        print(enemy_2)
 ```
        
        
  #The Descent
  
```.py
import sys
import math

# game loop

while True:
    mountain = []
    for i in range(8):
        mountain.append(int(input())) 

    #max(list)
    #list.index()
    
    max_value = max(mountain)
    
    index_of_max = mountain.index(max_value)
    
    print(str(index_of_max))
    ```
    
    
