1. import random
a = random.randrange(1,10)
b = random.randrange(1,10)
print("a = ", a)
print("b = ", b)
a2 = a**2
b2 = b**2
print("Квадрат a = ", a2)
print("Квадрат b = ", b2)
print("Сумма квадратов: ", a2+b2)
print("Разность квадратов: ", abs(a2-b2))
print("Произведение квадратов: ", a2*b2)
print("Частное квадратов: ", a2/b2)
2.import random
N = random.randrange(100,1000)
print("Число: ", N)
d1 = int((N-d2*100)/10)
d0 = N%10
print("Единицы: ", d0)
print("Десятки: ", d1)
3.import random
A = random.randrange(1,10)
B = random.randrange(1,10)
print("A = ", A)
print("B = ", B)
a1 = (A%2)==1
b1 = (B%2)==1
x = (a1 != b1)
print("A нечетно: ", a1)
print("B нечетно: ", b1)
print("Ровно одно из чисел A и B нечетное: ", x)
4.import random
A = random.randrange(-3,3)
B = random.randrange(-3,3)
print("Число A:", A)
print("Число B:", B)
if A != B:
    A = B = A+B
else:
    A = B = 0
print("Число A:", A)
print("Число B:", B)
