# Requisitos do Sistema

## Projeto

**Sistema:** SauceDemo

**Objetivo:**

Validar as principais funcionalidades do sistema de comércio eletrônico SauceDemo, garantindo que os requisitos funcionais e não funcionais sejam atendidos.

---

# Requisitos Funcionais

## RF001 – Login

O sistema deve permitir que um usuário autenticado realize login utilizando usuário e senha válidos.

### Critérios de Aceitação

* O usuário deve informar login e senha.
* O sistema deve validar as credenciais.
* Após autenticação, o usuário deve ser direcionado para a página de produtos.

---

## RF002 – Login Inválido

O sistema deve impedir acesso utilizando credenciais inválidas.

### Critérios de Aceitação

* Exibir mensagem de erro.
* Permanecer na tela de login.

---

## RF003 – Usuário Bloqueado

Usuários bloqueados não podem acessar o sistema.

### Critérios de Aceitação

* Exibir mensagem informando que o usuário está bloqueado.
* Não permitir acesso.

---

## RF004 – Listagem de Produtos

Após o login, o sistema deve apresentar a lista de produtos disponíveis.

### Critérios de Aceitação

* Exibir nome.
* Exibir descrição.
* Exibir preço.
* Exibir botão "Add to cart".

---

## RF005 – Carrinho

O usuário deve conseguir adicionar e remover produtos do carrinho.

### Critérios de Aceitação

* Atualizar quantidade de itens.
* Atualizar botão "Add to cart" para "Remove".

---

## RF006 – Checkout

O sistema deve permitir finalizar uma compra.

### Critérios de Aceitação

* Solicitar Nome.
* Solicitar Sobrenome.
* Solicitar CEP.
* Exibir resumo da compra.
* Finalizar pedido.

---

## RF007 – Logout

O usuário deve conseguir encerrar sua sessão.

### Critérios de Aceitação

* Retornar para a tela de login.
* Invalidar a sessão.

---

# Requisitos Não Funcionais

## RNF001 – Performance

* O login deve responder em tempo adequado.
* A navegação entre páginas deve ser fluida.

---

## RNF002 – Usabilidade

* Interface intuitiva.
* Botões facilmente identificáveis.
* Mensagens claras ao usuário.

---

## RNF003 – Compatibilidade

O sistema deve funcionar corretamente nos principais navegadores modernos.

---

# Regras de Negócio

### RN001

Somente usuários válidos podem acessar o sistema.

### RN002

Usuários bloqueados não podem efetuar login.

### RN003

Não é permitido finalizar uma compra com campos obrigatórios vazios.

### RN004

O carrinho deve refletir corretamente os produtos adicionados ou removidos.

---

# Funcionalidades Identificadas

* Login
* Logout
* Produtos
* Carrinho
* Checkout
* Menu lateral
* Ordenação de produtos
* Informações dos produtos

---

# Riscos Identificados

* Falha na autenticação.
* Perda de itens do carrinho.
* Erros na finalização da compra.
* Mensagens de erro incorretas.
* Problemas de navegação entre páginas.

---

# Fora do Escopo

Este projeto não contempla:

* Testes de pagamento.
* Integrações com sistemas externos.
* Testes de segurança avançados.
* Testes de carga.
