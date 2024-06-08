# Sistema Bancário

1 - Menu de opções:
- O menu é exibido repetidamente em um loop while True.

- As opções disponíveis são:
    - d : ****Depositar****
    - s : ****Sacar****
    - e : ****Extrato****
    - q : ****Sair****

2 - Variáveis iniciais:

 - ****saldo****: Inicializado com zero (representa o saldo da conta).

 - ****limite****: Inicializado com 1000 (representa o limite de saque).

 - ****extrato****: Inicializado como uma string vazia (será usado para registrar as transações).

 - ****numero_saques****: Inicializado com zero     (conta o número de saques realizados).

 - ****LIMITE_SAQUES****: Constante definida como 3 (número máximo de saques permitidos).

3 - Funcionalidades:

Depósito (d):
 - Solicita ao usuário o valor do depósito.
Se o valor for maior que zero, atualiza o saldo e registra a transação no extrato.
Caso contrário, exibe uma mensagem de erro.

Saque (s):
 - Solicita ao usuário o valor do saque.

    - Verifica se o valor excede o saldo, o  
    - limite ou o número máximo de saques.
    - Se todas as condições forem atendidas, atualiza o saldo, registra a transação e incrementa o contador de saques.
    
    - Caso contrário, exibe mensagens de erro específicas.

Extrato (e):
- Exibe o extrato das transações realizadas (ou uma mensagem informando que não houve movimentações).
- Mostra o saldo atual.

Sair (q):
 - Encerra o loop e finaliza o programa.
