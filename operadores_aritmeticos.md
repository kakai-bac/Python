# explorando a formatação
nome = input('Qual é o seu nome?')
print(f'Prazer em te conhecer, {nome:=^20}!')

# operadores aritméticos
a = int(input('Primeiro valor:'))
b = int(input('Segundo valor:'))
soma = a + b
sub = a - b
mult = a * b
div = a / b
pot = a ** b
divint = a // b
mod = a % b
print(f'a soma de {a} e {b} é {soma}')
print(f'a subtração de {a} e {b} é {sub}')
print(f'a multiplicaçao de {a} e {b} é {mult}')
print(f'a divisão de {a} e {b} é {div:.3}')
print(f'a potencia de {a} elevado a {b} é {pot}')
print(f'a divisão inteira de {a} por {b} é {divint}')
print(f'o modulo de {a} por {b} é {mod}')

# ler numero e mostrar antecessor, sucessor, dobro, triplo e raiz quadrada
a = int(input('Digite um número:'))
ant = a - 1
suc = a + 1
dob = a * 2
tri = a * 3
raizq = a**(1/2)
print('>>> 'f'o antecessor de {a} é {ant} \n>>>'f' o sucessor de {a} é {suc}')
print('>>> 'f'o dobro de {a} é {dob} \n>>> 'f'o triplo de {a} é {tri} \n>>>'f' a raiz quadrada de {a} é {raizq:.3}')

# ler primeira e segunda nota e calcular media
n1 = float(input('Digite a primeira nota:'))
n2 = float(input('Digite a segunda nota:'))
media = (n1 + n2) / 2
print(f'Primeira nota: {n1} > Segunda nota: {n2}', end=' >>> ')
print(f'Média: {media:.2}')

# conversor de medidas
m = float(input('Digite um valor(em metros):'))
cm = m * 100
mm = m * 1000
print(f'em metros(m): {m} >>> em centímetros(cm): {int(cm)} >>> em milímetros(mm): {int(mm)}')

# tabuada
n = int(input('Digite um valor:'))
print(f'TABUADA DE {n}')
print(f'{n} x',1,f'= {n*1}')
print(f'{n} x',2,f'= {n*2}')
print(f'{n} x',3,f'= {n*3}')
print(f'{n} x',4,f'= {n*4}')
print(f'{n} x',5,f'= {n*5}')
print(f'{n} x',6,f'= {n*6}')
print(f'{n} x',7,f'= {n*7}')
print(f'{n} x',8,f'= {n*8}')
print(f'{n} x',9,f'= {n*9}')
print(f'{n} x',10,f'= {n*10}')

# conversor de moeda
real = float(input('Quantos reais você tem na carteira?'))
dolar = real / 3.27
print(f'Com R${real:.2f} você poderá comprar US${dolar:.2f}')

# auxiliar de pintura
larg = float(input('Informe a largula da parede (em metros):'))
alt = float(input('Informe a altura da parede (em metros):'))
area = larg * alt
tinta = area / 2
print(f'A área dessa parede é: {area} m2')
print(f'Serão necessários {tinta} baldes de tinta para pintá-lá')

# valor antigo e valor novo com 5% de desconto
valorantigo = float(input('Informe o valor do produto:'))
novovalor = valorantigo - ((5/100) * valorantigo)
print(f'Valor antigo: R$ {valorantigo:.2f}')
print(f'Valor novo: R$ {novovalor:.2f}')

# ler salario e mostrar novo salário com 15% de aumento
sal = float(input('Informe o salário do funcionário:'))
novosal = (sal * (15/100)) + sal
print(f'Novo salário do funcionário: R$ {novosal:.2f}')

# conversor de temperatura(ºC, ºF, K)
c = float(input('Qual a temperatura em Celsius(ºC)?'))
f = (c * 1.8) + 32
k = c + 273
print(f'Transformando...\nA temperatura em Celsius: {c}ºC\nDe Celsius para Fahrenheit: {f}ºF\nDe Celsius para Kelvin: {k}K')

# custo de aluguel de carro por dias e km rodados
dias = int(input('Por quantos dias o carro foi alugado?'))
km = float(input('Quantos quilômetros(km) foram rodados no carro?'))
total = (dias * 60) + (0.15 * km)
print(f'O total a pgar é de R${total:.2f}')
