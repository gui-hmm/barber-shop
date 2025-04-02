<!--START_SECTION:header-->
<div align="center">
  <p align="center">
    <h1>barber-shop-api</h1>
  </p>
</div>
<!--END_SECTION:header-->

<p align="center">
  <a href="NIVEL"><img  src="https://img.shields.io/static/v1?label=Nivel&message=Basico&color=E94D5F&labelColor=202024" alt="Nivel"></a>
</p>

## 💻 Sobre o Projeto

Este projeto é uma API REST desenvolvida em **Java com Spring** para o agendamento de atendimentos em uma barbearia. Ele utiliza **JPA com Hibernate** para a persistência de dados no **PostgreSQL** e **Flyway** para versionamento do banco de dados.

## 📚 Pré-requisitos

- Java | Intermediário
- SQL | Intermediário
- Gradle | Básico
- Spring | Básico
- Docker | Básico (opcional)
- Docker Compose | Básico (opcional)

## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **Hibernate / JPA**
- **PostgreSQL**
- **Flyway**
- **Docker e Docker Compose** (opcional)

## 🎯 Funcionalidades

- Cadastro de clientes e agendamentos
- Versionamento de banco de dados com Flyway
- API REST seguindo boas práticas

## 🚀 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/gui-hmm/barber-shop-api.git

# Acesse a pasta do projeto
cd barber-shop-api

# Execute a aplicação (caso use Docker)
docker-compose up --build
