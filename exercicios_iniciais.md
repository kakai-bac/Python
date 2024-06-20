# primeiro print ola mundo
print("Olá, mundo!")

# input e print de nome
nome = input("Qual o seu nome?")
print("É um prazer te conhecer, " , nome,"!")
print(nome,", me diga qual é o seu nome completo, por favor.")
nome_completo = input("Nome completo:")
print(nome_completo)

# tipo da variavel, input e print usando a soma
n1 = int(input("Primeiro número:"))
n2 = int(input("Segundo valor:"))
soma = n1 + n2
print(f'A soma entre {n1} e {n2} vale {soma}')

# tipos e funções de uma variável
a = input('Digite algo:')
print("O tipo primitivo é:", type(a))
print(f'{a} tem espaços?', a.isspace())
print(f'{a} tem números?', a.isnumeric())
print(f"{a} tem letras?", a.isalpha())
print(f'{a} tem números e letras?', a.isalnum())
print(f'{a} está em maiúsculas?', a.isupper())
print(f'{a} está em minúsculas?', a.islower())
print(f'{a} está em maiúsculas e minúsculas?', a.istitle())
