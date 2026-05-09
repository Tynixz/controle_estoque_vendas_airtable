# Modelagem de Dados

## Estrutura do projeto

O sistema foi estruturado utilizando separação entre:

- catálogo de produtos;
- unidades físicas;
- movimentação operacional;
- controle de vendas;
- distribuição para vendedores.

---

## Catálogo de Produtos

A tabela `catalogo_produtos` representa os produtos únicos do sistema.

Exemplo:

- Plax 1,5l
- Top Preto G
- Fone Corsair

Essa separação evita duplicidade de nomes e inconsistências.

---

## Produtos

A tabela `produtos` representa cada unidade física individual.

Cada item possui:

- status;
- validade;
- localização;
- vendedor;
- vínculo com caixa;
- vínculo com venda.

---

## Quantidade em estoque

A tabela `quantidade_estoque` foi criada para consolidar:

- quantidade disponível;
- quantidade total;
- quantidade vendida;
- valor total por produto.

Os valores são calculados automaticamente através de rollups e lookups.

---

## Separação catálogo x unidade física

Uma das principais decisões do projeto foi separar:

- produto mestre;
- item físico individual.

Isso permitiu controlar status individuais mesmo em produtos iguais.
