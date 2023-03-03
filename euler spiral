import math
import matplotlib.pyplot as plt
x=0
y=0
angle=0
k=int(input("enter limit:"))
xcor=[]
ycor=[]
i=0
while(i<=k):
    angle=angle+(i*22/(7*180))
    x=x+math.cos(angle)
    y=y+math.sin(angle)
    xcor=xcor+[x]
    ycor=ycor+[y]
    i=i+1
plt.plot(xcor,ycor)
plt.show()
plt.plot(0,0)
plt.show()

#for turtle programme
import turtle
s=turtle.getscreen()
t=turtle.Turtle()
i=0
k=int(input("enter limit:"))
while(i<=k):
    t.right(i*(0.02))
    t.forward(1)
    i=i+1
