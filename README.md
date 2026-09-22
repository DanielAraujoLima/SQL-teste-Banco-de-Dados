Projeto Banco de Dados — Teste SQL

Este projeto foi desenvolvido como um **teste e estudo pessoal sobre SQL e bancos de dados**, com o objetivo de compreender melhor a criação, organização e relacionamento entre diferentes tabelas.

Durante o desenvolvimento, foram explorados conceitos importantes de banco de dados, como **chaves primárias, chaves estrangeiras, relacionamentos entre tabelas e manipulação de dados**.

Objetivo

O principal objetivo deste projeto é colocar em prática conhecimentos relacionados a:

* Criação de bancos de dados;
* Criação e organização de tabelas;
* Definição de **chaves primárias (PRIMARY KEY)**;
* Definição de **chaves estrangeiras (FOREIGN KEY)**;
* Relacionamento entre tabelas;
* Inserção e manipulação de dados;
* Consultas utilizando SQL;
* Estruturação e organização de um banco de dados.

Tecnologias utilizadas

* **SQL**
* Banco de dados utilizado: `[adicione aqui: MySQL, PostgreSQL, SQLite, etc.]`

Sobre o projeto

Este banco de dados foi criado exclusivamente para fins de **aprendizado e testes**.

A ideia é utilizar uma estrutura simples para entender, na prática, como os dados são armazenados e como diferentes tabelas podem se relacionar por meio de chaves primárias e estrangeiras.

O projeto também serve como uma forma de praticar comandos SQL e compreender melhor a estrutura de um banco de dados relacional.

Conceitos estudados

### Primary Key

A **chave primária** é utilizada para identificar de forma única cada registro dentro de uma tabela.

Exemplo:

```sql
id INT PRIMARY KEY
```

### Foreign Key

A **chave estrangeira** é utilizada para criar um relacionamento entre tabelas, fazendo referência à chave primária de outra tabela.

Exemplo:

```sql
FOREIGN KEY (id_usuario) REFERENCES usuarios(id)
```

Estrutura

A estrutura do projeto contém os arquivos necessários para a criação e manipulação do banco de dados.

```text
projeto-banco-dados
 ├── README.md
 ├── banco.sql
 └── outros arquivos
```

 Como utilizar

1. Clone este repositório:

```bash
git clone URL_DO_REPOSITORIO
```

2. Abra o arquivo SQL no seu sistema de gerenciamento de banco de dados.

3. Execute os comandos presentes no arquivo `banco.sql`.

4. Explore as tabelas, relacionamentos e consultas disponíveis no projeto.

Observação

Este é um **projeto de estudo**, criado para praticar e compreender melhor os conceitos de SQL e bancos de dados relacionais.

Novas tabelas, relacionamentos e consultas poderão ser adicionados conforme o aprendizado evoluir.

---

**Projeto desenvolvido para fins de aprendizado e prática com SQL.**
