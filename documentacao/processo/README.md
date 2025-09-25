
# Definição de Padrões e Processo de Desenvolvimento de Software   

---

## Processo

**Papeis**   
    - [Analista de Negócio]() : Responsável por entender as necessidades do cliente/mercado e traduzi-las em funcionalidades priorizadas pelo valor proporcionado.   
    - [Analista de Req/Q]() : Responsável por detalhar, documentar e gerenciar os artefatos de requisitos, garantindo a qualidade do produto.  
    - [Desenvolvedor]() : Responsável por projetar e construir o software, transformando os artefatos de requisitos detalhados em código funcional.   

**Artefatos**   
    - [Documento de Visão]() : Artefato responsável por compreender uma visão geral do produto que está sendo desenvolvido.    
    - [História de Usuário]() : Artefato que descreverá uma funcionalidade do sistema.   
    - [Produto]() : Artefato executável e entregável do que foi solicitado e desenvolvido.  

**Atividades**   
    - [Analisar Negócio]() : Entender o contexto, objetivos, problemas e oportunidades do cliente/mercado. Resulta na definição de escopo e em uma visão geral.  
    - [Especificar]() : Detalhar as funcionalidades de alto nível em Histórias de Usuário claras e testáveis.   
    - [Codificar]() : Escrever, testar unitariamente e integrar o código-fonte para implementar as funcionalidades definidas nas Histórias de Usuário.  

---
## Padrões Estabelecidos para o Desenvolvimento   

**Padrão de Diretórios** - Artefatos só podem ser criados dentro dessa estrutura estabelecida. 

- [Requisistos](documentacao/requisitos/) : Artefatos que desencadeará a descrição das funcionalidades funcionais e não funcionais do programa.
- [Código Fonte](codificacao/) : Artefatos de código/configuração do programa, aplicação/produto em si.

**Padrão para criar os Artefatos de Requisitos** - Os artefatos de requisitos deverão **representar apenas uma funcionalidade**, seguir **o padrão de nomenclatura estabelecido e descrito pelo ambiente** e **uma estrutura de diretório com nomes significativos** para organizar esses artefatos dentro do diretório padrão de [Requisitos](documentacao/requisitos/).

 - A estrutura de diretórios que armazenará esses artefatos de requisitos criados e mantidos no diretório [Requisitos](documentacao/requisitos/), deverá seguir esta classificação primária : (a) para as necessidades do domínio do problema, os artefatos de requisitos deverão ser organizados no diretório [Requisitos Funcionais](documentao/requisitos/funcionais); (b) para as necessidades determinadas por lei, os artefatos de requisitos deverão ser organizados no diretório [Requisitos Legais](documentacao/requisitos/legais) (c) para características de qualidade do produto, os artefatos de requisitos deverão ser organizados no diretório [Requisitos Não-Funcionais](documentacao/requisitos/n-funcionais);   
   
 - Padrão de nomenclatura
   - `REQ.` como prefixo para identificar os artefatos de requisitos que irão contextualizar (indexam / contextualizam) especificações de requisitos arquivos que carregam a documentação;
   - Em seguida, dentro do diretório no qual ele será criado, uma identificação numérica de três dígitos (`REQ.000`) que consiga identificar o artefato de modo único e exclusivo.
   - Por fim, utilizaremos a extensão `.md` para permitir a utilização da [Linguagem de Marcação Markdown](https://www.markdownguide.org/) com intuito de formatar os artefatos de requisitos, possibilitando criar artefatos organizados e de estrutura fluida. (ex.: `REQ.000.md`)
 