import math
#Escrever entradas para os valores de a, b e c

a = int(input("Escreva o valor de a:"))
b = int(input("Escreva o valor de b:"))
c = int(input("Escreva o valor de c:"))

#Fazer as operações com os valores armazenados

delta = (b**2 * 4 * a * c)
if delta >= 0:
  print(delta)
else:
  print("Não existe delta negativo")
  
#Exibir os dois valores da equação

x1 = (- b + (math.sqrt(delta)))
divisao = (a*2)
xl = (x1 / divisao)
print(xl)
x2 = (- b - (math.sqrt(delta)))
xll = (x2 / divisao)
print(xll)
