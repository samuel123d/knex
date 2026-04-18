# week_6
# Knex Data Management | Estrutura de Base de Dados

Este repositório é dedicado ao estudo e implementação de persistência de dados utilizando o **Knex.js**. O projeto foca na construção de uma camada de acesso a dados (DAL) eficiente, explorando a criação de esquemas, migrações e manipulação de bases de dados relacionais através de um query builder para Node.js.

---

## Resumo do Projeto

O projeto demonstra a aplicação de boas práticas no desenvolvimento Back-end, substituindo o SQL puro por uma abordagem programática e segura. A estrutura permite a gestão de ciclos de vida de base de dados, desde a criação de tabelas até à execução de consultas complexas (JOINs, agrupamentos e transações), garantindo escalabilidade e facilidade de manutenção.

### Tecnologias e Ferramentas

| Categoria | Tecnologias Utilizadas |
| :--- | :--- |
| **Runtime** | Node.js |
| **Query Builder** | Knex.js |
| **Bases de Dados** | SQLite / PostgreSQL / MySQL |
| **Linguagem** | JavaScript (ES6+) |

---

## Estrutura de Diretórios

A organização segue os padrões recomendados para projetos que envolvem infraestrutura de dados:

* **migrations/**: Histórico de alterações estruturais na base de dados (versionamento de tabelas).
* **seeds/**: Dados iniciais para popular o sistema durante o desenvolvimento ou testes.
* **knexfile.js**: Configurações de ambiente e conexão para diferentes bases de dados.
* **src/database/**: Lógica de inicialização e conexão com o banco de dados.

---

## Funcionalidades Principais

O projeto destaca a proficiência em arquitetura de sistemas e manipulação de dados:

> **Versionamento de Base de Dados**
> Utilização de Migrations para garantir que a estrutura da base de dados seja consistente em qualquer ambiente de desenvolvimento, facilitando o trabalho em equipa e o deploy contínuo.

---

## Instalação e Configuração

Para executar este projeto localmente e realizar os testes de base de dados:

1. Efetue o clone do repositório:
   ```bash
   git clone [https://github.com/samuel123d/knex.git](https://github.com/samuel123d/knex.git)
