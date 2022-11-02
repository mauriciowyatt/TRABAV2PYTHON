# TRABALHO AV2 PYTHON

#1) Faça função que calcule a área do trapézio, dados:
a) Base maior
b) Base menor
c) Altura
Lembrando que a área pode ser calculada por: A=(B + b) * h /2
O programa principal deve pedir os valores e usar a função para calcular a área.

basemaior = float(input('Digite a Base Maior: '))
basemenor = float(input('Digite a Base Menor: '))
altura = float(input('Digite a altura: '))
area = (basemaior + basemenor) / 2
print('A área do trapézio vale: ', area)



#2) Faça um programa em Python com uma função chamada soma_imposto. A função
possui dois parâmetros formais:
a) taxa_imposto, que é a quantia de imposto sobre vendas expressa em
porcentagem; e
b) custo, que é o custo de um item antes do imposto. A função "altera" o valor de
custo para incluir o imposto sobre vendas.
O programa principal deve pedir os dados e usar a função para calcular preço do produto.

def somaimposto(taxaimposto, Custo):
    return (1 + taxaimposto/100)*Custo
ti = float(input('Digite o valor da taxa de imposto: '))
ct = float(input('Digite o valor do custo: '))
print('O Valor tributado é:', somaimposto(ti,ct))


#3) Faça um programa que converta da notação de 24 horas para a notação de 12 horas.
Por exemplo, o programa deve converter 14:25 em 2:25 P.M.
a) A entrada é dada em dois inteiros.
b) Deve haver pelo menos duas funções: uma para a conversão e uma para a saída.
c) Registre a informação A.M./P.M. como um valor "A" para A.M. e "P" para P.M.
Assim, a função para efetuar as conversões terá um parâmetro formal para
registrar se é A.M. ou P.M.
d) Inclua um loop que permita que o usuário repita esse cálculo para novos valores
de entrada todas as vezes que desejar, digitando um valor negativo para a hora
quando quiser encerrar


def converta(h, m):
    if 0 < h <= 12 and 0 < m < 60:
        print(f'{h}:{m} AM')
    elif 12 < h < 24 and 0 < m < 60:
        print(f'{h - 12}:{m} PM')
    else:
        print('Valor inválido')


while True:
    h = int(input('Hora: '))
    if h == 999: break
    m = int(input('Minuto: '))
    converta(h,m)
    print('='*20)

