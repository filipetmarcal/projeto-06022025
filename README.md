# Sistema de Controle e Gerenciamento de Ordens de Serviço

Este projeto tem como objetivo modelar um sistema de controle para uma oficina mecânica, no qual clientes levam seus veículos para conserto ou revisão periódica. O sistema gerencia a execução das ordens de serviço, incluindo a alocação de mecânicos, serviços a serem realizados, peças utilizadas e cálculo dos valores de cada serviço.

## Entidades do Sistema

- **Cliente**: Contém informações sobre o cliente que leva o veículo para reparo.
- **Veículo**: Informações sobre os veículos que são consertados na oficina.
- **Mecânico**: Dados dos mecânicos responsáveis pela execução dos serviços.
- **Equipe**: Cada equipe é composta por um grupo de mecânicos responsáveis pela execução das ordens de serviço.
- **Ordem de Serviço (OS)**: Documento que descreve os serviços a serem executados em um veículo, incluindo valor e status.
- **Serviço**: Descrição dos serviços disponíveis na oficina.
- **Peça**: Componentes utilizados nos serviços de reparo.

## Relacionamentos

- Cada **Cliente** pode ter muitos **Veículos**.
- Cada **Veículo** pode ter muitas **Ordens de Serviço (OS)**.
- Cada **OS** é realizada por uma **Equipe** e inclui **Serviços** e **Peças**.
- **Serviços** e **Peças** são associados a uma **OS** através de tabelas intermediárias.

## Como Executar

1. Clone este repositório.
2. Utilize um banco de dados relacional para criar as tabelas baseadas no esquema conceitual.
3. Implemente os fluxos do sistema utilizando a linguagem e tecnologias de sua escolha.

## Desafios e Aprendizados

- O desafio foi estruturar um sistema complexo de controle de ordens de serviço, identificando as entidades necessárias e os relacionamentos entre elas.
