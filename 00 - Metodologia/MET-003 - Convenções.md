

| Documento      | MET-003 - Convenções                               |
| -------------- | -------------------------------------------------- |
| Versão         | 2.0                                                |
| Status         | Aprovado                                           |
| Ultima revisão | 28/07/2026                                         |
| Data de Início | Data de criação do projeto.                        |
| Última Revisão | Data da última revisão significativa do documento. |


## Objetivo

Este documento define os padrões de nomenclatura, organização e escrita utilizados no projeto.

Seu objetivo é garantir consistência entre os artefatos produzidos, facilitar a navegação pelo projeto e manter um histórico organizado durante sua evolução.

---

## Convenções de Pastas

As categorias principais do projeto são numeradas para representar sua organização lógica.

0. Metodologia
1. Iniciação
2. Objetivos
3. Projetos
4. Labs
5. Conteúdo
6. Recursos

A numeração possui finalidade organizacional e não representa obrigatoriamente uma sequência de execução. 

---

## Convenções de Documentos

Os documentos utilizam identificadores únicos de acordo com sua categoria.

### Metodologia

MET-001 - Metodologia.md
MET-002 - Estrutura do Projeto.md
MET-003 - Convenções.md
MET-004 - Padrão de Commits.md
MET-005 - Glossário.md

---

### Iniciação

INIT-001 - Termo de Abertura.md
INIT-002 - Visão do Projeto.md
INIT-003 - Escopo.md

---

### Objetivos

Cada Objetivo de Aprendizado recebe um identificador único.

OBJ-001 - Infraestrutura
OBJ-002 - React
OBJ-003 - Cloud

---

### Projetos

PROJ-001 - Ferraz Armazéns
PROJ-002 - Portal Corporativo

---

### Labs

LAB-001 - DNS
LAB-002 - Active Directory
LAB-003 - Docker

---

## Conteúdo

### Vídeos

VID-001 - Introdução ao DNS
VID-002 - Active Directory

### Artigos

ART-001 - O que é DNS
ART-002 - Active Directory

### Apresentações

APR-001 - Arquitetura da Solução

---

### Recursos

Livros

LIV-001 - Systems Analysis and Design

### Cursos

CUR-001 - Windows Server

### Documentações

DOC-001 - Docker Documentation

---

## Convenções de Escrita

Sempre que possível:

- Utilizar linguagem clara e objetiva.
- Evitar ambiguidades.
- Preferir frases curtas.
- Documentar decisões importantes.
- Explicar o "porquê" das decisões, não apenas o "como".

---

## Convenções de Relacionamentos

Os artefatos devem ser relacionados por seus identificadores.

Exemplo:

OBJ-001

### Projetos Relacionados

- PROJ-001

### Labs Relacionados

- LAB-001
- LAB-002

### Conteúdos Relacionados

- VID-001
- ART-002

### Recursos Utilizados

- LIV-001
- CUR-001

Os relacionamentos devem ser utilizados sempre que um artefato contribuir para outro.

Sempre que possível, deve-se evitar duplicação de informações.

---

## Convenções de Versionamento

Alterações significativas devem ser registradas por meio de commits seguindo o padrão definido em MET-004 - Padrão de Commits.

Cada commit deve representar uma alteração lógica e independente.

---

## Convenções de Idioma

- Documentação em português brasileiro.
- Termos técnicos amplamente conhecidos poderão permanecer em inglês.
- Nomes de tecnologias, ferramentas e frameworks devem manter sua nomenclatura oficial.

---

## Convenções Gerais

O projeto adota os seguintes princípios de organização:

- Um artefato possui uma única responsabilidade.
- As categorias organizam os arquivos fisicamente.
- Os relacionamentos organizam o conhecimento logicamente.
- Sempre que possível, evitar duplicação de informações.
- Utilizar identificadores únicos para facilitar a rastreabilidade.

---
# Controle de Documentos

Todos os documentos do Projeto Victor devem iniciar com uma tabela de identificação, permitindo controlar informações básicas do projeto e do próprio documento.

O padrão adotado é:

| Campo          | Valor                                                                                     |
| -------------- | ----------------------------------------------------------------------------------------- |
| Documento      | Nome do documente.                                                                        |
| Versão         | Versão do documento.                                                                      |
| Ultima revisão | Data da revisão.                                                                          |
| Status         | Situação atual do documento (Em elaboração, Em revisão, Aprovado, Obsoleto ou Arquivado). |
| Data de Início | Data de criação do projeto.                                                               |
| Última Revisão | Data da última revisão significativa do documento.                                        |

Exemplo:

| Campo          | Valor                                 |
| -------------- | ------------------------------------- |
| Projeto        | Projeto Victor                        |
| Documento      | MET-001 - Metodologia                 |
| Tipo           | Framework de Desenvolvimento Contínuo |
| Versão         | 2.0                                   |
| Status         | Aprovado                              |
| Responsável    | Victor Angelo Ferraz de Oliveira      |
| Data de Início | 20/07/2026                            |
| Última Revisão | 28/07/2026                            |

### Versões

| Versão | Uso                                                        |
| ------ | ---------------------------------------------------------- |
| 1.0    | Primeira versão estável do documento.                      |
| 1.x    | Correções, ajustes e pequenas melhorias.                   |
| 2.0    | Mudanças estruturais ou revisão significativa do conteúdo. |
| n.0    | Novas revisões estruturais.                                |
## Alterações

Este documento poderá ser atualizado sempre que novas convenções forem necessárias.

Toda alteração deve buscar manter a consistência do projeto e preservar sua organização ao longo do tempo.