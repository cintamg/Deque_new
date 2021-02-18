# Deque_new
To implement dequeue
from collections import deque
d=deque()
for i in range(int(input())): 
  y,*z=input().split()
  getattr(d,y)(*z)
print(*d)
