# Banco de Dados Escola — SQL Server

Repositório com um banco de dados desenvolvido em **SQL Server**, com foco na prática de criação e manipulação de bancos de dados relacionais.

## 📚 Estrutura do banco

O banco de dados `escola` possui as seguintes tabelas:

* **alunos** — informações dos alunos
* **docentes** — informações dos docentes
* **cursos** — cursos disponíveis
* **disciplinas** — disciplinas relacionadas aos cursos
* **notas** — notas dos alunos nas disciplinas
* **salas** — salas disponíveis
* **funcionarios** — informações dos funcionários
* **matriculas** — matrículas dos alunos nos cursos
* **alunos_cursos** — relacionamento entre alunos e cursos
* **funcionarios_salas** — relacionamento entre funcionários e salas
* **docentes_salas** — relacionamento entre docentes e salas

## 🧠 Conceitos praticados

* Criação de banco de dados
* Criação de tabelas
* Chaves primárias (`PRIMARY KEY`)
* Chaves estrangeiras (`FOREIGN KEY`)
* `IDENTITY`
* `NOT NULL`
* `UNIQUE`
* Relacionamentos entre tabelas
* Relacionamentos **1:N**
* Relacionamentos **N:N**
* Inserção de dados com `INSERT`
* Alteração de tabelas com `ALTER TABLE`
* Remoção de constraints
* Consultas ao sistema do SQL Server
* Modelagem de banco de dados relacional

## 🔗 Relacionamentos

O banco possui relacionamentos entre diferentes entidades, incluindo tabelas associativas para representar relacionamentos **N:N**, como `alunos_cursos`, `funcionarios_salas` e `docentes_salas`.

## 🎯 Objetivo

Praticar os fundamentos de **SQL Server e bancos de dados relacionais**, desenvolvendo tabelas, relacionamentos, chaves e operações de manipulação de dados.
