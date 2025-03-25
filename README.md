# Sistema de Controle de Ordens de Serviço para Oficina Mecânica

Este repositório contém um projeto de estudo focado na criação de um esquema conceitual para o gerenciamento de ordens de serviço em uma oficina mecânica. O objetivo principal é aplicar conceitos de modelagem de dados e estruturas relacionais para organizar o fluxo de trabalho de uma oficina, incluindo o controle de clientes, veículos, mecânicos, serviços e peças.

## Descrição do Projeto

O sistema proposto visa organizar e otimizar o processo de execução de serviços em uma oficina mecânica. Ele contempla a criação de ordens de serviço (OS), associadas a clientes e veículos, e a atribuição dos serviços a equipes de mecânicos. O modelo também inclui o cálculo do valor de serviços e peças, proporcionando uma visão integrada do processo de atendimento.

### Entidades Principais:

- **Clientes**: Pessoas ou empresas que solicitam os serviços da oficina.
- **Veículos**: Automóveis ou outros tipos de veículos que necessitam de manutenção ou reparos.
- **Mecânicos**: Profissionais responsáveis pela execução dos serviços. Cada mecânico possui especialidade e informações de contato.
- **Ordens de Serviço (OS)**: Documentos que registram os serviços a serem realizados em um veículo, com dados como número da OS, data de emissão, status e data de conclusão.
- **Serviços e Peças**: Cada ordem de serviço pode envolver a utilização de peças e a execução de serviços com custos específicos, que são calculados a partir de tabelas de referência.

## Objetivo do Projeto

Este projeto tem como objetivo praticar e aplicar técnicas de modelagem de dados relacionais, fornecendo uma estrutura clara para o gerenciamento das atividades de uma oficina mecânica. Ele serve como uma base para futuros aprimoramentos e implementações de sistemas mais complexos.

## Como Usar

1. Clone o repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/Fabianogf12/OFICINATECH.git
