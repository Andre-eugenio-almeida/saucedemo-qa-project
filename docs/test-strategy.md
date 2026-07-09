# Estratégia de Testes

## 1. Objetivo

Definir a abordagem de testes utilizada no projeto SauceDemo QA Project, garantindo que as funcionalidades da aplicação sejam validadas por meio de testes manuais e automatizados, seguindo boas práticas de Qualidade de Software.

---

# 2. Objetivos da Estratégia

* Garantir que os requisitos funcionais sejam atendidos.
* Detectar defeitos o mais cedo possível.
* Reduzir riscos antes da entrega.
* Automatizar cenários críticos.
* Facilitar a execução contínua dos testes.

---

# 3. Abordagem de Testes

Os testes serão executados em etapas:

### Etapa 1 – Análise

* Estudo dos requisitos.
* Identificação das regras de negócio.
* Levantamento dos riscos.

### Etapa 2 – Testes Manuais

Execução dos principais fluxos da aplicação para validar:

* Login
* Produtos
* Carrinho
* Checkout
* Logout

### Etapa 3 – Automação Web

Automação dos cenários críticos utilizando:

* Robot Framework
* Selenium
* Cypress

### Etapa 4 – Testes de API

Validação dos serviços utilizando:

* Postman
* Newman

### Etapa 5 – Integração Contínua

Execução automática dos testes utilizando GitHub Actions a cada atualização do repositório.

---

# 4. Técnicas de Teste

Serão utilizadas as seguintes técnicas:

## Testes Funcionais

Validar se o sistema atende aos requisitos definidos.

## Testes Exploratórios

Explorar funcionalidades sem roteiro rígido para identificar comportamentos inesperados.

## Testes de Regressão

Garantir que novas alterações não afetem funcionalidades já aprovadas.

## Testes de Interface

Validar elementos visuais e fluxo de navegação.

## Testes de API

Validar respostas, códigos HTTP, tempos de resposta e estrutura dos dados.

---

# 5. Critérios de Priorização

Os cenários serão executados conforme a seguinte prioridade:

### Alta

* Login
* Carrinho
* Checkout

### Média

* Produtos
* Menu

### Baixa

* Ordenação
* Informações complementares

---

# 6. Registro de Defeitos

Todo defeito identificado deverá conter:

* Título
* Descrição
* Passos para reprodução
* Resultado esperado
* Resultado obtido
* Severidade
* Prioridade
* Evidências

---

# 7. Evidências

Serão registradas:

* Capturas de tela
* Relatórios de execução
* Logs
* Vídeos (quando necessário)

---

# 8. Ferramentas

## Documentação

* Markdown

## Versionamento

* Git
* GitHub

## Testes Manuais

* Casos de teste
* Relatórios de execução

## Automação

* Robot Framework
* Selenium
* Cypress

## API

* Postman
* Newman

## CI/CD

* GitHub Actions

---

# 9. Métricas

Durante o projeto serão acompanhados:

* Quantidade de casos de teste
* Casos executados
* Casos aprovados
* Casos reprovados
* Bugs encontrados
* Bugs corrigidos
* Cobertura dos cenários críticos

---

# 10. Resultado Esperado

Ao final do projeto espera-se:

* Documentação completa.
* Casos de teste organizados.
* Evidências registradas.
* Automação dos principais fluxos.
* Execução automática via CI/CD.
* Projeto estruturado para apresentação em portfólio.
