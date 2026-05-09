# Controle de Estoque e Vendas com Airtable

Case de modelagem de dados, automações no-code e estruturação de processos utilizando Airtable.


## Objetivo do Case

O objetivo do projeto: criar uma solução simples e escalável para controle de estoque, vendas e distribuição de produtos para pequenos negócios.

O sistema foi pensado para resolver problemas como:

- falta de controle sobre estoque;
- dificuldade em localizar produtos;
- duplicidade de produtos cadastrados manualmente;
- controle operacional feito apenas em planilhas;
- ausência de rastreabilidade de vendas e vendedores.


## Ferramenta Utilizada

- Airtable


## Principais Funcionalidades

- Cadastro de catálogo de produtos;
- Controle de unidades físicas individuais;
- Controle de estoque disponível;
- Registro de vendas;
- Controle de produtos enviados para vendedores;
- Controle de caixas de distribuição;
- Cálculo automático de quantidade disponível;
- Cálculo automático de valor total por caixa;
- Interfaces administrativas;
- Automações de atualização de status;
- Estrutura relacional entre tabelas.


## Estrutura do Projeto

```plaintext
controle-estoque-vendas-airtable/
│
├── README.md
│
├── assets/
│   ├── data.jpg
│   ├── automations.jpg
│   ├── interface.jpg
│   └── projects.jpg
│
└── docs/
    ├── modelagem.md
    ├── automacoes.md
    └── aprendizados.md
```

## Estrutura de Dados

O projeto foi estruturado utilizando separação entre:

- catálogo de produtos;
- unidades físicas;
- movimentações operacionais;
- vendedores;
- vendas;
- caixas de distribuição.



## Tabelas Principais

`catalogo_produtos`

Representa os produtos únicos do sistema.

Exemplos:

- Plax 1,5l
- Top Preto G
- Fone Corsair

Essa separação evita duplicidade de nomes e inconsistências.



`produtos`

Representa cada unidade física individual do estoque.

Cada item possui:

- status;
- validade;
- localização;
- vendedor;
- vínculo com venda;
- vínculo com caixa.



`quantidade_estoque`

Tabela criada para consolidação automática de:

- quantidade disponível;
- quantidade total;
- quantidade vendida;
- valor total por produto.



`caixas`

Controle de produtos enviados para vendedores.



`vendas`

Controle de vendas realizadas e rastreabilidade de vendedores responsáveis.

## Prints do Projeto
## Estrutura de Dados

## Automações

## Interface

## Visão Geral do Projeto


## Demonstração em Vídeo

Os vídeos demonstrativos do projeto estão disponíveis nos links abaixo:

- Estrutura das tabelas: [LINK_AQUI](https://youtu.be/J6YHfYjYcWQ)
- Automações: [LINK_AQUI](https://youtu.be/BQS3jzeWvRU)
- Interfaces: [LINK_AQUI](https://youtu.be/3RAlybUeUKQ)


## Documentação Adicional
- [Modelagem](docs/modelagem.md)
- [Automações](docs/automacoes.md)
- [Aprendizados](docs/aprendizados.md)


## Principais Aprendizados

Durante o desenvolvimento deste projeto foram trabalhados conceitos relacionados a:

- modelagem relacional;
- organização de processos;
- automações no-code;
- estruturação operacional;
- integridade de dados;
- UX em interfaces administrativas;
- controle de estoque;
- separação entre catálogo e unidade física.


## Melhorias Futuras
- Controle de acesso por usuário;
- Login para vendedores;
- Dashboard financeiro;
- Relatórios operacionais;
- Controle de comissão;
- Integração com ferramentas externas;
- Migração futura para aplicação própria.


## Tecnologias e Conceitos Trabalhados
- Airtable
- No-code
- Data Modeling
- Workflow Automation
- Inventory Management
- Relational Structure
- Operational Process Design
