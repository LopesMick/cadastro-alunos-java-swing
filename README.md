# 🎓 Cadastro de Alunos - Java Swing

Este projeto é uma aplicação simples de cadastro de alunos desenvolvida em **Java** utilizando a biblioteca **Swing** para interface gráfica e **JDBC** para conexão com um banco de dados **MySQL**.

## 📋 Funcionalidades

- Cadastro de alunos com:
  - Nome
  - CPF
  - E-mail
- Armazenamento dos dados no banco de dados MySQL
- Interface gráfica simples e funcional usando `JFrame`
- Conexão com banco via `ConnectionFactory`

## 🛠 Tecnologias utilizadas

- **Java 8+**
- **Swing (javax.swing)**
- **JDBC**
- **MySQL**
- **Eclipse IDE**

## 🧩 Estrutura do Projeto

# cadastro-alunos-java-swing
Projeto Java com Swing e JDBC para cadastro de alunos



## 🧪 Banco de Dados

Crie o banco de dados com o seguinte comando:

```sql
CREATE DATABASE sistema_academico;
USE sistema_academico;

CREATE TABLE aluno (
  id INT AUTO_INCREMENT PRIMARY KEY,
  nome VARCHAR(100),
  cpf VARCHAR(20),
  email VARCHAR(100)
);

Como executar
Certifique-se de que o MySQL está rodando.

Atualize os dados de conexão na classe ConnectionFactory.java com seu usuário e senha do MySQL.

Execute a classe MenuPrincipal.java.

A interface será aberta e você poderá cadastrar alunos.

✅ Requisitos
Java instalado

MySQL rodando localmente

Driver JDBC (mysql-connector-java) adicionado ao projeto

📌 Observações
Este projeto é utilizado para fins educacionais e demonstra os princípios básicos de uma aplicação Java com GUI e persistência em banco de dados.
