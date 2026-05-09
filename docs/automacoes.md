# Automações

## STATUS_PRODUTO_CAIXA

Quando um produto é vinculado a uma caixa:

- o status muda automaticamente para:
  - `Com vendedor`

---

## STATUS_PRODUTO_VENDA

Quando uma venda é registrada:

- o status do produto muda para:
  - `Vendido`

- o vendedor responsável é vinculado ao produto.

---

## Controle automático de estoque

Os cálculos de disponibilidade utilizam:

- lookups;
- rollups;
- filtros condicionais.

Isso permite visualizar automaticamente:

- itens disponíveis;
- itens vendidos;
- itens com vendedores.
