# Beginning-of-python
a python learning notebook--code

根据半径r计算圆面积
r=25
area = 3.1415*R*R
print(area)
print("{:.2f}".format(area))

绘制五角星
交互式
from turtle import*
color（'red','red')
begin_fill()
for i in range(5):
  fd(200)
  rt(144)
end_fill()
