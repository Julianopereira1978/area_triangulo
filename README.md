# Area_Triangulo
Basic program made in Python to calculate the triangle area.

# Created by Juliano Pereira on 13/08/2022
#calculadora area do triangulo

import os

print("Informe os dados do triangulo: ")

base = float(input('Base: '))

altura = float(input('Altura: '))

area = base * altura / 2

print ('A área do triângulo é' , area)
     

os.system('pause')
