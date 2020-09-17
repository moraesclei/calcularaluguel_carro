# calcularaluguel_carro
código_para_calcularaluguel_carro
##Código para calcular aluguel de carros##
km = float(input('Quantos Km percorridos?'))
dias = int(input('Quantos dias alugados?'))
pago = (dias * 60) + (km * 0.15)
print('O valor a pagar é R${:.2f}'.format(pago))

