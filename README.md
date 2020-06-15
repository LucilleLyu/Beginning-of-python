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



1. 字符串：有0个或多个字符串组成的有序字符序列
由一对单引号或一对双引号表示（‘’ “”）
2. 返回单个字符 [3]-索引
  返回这段字符，除掉最后一个字符 [0:-1] 即从0到-1不包括-1 -切片
  
  
  分支语句 
  由判断条件决定程序运行方向
  if（条件为true则执行冒号后语句） / elif / else + ：
  
  函数
  类似数学函数
  print（） #打印输出
  input() #输入
  eval() #去掉参数最外侧引号并执行剩下语句-评估函数
  
  print()函数的格式化：
  print("转换后的温度是{:.2f}C".fromat(c))
  {}表示槽，后续变量填充到槽中
  {:.2f}表示将变量C填充到这里是取小数点后2位
  
  
