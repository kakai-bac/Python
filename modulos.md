# nesse caso, math esta sendo colocado em frente da raiz porque é um import math, o math., é para especificar a raiz
import math
n = int(input('Digite um número:'))
raiz = math.sqrt(n)
print(f'A raiz quadrda de {n} é {math.ceil(raiz)}')

# já aqui, não precisa do math. porque foi importado a função especifica
from math import sqrt, floor
n = int(input('Digite um número:'))
raiz = sqrt(n)
print(f'A raiz quadrda de {n} é {floor(raiz)}')

# usando o modulo random
import random
num = random.randint(1,100)
print(num)

# uso do módulo externo emoji
import emoji
print('Olá, mundo!' + emoji.emojize(':globe_with_meridians:'))
