# Sistema de Aluno Online

Sistema de gestão acadêmica desenvolvido em **Java** com **Spring Framework**. É possível gerenciar alunos, professores, disciplinas e matrículas. Desenvolvido com arquitetura RESTful, integração com **Swagger** para documentação, e **PostgreSQL** como banco de dados.

---

## Funcionalidades

### Alunos
- **CRUD completo** (criação, leitura, atualização e exclusão).
- Adicionar notas aos alunos.
- Calcular média de notas.
- Exibir status de aprovação/reprovação.
- Permitir trancamento de matrícula.

### Professores
- **CRUD completo**.
- Associar um professor a várias disciplinas.

### Disciplinas
- Criar disciplinas.
- Associar alunos e professores.

### Matrículas
- Vincular um aluno a várias disciplinas.
- Gerenciar trancamento de matrícula.

---

## Tecnologias Utilizadas

- **Java** (Spring Framework)
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL** (banco de dados relacional)
- **Swagger** (documentação da API)
- **Maven** (gerenciador de dependências)

---

## Arquitetura

O projeto segue os princípios da arquitetura RESTful:
- **Controllers**: Camada responsável por expor endpoints da API.
- **Services**: Camada de lógica de negócios.
- **Repositories**: Camada de acesso ao banco de dados.
- **Models**: Representações das entidades do sistema.

---

## Pré-requisitos

- **Java 11 ou superior** instalado.
- **PostgreSQL** configurado e rodando.
- **Maven** para gerenciar dependências.
