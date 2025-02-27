# O-Troco
# Pedir ao usuario o valor total da compra
# pedir ao usuario o valor pago pelo cliente
# calcular e exibir o troco que deve ser dado ao cliente
# Caso o valor seja insuficinte, exibir uma mensegem, valor insuficiente
# Caso contrario, exibir o valor esta correto
# caso o valor seja maior exibir o valor do troco


# Entrda de dados

valor_total = float(input("Digite o valor total da compra:"))
valor_pago = float(input("Digite o valor pago pelo cliente:"))
#processamento de dados
troco = valor_pago - valor_total
#saida de dados 
if valor_pago < valor_total:
     print("valor é insuficiente")
else:
     if valor_pago == valor_total:
          print("valor está correto")
     elif valor_pago > valor_total:
          print("O Troco é de R$ {:.2f}".format(troco))


