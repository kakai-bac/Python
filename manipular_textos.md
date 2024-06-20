# fatiamento simples
frase = 'Curso em Video Python'
print(frase[9])

# fatiamento com indice final e inicial
frase = 'Curso em Video Python'
print(frase[9:13])

# fatiamento com inicio e final com salto
frase = 'Curso em Video Python'
print(frase[9:21:2])

# fatiamento somento com indice final
frase = 'Curso em Video Python'
print(frase[:9])

# fatiamento somento com indice inicial
frase = 'Curso em Video Python'
print(frase[15:])

# fatiamento com indice inicial, sem indice fibnal e com salto
frase = 'Curso em Video Python'
print(frase[9::3])

# analise de string com len
frase = 'Curso em Video Python'
print(len(frase))

# analise de string com count
frase = 'Curso em Video Python'
print(frase.count('o'))

# analise de string com count e fatiamento
frase = 'Curso em Video Python'
print(frase.count('o',0,14))

# analise de string com find
frase = 'Curso em Video Python'
print(frase.find('em'))

# analise de string com in
frase = 'Curso em Video Python'
print('Video' in frase)

# transformaçao de str com replace
frase = 'Curso em Video Python'
novafrase = frase.replace('Python','Java')
print(novafrase)

# transformaçao de str com upper
frase = 'Curso em Video Python'
maiusc = frase.upper()
print(maiusc)

# transformaçao de str com lower
frase = 'Curso em Video Python'
minusc = frase.lower()
print(minusc)

# transformaaçao de str com capitalize
frase = ('Curso em Video Python')
cap = frase.capitalize()
print(cap)

# transformaçao de str com title
frase = 'Curso em Video Python'
tit = frase.title()
print(tit)

# transformaçao de str com strip
frase = '    Curso em Video Python     '
strip = frase.strip()
print('Antes:', frase)
print('Depois:', strip)

# transformaçao de str com rstrip
frase = '    Curso em Video Python     '
rstrip = frase.rstrip()
print('Antes:', frase)
print('Depois:', rstrip)

# transformaçao de str com lstrip
frase = '    Curso em Video Python     '
lstrip = frase.lstrip()
print('Antes:', frase)
print('Depois:', lstrip)

# divisao de str com split
frase = 'Curso em Video Python'
splitar = frase.split()
print(splitar)

# junçao de str com join (juntar uma str que esta splitada)
frase = 'Curso em Video Python'
splitar = frase.split()
juntar = ' '.join(splitar)
print('Antes:', splitar)
print('Depois:', juntar)
