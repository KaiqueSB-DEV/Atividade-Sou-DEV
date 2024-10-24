# Atividade-Sou-DEV
A seguir, mostrarei o desenvolvimento do programa passo a passo

O trabalho em questão tem como principal objetivo desenvolver um programa que simule o cálculo de uma fatura de cartão de crédito.

total_fatura = 0: Inicializa o valor total da fatura com zero. A cada compra inserida será atualizado.

ultima_compra = False: Variável usada para controlar o loop.

O while not ultima_compra cria um loop onde o programa pede que o usuário insira o valor de uma compra e esse valor é somado ao total_fatura

Após cada inserção, o programa pergunta se aquela foi a última compra. Se o usuário responder ‘S’ (sim), a variável  ultima_compra é definida como True e o loop é encerrado.

Logo após no bloco seguinte, o programa pergunta ao usuário o dia de pagamento

O código verifica se o pagamento foi feito até dia 25

    Se o pagamento foi feito até o dia 25, o programa informa o valor total da fatura sem juros
    
    Caso contrário, aplica-se um juro de 3% ao valor da fatura para cada dia de atras 
    
O cálculo do valor adicional de juros é feito usando a fórmula:

juros_adicional  = (total_fatura * 0.01) *  dias_extras

E finalmente o programa exibe o valor  final da fatura, seja com ou sem juros.

Vimos que este programa oferece uma solução simples e eficiente para o cálculo de fatura de cartão de crédito com base nas compras realizadas e no dia do pagamento.

