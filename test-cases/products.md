# Casos de Teste - Produtos

## Informações

**Módulo:** Produtos

**Prioridade:** Alta

**Responsável:** André Almeida

---

# CT-101 – Exibir lista de produtos

## Objetivo

Validar que todos os produtos sejam exibidos após o login.

### Pré-condições

* Usuário autenticado.

### Passos

1. Realizar login.
2. Acessar a página de produtos.

### Resultado Esperado

* A lista de produtos deve ser exibida.
* Cada produto deve conter nome, descrição, preço, imagem e botão "Add to cart".

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-102 – Adicionar produto ao carrinho

### Passos

1. Selecionar um produto.
2. Clicar em "Add to cart".

### Resultado Esperado

* O botão deve mudar para "Remove".
* O contador do carrinho deve exibir 1 item.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-103 – Remover produto do carrinho

### Passos

1. Adicionar um produto ao carrinho.
2. Clicar em "Remove".

### Resultado Esperado

* Produto removido.
* Contador do carrinho atualizado.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-104 – Ordenar produtos por nome (A → Z)

### Passos

1. Abrir o filtro.
2. Selecionar "Name (A to Z)".

### Resultado Esperado

Produtos exibidos em ordem alfabética crescente.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-105 – Ordenar produtos por nome (Z → A)

### Passos

1. Selecionar "Name (Z to A)".

### Resultado Esperado

Produtos exibidos em ordem alfabética decrescente.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-106 – Ordenar produtos por menor preço

### Passos

1. Selecionar "Price (low to high)".

### Resultado Esperado

Produtos ordenados do menor para o maior preço.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-107 – Ordenar produtos por maior preço

### Passos

1. Selecionar "Price (high to low)".

### Resultado Esperado

Produtos ordenados do maior para o menor preço.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-108 – Abrir detalhes de um produto

### Passos

1. Clicar no nome de um produto.

### Resultado Esperado

A página de detalhes do produto deve ser exibida corretamente.

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-109 – Validar informações do produto

### Passos

1. Abrir os detalhes de um produto.

### Resultado Esperado

Devem ser exibidos:

* Nome
* Descrição
* Preço
* Imagem
* Botão "Add to cart"

### Tipo

Teste Funcional

### Status

Não Executado
