
| Documento      | MET-002 - Estrutura do Projeto |
| -------------- | ------------------------------ |
| Versão         | 2.0                            |
| Status         | Aprovado                       |
| Ultima revisão | 28/07/2026                     |



## 1. Objetivo 

Este documento descreve a organização estrutural do Projeto Victor e a responsabilidade de cada uma de suas categorias.

A estrutura foi projetada para facilitar a evolução contínua do conhecimento, mantendo os artefatos organizados e evitando duplicação de informações por meio de relacionamentos entre documentos.

---

# Arquitetura Geral

```text
Projeto Victor
│
├── 00. Metodologia
├── 01. Iniciação
├── 02. Objetivos
├── 03. Projetos
├── 04. Labs
├── 05. Conteúdo
└── 06. Recursos
```

Cada categoria possui uma responsabilidade específica e representa um tipo de artefato dentro do projeto.

---

# Categorias

## 00. Metodologia

Contém os documentos que definem como o Projeto Victor funciona.

Exemplos:

- Metodologia
    
- Estrutura do Projeto
    
- Convenções
    
- Padrão de Commits
    
- Glossário
    

---

## 01. Iniciação

Reúne os documentos responsáveis por definir a identidade do Projeto Victor.

Exemplos:

- Termo de Abertura
    
- Visão do Projeto
    
- Escopo
    

---

## 02. Objetivos

Representa os Objetivos de Aprendizado.

Cada objetivo descreve uma necessidade de desenvolvimento e centraliza seu planejamento, progresso e relacionamentos.

Exemplos:

- OBJ-001 — Infraestrutura
    
- OBJ-002 — React
    
- OBJ-003 — Cloud
    

---

## 03. Projetos

Contém projetos utilizados para aplicação prática do conhecimento.

Os projetos existem para desenvolver competências e gerar evidências de aprendizado.

Um projeto pode contribuir para diversos Objetivos de Aprendizado.

Exemplos:

- PROJ-001 — Ferraz Armazéns
    
- PROJ-002 — Portal Corporativo
    

---

## 04. Labs

Contém laboratórios de estudo e experimentação.

Os Labs possuem escopo reduzido e são utilizados para validar tecnologias antes de sua utilização em projetos maiores.

Exemplos:

- LAB-001 — DNS
    
- LAB-002 — Active Directory
    
- LAB-003 — Docker
    

---

## 05. Conteúdo

Reúne os materiais produzidos durante o desenvolvimento dos Objetivos de Aprendizado.

Exemplos:

- Vídeos
    
- Artigos
    
- Apresentações
    
- Roteiros
    

---

## 06. Recursos

Contém referências utilizadas durante os estudos.

Esta categoria registra apenas a utilização dos recursos.

Os resumos e anotações detalhadas permanecem no Segundo Cérebro (Obsidian).

Exemplos:

- Livros
    
- Cursos
    
- Documentação Oficial
    
- Ferramentas
    

---

# Relacionamentos

A organização física do projeto é feita por categorias.

A organização lógica é realizada por meio de relacionamentos entre os documentos.

Isso permite que um mesmo artefato seja reutilizado em diferentes contextos sem duplicação de informações.

Exemplo:

```text
OBJ-001 Infraestrutura
        │
        ├──────────────┐
        │              │
        ▼              ▼

PROJ-001        LAB-002

        │
        ▼

VID-001
```

Nesse exemplo:

- O Projeto Ferraz Armazéns contribui para o Objetivo de Infraestrutura.
    
- O Lab de Active Directory apoia o projeto.
    
- Um vídeo documenta a implementação realizada.
    

Todos permanecem independentes, sendo conectados apenas por referências.

---

# Princípios da Estrutura

A arquitetura do Projeto Victor segue os seguintes princípios:

- Cada artefato possui uma única responsabilidade.
    
- As categorias organizam os arquivos fisicamente.
    
- Os relacionamentos organizam o conhecimento logicamente.
    
- Sempre que possível, evita-se duplicação de informações.
    
- Um artefato pode contribuir para diversos Objetivos de Aprendizado.
    
- O projeto deve permanecer simples, escalável e de fácil manutenção.
    

---

# Evolução

A estrutura apresentada neste documento poderá evoluir conforme novas necessidades forem identificadas.

Alterações estruturais devem preservar os princípios definidos nesta documentação e buscar manter a organização, a rastreabilidade e a simplicidade do projeto.