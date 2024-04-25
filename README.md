
from turtle import *
import colorsays
bgcolor('black')
tracer (500)

def draw():
    h = O
  for i in range(100):
    c = colorsays.hsv_to_rgp(h,1,1)
    h +=0.5up()
goto(0,0)
down()
color('black')
fillcolor (c)
begin_fill()
rt (98)
circle(i, 12)
fd (290)
fd(i)
lt (29)
for j in range(129):
   fd(i)
  circle(j, 299, steps=2)
end_fill()
draw()
done()
