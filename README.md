# Curso Alura :: Blockchain para Negócios: aplicações reais

## Algorítmos de concenso

> Opinião: Visa garantir que o ativo criado seja único e que somente quem tenha sua propriedade/posse pode transferi-lo a um novo proprietário/possuidor

### Prova de Tabalho (PoW)

- Utilizado pela rede BitCoin
- Chamado de mineração, por que remunera os nós de consenso
- Remunera seus participantes(mineradores)
- Consome muita energia : é a grande desvantagem

### Prova de Investimento(PoS)

- Utilizado pela rede Ethereum
- Remunera seus participantes(mineradores)
- Quem investe($$$) mais na rede tem mais chances de ser escolhido *"aleatóriamente"* :thinking:
- Menor consumo de energia

### Prova de Tempo Decorrido(PoET)

- Criado pela Intel
- Implementação em Sawtooth
- Hibrido entre PoW e PoS
- A rede distribui entre os participantes os ativos que precisam ser validados

### Byzantine Fault Tolerance (SBFT)

- Melhorias sobre o PoW
- Podemos selecionar quais nós irão validar os ativos
- Só um validador

### Prova de Autoridade (PoA)

- Autoridades são os nós de validação

## Pilares do Blockchain

- Ledger Distribuído : Garante transparência e imutabilidade a informação
- Criptografia : mantém a privacidade e a segurança tradicional
- Smart Contract : Regras de negócio do ativo
- Consenso : Estabilidade e validação distribuída

## Tipos de Blockchain(Plataformas)

### Públicos

- Qualquer pessoa pode consultar o Ledger(Livro Caixa)
- Exemplos: Bitcoin, Ethereum, RSK, IOTA
- 

### Privados (Blockchain Permissionado)

- Somente quem participa da rede pode consultar o Ledger(Livro Caixa)
- Exemplos: CORDA, Quorum, Hyperledger
- Membership Services
  - Registration
  - Attributes
  - Reputation 

## Contratos (Smart Contracts)

Implementam em uma linguagem de programação as regras de negócio de validação do ativo

## Implementações 

Os diferentes modelos de implementação de blockchain, são:

- IoT: desenvolver uma rede de blockchain para gerenciar/controlar os sensores.
- Supply: faz a gestão da cadeia logística, desde a fabricação, até a entrega.
- BPM: gestão e controle de processos, permite ter uma visão mais integrada de um processo.
- Tokens: faz com que a execução da troca de ativos seja seguro e privado.

## Casos de uso

O objetivo dos cases passados em aula foi de entender a implementação e a diversidade de soluções e problemas de negócio de Blockchain:

- Blockchain para varejo: a receita pode ser diretamente afetada, os preços podem ser afetados.
- Blockchain para produtos de luxo: uma rede vulnerável a fraudes, tem uma rede regulatória que aumenta a complexidade na manufatura.
- Blockchain para a Logística: um alto custo administrativo e burocrático, falta de automação.
- Blockchain para Agro: a visão de áreas produtivas é limitada.
- Blockchain para Finanças: transferências internacionais precisam de intermediários, aumentando o custo de transação.
- Blockchain para Mobilidade Urbana: aumento de fraudes e roubos.

## Inicio do Projeto

### 1. Como gerar um negócio de valor:
Entender o contexto e informações, utilizando perguntas e pesquisa exploratória:

Foco em produto ou solução? Qual a real necessidade deste negócio? Quais são os principais problemas que motivam essa demanda? O que está sendo feito/validado para resolver essa necessidade? Qual o impacto financeiro do contexto do problema?

### 2. Desenhar um produto viável mínimo (MVP)
Determinar o objetivo da proposta, utilizando perguntas:

- Qual é o fluxo concreto de ações necessárias que deve acontecer?
- Qual o impacto financeiro em termos de tempo, risco e custo?
- Qual é o fator de sucesso?
- Qual o resultado que o cliente espera?

### 3. Design da rede (in chain)
Determinar a quantidade de participantes para cada tarefa:

- Transações de pagamento
- Ativos que serão negociados
- Entender a complexidade dessas transações e a segurança dos dados do blockchain.
### 4. Design da rede (off chain)
Determinar a interação do usuário, utilizando perguntas:

- Utilizar Front-end, portais, apps e APIs?
- É preciso levantar relatórios?
- 
### 5. Modelo operacional/infraestrutura
Nó

- São máquinas físicas que armazenam e processam os dados e transações.
Peer

- Armazena e executa os dados/transações.
- Valida as assinaturas digitais, fazendo com que elas sejam reconhecidas na rede.

### 6. Utilizamos a estratégia MPV (MVP em inglês) para implementação:

- Mínimo produto viável: lançar um produto com as mínimas características necessárias para validar uma ideia.
- O sprint vai definir as entregas dos produtos.