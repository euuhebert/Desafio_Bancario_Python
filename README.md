### Projeto Banco Virtual

Este projeto consiste em um aplicativo de terminal em Python para gerenciar transações bancárias básicas, como depósitos, saques, visualização de extrato e controle de limite de saques diários. Abaixo estão detalhadas as funcionalidades, a estrutura do projeto e instruções para execução.

#### Funcionalidades:

1. **Depósito de Fundos:**
   - Permite ao usuário depositar um valor na conta bancária.

2. **Saque de Fundos:**
   - Permite ao usuário sacar um valor da conta, respeitando o saldo disponível, o limite de saque e o número máximo de saques diários.

3. **Visualização de Extrato:**
   - Mostra ao usuário o histórico de transações realizadas e o saldo atual da conta.

4. **Encerramento do Programa:**
   - Opção para sair do programa.

#### Estrutura do Projeto:

O projeto é implementado em Python e possui a seguinte estrutura de classes:

- **Classe `ContaBancaria`:**
  - Gerencia o saldo, o extrato, o limite de saques e as operações relacionadas à conta bancária.

- **Função `main()`:**
  - Função principal que controla o fluxo de interações do usuário através de um menu interativo.

#### Instruções de Execução:

Para executar o projeto, siga os passos abaixo:

1. **Pré-requisitos:**
   - Python instalado (versão 3.x recomendada).

2. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/banco-virtual.git
   cd banco-virtual
   ```

3. **Executar o Programa:**
   ```bash
   python main.py
   ```

4. **Interagir com o Programa:**
   - Após iniciar o programa, utilize as opções do menu para realizar operações de depósito, saque, visualização de extrato ou sair do programa.

#### Exemplo de Uso:

```plaintext
[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> d
Informe o valor do depósito: 100
Depósito: R$ 100.00

[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> s
Informe o valor do saque: 50
Saque: R$ 50.00

[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> e

================ EXTRATO ================
Depósito: R$ 100.00
Saque: R$ 50.00

Saldo: R$ 50.00
==========================================

[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> q
```

#### Considerações Finais:

Este projeto proporciona uma implementação básica de um sistema de banco virtual em Python, demonstrando o uso de classes, métodos, controle de fluxo e interações via terminal. Sinta-se à vontade para explorar, modificar e expandir conforme necessário para atender a requisitos específicos ou cenários adicionais.