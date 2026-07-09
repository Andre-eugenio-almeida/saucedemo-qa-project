# Casos de Teste - Login

## Informações

**Módulo:** Login

**Prioridade:** Alta

**Responsável:** André Almeida

---

# CT-001 – Login com credenciais válidas

## Objetivo

Validar que um usuário autenticado consegue acessar o sistema.

### Pré-condições

* Aplicação disponível.
* Usuário válido cadastrado.

### Massa de teste

**Usuário**

standard_user

**Senha**

secret_sauce

### Passos

1. Acessar a página inicial.
2. Informar usuário válido.
3. Informar senha válida.
4. Clicar em **Login**.

### Resultado Esperado

* Login realizado com sucesso.
* Página de produtos exibida.

### Prioridade

Alta

### Tipo

Teste Funcional

### Status

Não Executado

---

# CT-002 – Senha incorreta

## Objetivo

Validar que o sistema não permita login com senha inválida.

### Pré-condições

Aplicação disponível.

### Massa de teste

Usuário

standard_user

Senha

123456

### Passos

1. Informar usuário válido.
2. Informar senha inválida.
3. Clicar em Login.

### Resultado Esperado

* Exibir mensagem de erro.
* Permanecer na tela de login.

### Prioridade

Alta

### Tipo

Teste Negativo

### Status

Não Executado

---

# CT-003 – Usuário inexistente

### Objetivo

Validar tentativa de login com usuário inexistente.

### Massa de teste

Usuário

usuario123

Senha

secret_sauce

### Passos

1. Informar usuário inexistente.
2. Informar senha.
3. Clicar em Login.

### Resultado Esperado

Exibir mensagem de erro.

### Prioridade

Alta

### Tipo

Teste Negativo

### Status

Não Executado

---

# CT-004 – Campo usuário vazio

### Passos

1. Não preencher usuário.
2. Informar senha.
3. Clicar em Login.

### Resultado Esperado

Mensagem informando que o usuário é obrigatório.

### Prioridade

Alta

### Tipo

Validação

### Status

Não Executado

---

# CT-005 – Campo senha vazio

### Passos

1. Informar usuário.
2. Não preencher senha.
3. Clicar em Login.

### Resultado Esperado

Mensagem informando que a senha é obrigatória.

### Prioridade

Alta

### Tipo

Validação

### Status

Não Executado

---

# CT-006 – Usuário bloqueado

### Massa de teste

Usuário

locked_out_user

Senha

secret_sauce

### Passos

1. Informar usuário bloqueado.
2. Informar senha.
3. Clicar em Login.

### Resultado Esperado

Mensagem informando que o usuário está bloqueado.

### Prioridade

Alta

### Tipo

Teste Funcional

### Status

Não Executado
