# EngSoft1

## 1.1 Resumo do Projeto (Descrição textual)

* O projeto consiste no desenvolvimento de um sistema de compra e venda de AUTOS. o sistema consiste em duas partes a compra totalmente online atraves da escolha do AUTO e pagamento e transções online ou presencialmente em uma revenda.

## 1.2 Plataforma de Desenvolvimento
* As tecnologias para o desenvolvimento do sistema podem incluir:

* Linguagens de programação: Dependendo da escolha de tecnologia, como Java, Python, ou outra.
Banco de dados: MySQL, PostgreSQL ou outro sistema de gerenciamento de banco de dados.
Frameworks: Pode ser usado um framework de desenvolvimento web, como Django ou Spring Boot.
Ambiente de desenvolvimento: Um ambiente de desenvolvimento integrado (IDE) compatível com as linguagens de programação escolhidas.
## 1.3 Plataforma de Operação
* Os clientes podem utilizar o sistema em diferentes plataformas:

* Presencial: Para a compra do AUTO no balcão de atendimento da empresa.

* Online: Através de um aplicativo para dispositivos móveis ou uma interface web para a compra de passes.

## 1.5.1 Modos de Operação
* O sistema oferece dois modos de operação principais:

* Presencial: Os clientes compram da empresa com o auxílio de um atendente.

*Online: Os clientes usam um aplicativo para dispositivos móveis ou uma interface web para compras e negociações de forma digital.

## 1.6 Funções do Produto
* Principais funções do sistema:

## Presencial
* R1.1 - Verificar a disponibilidade de carros a seu gosto
* R1.2 - Efetuar pagamento: O cliente paga pelo passe em dinheiro ou cartão ou transferencia/financiamento bancario ao atendente 
## Online
* R2.1 - Abrir o aplicativo: O cliente acessa o aplicativo usando suas credenciais.
* R2.2 - Logar com seus dados: O cliente faz login com seus dados pessoais.
 * R2.3 - procurar o carro deseja e verificar disponibilidade
 * R2.4 - Informar o meio de pagamento e proposta de valor
* R2.5 - Efetuar pagamento: O cliente paga digitalmente por meio de PIX, cartão tranferencia/financimento bancario

## 1.7 Características dos Usuários
* Os principais grupos de usuários esperados para o sistema incluem:

* Atendente: Responsável por auxiliar os clientes na compra de AUTOS presencialmente.

* Cliente: Pessoas que desejam adquirir o AUTO 

* Nível de Instrução: Variado, dependendo do cliente ou atendente.

* Proficiência em Informática: Varia de acordo com o usuário, mas é esperado um nível básico a avançado de proficiência para o uso do sistema, dependendo da ação (presencial ou digital).

## 2.2.1Diagramas de casos de uso (Modelo UML de Casos de Uso)

![Diagrama](https://github.com/Putzz2/EngSoft1/assets/126510497/d9cd41e9-3c62-4a6c-a298-83945fda14bf)

**Descrição dos Casos de Uso:**

1. **Seleção de Autos:**
   - Ator: Cliente
   - Fluxo Principal:
      - O cliente pesquisa veículos por marca, modelo, ano, etc.
      - O cliente visualiza detalhes e imagens dos veículos.
   - Fluxo Alternativo: 
      - Nenhum veículo encontrado.

2. **Processo de Compra:**
   - Ator: Cliente
   - Fluxo Principal:
      - O cliente escolhe a opção de compra online.
      - Seleção de opções de financiamento.
      - Integração de métodos de pagamento online.
   - Fluxo Alternativo: 
      - Transação não concluída.

3. **Entrega ou Retirada:**
   - Ator: Cliente
   - Fluxo Principal:
      - O cliente escolhe entre entrega ou retirada.
      - Opções de agendamento são disponibilizadas.
   - Fluxo Alternativo: 
      - Nenhuma opção de agendamento disponível.

4. **Agendamento de Visita:**
   - Ator: Cliente
   - Fluxo Principal:
      - Cliente agenda visita presencial à revenda.
      - Possibilidade de test drive e inspeção física.
   - Fluxo Alternativo: 
      - Visita não confirmada.

5. **Atendimento na Revenda:**
   - Ator: Equipe de Vendas
   - Fluxo Principal:
      - Equipe auxilia o cliente na escolha e compra.
      - Oferta de opções de financiamento e pagamento.
   - Fluxo Alternativo: 
      - Cliente não satisfeito com atendimento.

6. **Documentação e Transação:**
   - Ator: Equipe de Vendas
   - Fluxo Principal:
      - Coleta de documentos necessários para a transação.
      - Processo de pagamento e formalização da compra.
   - Fluxo Alternativo: 
      - Documentação incompleta.

**Observações:**
- As linhas contínuas representam o fluxo principal.
- As linhas tracejadas representam fluxos alternativos ou excepcionais.
- Os atores estão destacados no topo.
- Cada caso de uso está numerado e tem uma breve descrição associada.

## 2.2.2Fluxos dos casos de uso (Casos de Uso Expandidos e Diagramas de Atividades)

![123](https://github.com/Putzz2/EngSoft1/assets/126510497/6d979001-3462-4675-afc2-ef9545ab37b5)


* Cliente chega à loja e solicita um veículo dentro de uma faixa de preço específica. O atendente apresenta todas as opções disponíveis na faixa de preço desejada e aguarda a escolha do cliente. O atendente então elabora um contrato de venda do carro, entrega-o ao cliente e, após a assinatura do contrato por parte do cliente, conclui a transação com o pagamento do valor do automóvel e a transferência dos documentos.

Ator:

Cliente Atendente

Ações:

liente chega à loja e solicita um veículo dentro de uma faixa de preço específica. O atendente apresenta todas as opções disponíveis na faixa de preço desejada e aguarda a escolha do cliente. 

O atendente então elabora um contrato de venda do carro, entrega-o ao cliente e, após a assinatura do contrato por parte do cliente, conclui a transação com o pagamento do valor do automóvel e a transferência dos documentos.


@startuml
start
:Cliente chega à loja;
:Cliente solicita veículo;
:Atendente pergunta sobre preferências de preço;
:Atendente apresenta opções disponíveis;
:Cliente escolhe um veículo;
:Atendente elabora contrato de venda;
:Atendente entrega contrato ao cliente;
:Cliente examina e assina o contrato;
  :Atendente conclui a transação;
  :Cliente paga o valor do veículo;
  :Atendente inicia transferência de documentos;
  stop


@enduml


