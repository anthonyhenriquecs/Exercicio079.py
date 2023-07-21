# Exercicio079.py

numeros = list()
while True:
    n = int(input('Digte um valor:'))
    if n not in numeros:
        numeros.append(n)
        print('Valor adc com sucesso!')
    else:
        print('Valor duplicado, não adicionarei')
    r = str(input('Quer continuar?'))
    if r in 'Nn':
        break
print('-+'*30)
numeros.sort()
print(f'Voce digitou os valores{numeros}')
