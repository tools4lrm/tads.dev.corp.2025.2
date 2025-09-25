# Artefatos do Processo de Software

Este documento define a estrutura e o propósito dos principais artefatos utilizados em nosso processo de desenvolvimento de software.

---

## 1. Documento de Visão

### Propósito
O **Documento de Visão** estabelece o propósito do produto, seu escopo de alto nível e a justificativa de negócio para sua criação. Ele serve como o principal guia e "contrato" inicial entre o negócio e a equipe técnica, definindo **o que** será construído e **por que**.

### Template

```markdown
# Documento de Visão: [Nome do Produto/Projeto]

## 1. Contexto de Negócio
*(Descreva a situação atual, o problema ou a oportunidade de mercado que motiva a criação deste software.)*

**Exemplo:** Atualmente, a gestão de estoque é manual, gerando erros de contagem e atrasos na reposição, impactando negativamente a satisfação do cliente.

## 2. Escopo do Produto
*(Defina claramente o que o produto fará e, mais importante, o que ele **não** fará (exclusões).)*

- **Funcionalidades Chave (Alto Nível):**
    - [Exemplo: Cadastro de Fornecedores e Produtos]
    - [Exemplo: Rastreamento em tempo real do nível de estoque]
    - [Exemplo: Geração de relatórios de baixa de estoque]

- **Fora do Escopo:**
    - [Exemplo: Integração com o sistema de contabilidade externo]
    - [Exemplo: Aplicativo móvel para gerentes]

## 3. Diagrama de Casos de Uso (Simplificado)
*(Representação visual simples das principais funcionalidades e dos atores que as utilizam.)*

```

---

## 2. História de Usuário

### Propósito
A **História de Usuário** descreve uma funcionalidade do sistema a partir da perspectiva de quem a utiliza. Seu principal objetivo é focar no **valor** entregue ao usuário, detalhando o requisito de forma concisa e testável. É a principal unidade de trabalho para a equipe de desenvolvimento.

### Template

```markdown
# História de Usuário: [ID da HU - Título Conciso]

## 1. Descrição (Formato Padrão)
**COMO** [Tipo de Usuário/Papel],
**QUERO** [Funcionalidade/Objetivo],
**PARA** [Valor de Negócio/Benefício].

**Exemplo:**
**Como um** *Analista de Negócio*,
**Eu quero** *filtrar a lista de Histórias por estado (Nova, Em Desenvolvimento, Teste)*,
**Para que** *eu possa gerenciar de forma eficiente o fluxo de trabalho*.

## 2. Critérios de Aceitação
*(Condições de sucesso, em formato de teste, que devem ser satisfeitas para que a História seja considerada completa e funcional.)*

- **Cenário 1:** O usuário deve conseguir selecionar apenas um estado por vez para filtrar a lista.
    - **Dado** que estou na tela de lista de Histórias.
    - **E** existem histórias nos estados 'Nova', 'Desenvolvimento' e 'Teste'.
    - **Quando** eu seleciono o filtro 'Teste'.
    - **Então** apenas as histórias no estado 'Teste' são exibidas.

- **Cenário 2:** A remoção do filtro deve retornar a lista completa.
    - **Dado** que a lista está filtrada pelo estado 'Teste'.
    - **Quando** eu clico no botão "Limpar Filtro".
    - **Então** todas as histórias de todos os estados são exibidas novamente.

```

## 3. Produto (Software Executável)

O Produto é o artefato final e tangível de todo o processo. Representa o software funcional, testado e pronto para ser entregue aos usuários ou disponibilizado em um ambiente de produção/teste. É a manifestação concreta das Histórias de Usuário implementadas.

### Template

```markdown
```
