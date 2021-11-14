# Quadratic-Equation
My first Repository
import math
def quadratic(a,b,c):
    if a==0:
        return print('二次项系数不能为零，请重新填写')
       
    if b*b-4*a*c<0:
        return print('系数填写错误,请重新填写')
    else:
        x1=(-b+math.sqrt(b*b-4*a*c))/(2*a)
        x2=(-b-math.sqrt(b*b-4*a*c))/(2*a)
        return(x1,x2)
