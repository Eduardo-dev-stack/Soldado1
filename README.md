from turtle import *
...
color("BLUE")
bgcolor('BLACK')
speed(10)
hideturtle()
...
b = 0
while b < 200:
    right (b)
    forward (b * 3)
    b += 1
done()
