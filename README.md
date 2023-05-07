Projeto da disciplina de algoritmo do curso de Analise e Desenvolvimento de Sistemas no IFBA

Faça um sistema bancário utilizando vetores e matrizes na linguagem C, com as seguintes funções:

MENU INICIAL

1- CRIAR CONTA:
Esta função permitirá ao usuario criar uma conta no banco.

2- ACESSAR CONTA:
Para realizar qualquer operaçao no sistema o cliente deverá realizar o login informando seu nome numero da conta e sua senha. Essa função deverá autenticar o login do usuário e mostrar o menu intermediário.

3- SAIR

MENU INTERMEDIÁRIO

1- DEPOSITO:
Esta função receberá como parâmetro o vetor de saldo (por referencia) e o número da conta do cliente logada no sistema. A função irá solicitar do usuario o valor para o deposito. Ao final a funçäo deverá incluir o valor depositado na conta correspondente e informar ao usuário que o valor foi depositado com sucesso.

2- SAQUE:
Esta função receberá como parâmetro o vetor de saldo (por referencia), o numero da conta (por valor) do cliente logado no sistema. A função irá solicitar do usuário o valor para o saque. A função deverá avaliar se o saldo é maior que o valor do saque, caso nao seja, informar ao cliente: valor indisponível para saque. Caso o valor esteja disponível, a função deverá subtrair o valor do saque na conta correspondente e informar ao usuário: valor foi sacado com sucesso e o seu novo saldo.

3- TRANSFERENCIA:
Esta funçäo receberá como parâmetro o vetor de saldo e a matriz de contas (ambos por referência), eo número da conta do cliente logado no sistema. A função irá solicitar do usuário o numero da conta de destino e o valor da transferência. A função deverá avaliar se o limite é suficiente para a transferência e se a conta existe (neste caso nao existirá nenhum nome cadastrado no indice correspondente na matriz de contas). Caso exista a conta de destino e o saldo da conta de origem seja suficiente, o sistema deverá realizar a transferência (subtraindo o valor da conta de origem e adicionando na conta de destino). Caso o cliente da conta de origem não possua limite suficiente, informar ao cliente: conta não possui saldo suficiente para a transferência. Ao final a função deverá informar ao cliente: a transferência foi realizada com sucesso, informando a conta (nome do cliente e numero) de origem, destino e o valor transferido.

4- CONSULTA DE SALDO:
Esta função receberá como parâmetro o vetor de saldo (por referencia) e o numero da conta do cliente
logado por valor). A função deverá retornar o saldo da conta informada para a função que a chamou.

5- RETORNAR PARA O MENU INICIAL
