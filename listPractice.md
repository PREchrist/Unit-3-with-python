EVEN INDICES

```
a = input().split()
for i in range(0, len(a), 2):    
    print(a[i])
```
    
 EVEN ELEMENTS
 
 ```
 a = [int(i) for i in input().split()]
for elem in a:
    if elem % 2 == 0:
        print(elem)
```
        
 GREATER THAN PREVIOUS
 
 ```
 a = [int(i) for i in input().split()]
for i in range(1, len(a)):
    if a[i] > a[i - 1]:
        print(a[i])
 ```
        
  NEIGHBORS OF THE SAME SIGN
  
  ```
  a = [int(i) for i in input().split()]
for i in range(1, len(a)):
    if a[i - 1] * a[i] > 0:
        print(a[i - 1], a[i])
        break
  ```
        
   GREATER THAN NEIGHBOURS
   
   ```
   a = [int(i) for i in input().split()]
counter = 0
for i in range(1, len(a) - 1):
    if a[i - 1] < a[i] > a[i + 1]:
        counter += 1
print(counter)
```
