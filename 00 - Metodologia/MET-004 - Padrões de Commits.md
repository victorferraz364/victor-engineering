
| Campo          | Valor                        |
| -------------- | ---------------------------- |
| Documento      | MET-004 - Padrões de Commits |
| Versão         | 1.0                          |
| Status         | Aprovado                     |
| Ultima revisão | 20/07/2026                   |
## Objetivo

Este documento define o padrão de mensagens de commit utilizado no projeto.

O objetivo é manter um histórico organizado, consistente e rastreável, permitindo compreender facilmente a evolução do projeto ao longo do tempo.

---

# Estrutura

As mensagens de commit seguem o padrão:

```text
<tipo>: <descrição>
```

Exemplos:

```text
docs: adiciona metodologia do projeto

feat: cria objetivo de aprendizado em infraestrutura

project: inicia projeto Ferraz Armazéns

lab: implementa laboratório de DNS

content: adiciona roteiro do vídeo sobre Active Directory

study: adiciona referência do livro Systems Analysis and Design

refactor: reorganiza estrutura dos objetivos

fix: corrige referências entre projetos e objetivos

chore: atualiza estrutura inicial do repositório
```

---

# Tipos de Commit

## docs

Utilizado para alterações na documentação.

Exemplos:

- README
- Metodologia
- Documentação
- Diagramas
- Templates

Exemplo:

```text
docs: adiciona metodologia do projeto
```

---

## feat

Utilizado para adicionar uma nova funcionalidade.

Normalmente representa:

- novo Objetivo de Aprendizado;
- novo processo;
- nova funcionalidade da metodologia.

Exemplo:

```text
feat: cria objetivo de aprendizado em infraestrutura
```

---

## project

Utilizado para criação ou evolução de projetos.

Exemplos:

- Ferraz Armazéns
- Portal Corporativo

Exemplo:

```text
project: inicia projeto Ferraz Armazéns
```

---

## lab

Utilizado para criação ou evolução de laboratórios.

Exemplos:

- DNS
- Docker
- Active Directory
- VLAN

Exemplo:

```text
lab: implementa laboratório de Active Directory
```

---

## content

Utilizado para produção de conteúdo.

Exemplos:

- Vídeos
- Artigos
- Apresentações
- Roteiros

Exemplo:

```text
content: adiciona artigo sobre DNS
```

---

## study

Utilizado para registrar recursos de estudo utilizados durante o desenvolvimento.

Exemplos:

- Livros
- Cursos
- Documentações Oficiais
- Pesquisas

Exemplo:

```text
study: adiciona referências sobre Active Directory
```

---

## refactor

Utilizado para reorganizar ou melhorar a estrutura do projeto sem alterar seu comportamento ou conteúdo.

Exemplo:

```text
refactor: reorganiza estrutura dos laboratórios
```

---

## fix

Utilizado para correção de erros.

Exemplo:

```text
fix: corrige links entre objetivos e projetos
```

---

## chore

Utilizado para tarefas administrativas e manutenção do repositório.

Exemplos:

- .gitignore
- configuração
- estrutura de pastas
- arquivos auxiliares

Exemplo:

```text
chore: atualiza estrutura inicial do projeto
```

---

# Boas Práticas

- Cada commit deve representar uma alteração lógica e independente.
- Evite commits muito grandes contendo alterações sem relação entre si.
- Utilize descrições curtas, claras e objetivas.
- Escreva a descrição no presente do indicativo.
- Faça commits frequentemente durante o desenvolvimento.
- Sempre que possível, conclua uma pequena etapa antes de realizar um commit.

---

# Exemplos

```text
chore: bootstrap do projeto

docs: adiciona README do projeto

docs: define metodologia do projeto

docs: documenta estrutura do projeto

docs: define convenções

docs: define padrão de commits

docs: cria termo de abertura

feat: cria objetivo de aprendizado em infraestrutura

project: inicia projeto Ferraz Armazéns

lab: cria laboratório de DNS

content: adiciona roteiro do primeiro vídeo

study: adiciona referências sobre Windows Server

refactor: reorganiza estrutura dos projetos

fix: corrige relacionamentos entre objetivos e projetos
```

---

# Convenções

- Utilizar letras minúsculas no tipo do commit.
- Não utilizar ponto final na descrição.
- Evitar abreviações desnecessárias.
- Sempre que possível, um commit deve responder claramente à pergunta:

> **"O que foi alterado?"**

---

# Referências

Este padrão é inspirado na especificação **Conventional Commits**, com adaptações.