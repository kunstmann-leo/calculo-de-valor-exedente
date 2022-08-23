# calculo-de-valor-exedente
Calculando o valor a ser pago sobre o limite estabelecido

'''João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.
'''

peso=int(input("digite quantos KG de Peixe "))

kgTotal=int(peso - 50)

excesso=int(4)

if peso <= 50:

    print("João não pagará multa")
    
else:

    print("João pagará R$" , kgTotal * excesso , "pois pescou", kgTotal , "kg acima do limite do Estado de São Paulo" )
