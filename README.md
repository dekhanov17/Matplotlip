import matplotlib.pyplot as plt
import numpy as np


x = [0,0,0,0,0,0,0]
y = [0,5,10,15,20,25,30]

x1 = [0,2,4,5,4,2,0]
y1 = [30,30,27,25,23,20,20]
x2 = [0,2,4,5,4,2,0]
y2 = [15,15,12,10,7,5,5]

plt.scatter(x, y)
plt.scatter(x1, y1)
plt.scatter(x2, y2)

plt.axis('equal')
plt.grid()
plt.show()
