# Atividades do Processo de Software

Este documento detalha o fluxo de trabalho do processo de software, definindo o propósito e as ações primárias de cada atividade.

---

## 1. Analisar Negócio

### Propósito
A atividade **Analisar Negócio** é o ponto de partida do processo. Seu objetivo é **entender profundamente o contexto**, os **objetivos de negócio** e as **necessidades** do cliente/mercado. Esta etapa garante que o trabalho a ser realizado entregue o máximo valor estratégico.

### Responsável Principal
**[Analista de Negócio (AN)](papeis.md#analista-de-negócio-an)**.

### Fluxo de Artefatos

| Elemento | Descrição |
| :--- | :--- |
| **Entradas** | Solicitações do Cliente, Problemas/Oportunidades de Mercado, Estratégias de Negócio. |
| **Saídas** | Escopo do Projeto Definido, Requisitos de Alto Nível, **[Documento de Visão](artefatos.md#1-documento-de-visão)**. |

### Principais Tarefas
1.  **Levantamento de Necessidades:** Entrevistar *stakeholders* e clientes para identificar problemas e objetivos.
2.  **Análise de Viabilidade:** Avaliar se a solução proposta é tecnicamente viável e financeiramente justificada.
3.  **Definição de Escopo:** Determinar os limites claros do projeto (*in-scope* e *out-of-scope*).
4.  **Priorização Inicial:** Estabelecer uma ordem de importância para os requisitos de alto nível.
5.  **Documentação da Visão:** Criar o **[Documento de Visão](artefatos.md#1-documento-de-visão)** que formaliza os resultados desta análise.

---

## 2. Especificar

### Propósito
A atividade **Especificar** transforma a visão de alto nível em detalhes **operacionais e técnicos**. O objetivo é refinar os requisitos em unidades de trabalho claras, **não ambíguas e testáveis** para a equipe de desenvolvimento.

### Responsável Principal
**[Analista de Req/Q](papeis.md#analista-de-reqq-analista-de-requisitos-e-qualidade)**.

### Fluxo de Artefatos

| Elemento | Descrição |
| :--- | :--- |
| **Entradas** | **[Documento de Visão](artefatos.md#1-documento-de-visão)**, Requisitos de Alto Nível. |
| **Saídas** | **[Histórias de Usuário](artefatos.md#2-história-de-usuário)** detalhadas com Critérios de Aceitação. |

### Principais Tarefas
1.  **Elaboração de Histórias:** Desmembrar os requisitos de alto nível em **[Histórias de Usuário](artefatos.md#2-história-de-usuário)** no formato "Como... eu quero... para que...".
2.  **Definição de Critérios de Aceitação:** Escrever as condições de sucesso que devem ser satisfeitas para que uma História seja considerada concluída (critérios que guiarão o teste).
4.  **Refinamento com a [Equipe](papeis.md#papeis):** Apresentar e discutir as especificações detalhadas com o **[Desenvolvedor](papeis.md#desenvolvedor)** para garantir a clareza e a viabilidade técnica.

---

## 3. Codificar

### Propósito
A atividade **Codificar** é a implementação técnica. O objetivo é escrever, testar e integrar o **código-fonte** que transformará as **[Histórias de Usuário](artefatos.md#2-história-de-usuário)** em um **[Produto](artefatos.md#3-produto-software-executável)** funcional e executável, mantendo padrões de qualidade e desempenho.

### Responsável Principal
**[Desenvolvedor](papeis.md#desenvolvedor)**.

### Fluxo de Artefatos

| Elemento | Descrição |
| :--- | :--- |
| **Entradas** | **[Histórias de Usuário](artefatos.md#2-história-de-usuário)** detalhadas com Critérios de Aceitação. |
| **Saídas** | **[Produto](artefatos.md#3-produto-software-executável)** (Software Executável), Código-fonte, Testes Unitários Aprovados. |

### Principais Tarefas
1.  **Design de Baixo Nível:** Planejar a estrutura interna do código (classes, funções, etc.) para implementar a funcionalidade.
2.  **Escrita do Código:** Implementar a lógica da funcionalidade conforme definido nas Histórias de Usuário.
4.  **Integração:** Unir o código desenvolvido com o restante do sistema, resolvendo conflitos.
6.  **Geração do Produto:** Compilar e empacotar o software executável (**[Produto](artefatos.md#3-produto-software-executável)**) para entrega ao ambiente de testes.