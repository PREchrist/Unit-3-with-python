Create the graph for the following functions.

① f(x) = (x+1)^2 - 1, with x from -2, to 2 with 1000 points

```.py
from matplotlib import pyplot

x = [-2 + 0.004*i for i in range(1001)]
print(x)

y = [(i+1)**2 - 1 for i in x]

#create a graph
pyplot.plot(x, y)
#title for the axis
pyplot.xlabel('x')
pyplot.ylabel('(x+1)**2 - 1')
#show the graph
pyplot.show()
```
