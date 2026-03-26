<div align="center">
  <a href="#-versão-em-português">🇧🇷 Ler em Português</a> | <a href="#-english-version">🇺🇸 Read in English</a>
</div>

---

## 🇧🇷 Versão em Português

 Sistema VIP Desktop: MVC, API REST, SQLite e POO

Este é um projeto **Full-Stack Desktop** construído nativamente em **Java**. O sistema evoluiu de um script simples para uma aplicação robusta utilizando a arquitetura **MVC (Model-View-Controller)** e o padrão **DAO (Data Access Object)**, demonstrando as melhores práticas de Engenharia de Software.

 Funcionalidades e Arquitetura
* **Arquitetura Limpa (MVC & DAO):** O código foi refatorado para separar responsabilidades. A interface visual (`View`) não se comunica diretamente com o banco de dados. Toda a persistência de dados foi isolada na classe `ConvidadoDAO`, tornando o sistema escalável e fácil de manter.
* **Programação Orientada a Objetos (POO):** Aplicação prática de conceitos avançados como **Herança** (classes estendendo atributos base) e **Polimorfismo** (sobrescrita de métodos com `@Override` para comportamentos específicos).
* **Interface Gráfica (GUI):** Construída com **Java Swing**, capturando eventos assíncronos (`ActionListener`) para uma experiência de usuário fluida.
* **Consumo de API RESTful:** Integração via `java.net.http.HttpClient` para requisições HTTP ao servidor ViaCEP, processando dados JSON para autocompletar endereços dinamicamente.
* **Banco de Dados Relacional (SQLite):** Persistência estruturada com JDBC. Uso de comandos DDL e DML com `PreparedStatement` para garantir integridade e prevenir ataques de SQL Injection.

 Tecnologias Utilizadas
* **Linguagem:** Java (JDK 11+)
* **Paradigmas:** POO, Arquitetura MVC, Padrão DAO
* **Front-end:** Java Swing & AWT
* **Integração:** `java.net.http`
* **Banco de Dados:** SQLite e `java.sql` (JDBC)

---
*Desenvolvido por Italo Rocha de Almeida Ferreira - Estudante de Engenharia de Software*

<br>

---

## 🇺🇸 English Version

 VIP Desktop System: MVC, REST API, SQLite & OOP

This is a **Full-Stack Desktop** project built natively in **Java**. The system evolved from a simple script into a robust application utilizing the **MVC (Model-View-Controller)** architecture and the **DAO (Data Access Object)** pattern, demonstrating software engineering best practices.

 Features and Architecture
* **Clean Architecture (MVC & DAO):** The codebase was refactored to separate concerns. The visual interface (`View`) does not communicate directly with the database. All data persistence was isolated in the `ConvidadoDAO` class, making the system scalable and highly maintainable.
* **Object-Oriented Programming (OOP):** Practical application of advanced concepts such as **Inheritance** (classes extending base attributes) and **Polymorphism** (method overriding with `@Override` for specific behaviors).
* **Graphical User Interface (GUI):** Built with **Java Swing**, capturing asynchronous events (`ActionListener`) for a seamless User Experience (UX).
* **RESTful API Consumption:** Integration via `java.net.http.HttpClient` for HTTP requests to the ViaCEP server, processing JSON data to dynamically autocomplete addresses.
* **Relational Database (SQLite):** Structured persistence using JDBC. Executes DDL and DML commands via `PreparedStatement` to ensure data integrity and prevent SQL Injection vulnerabilities.

 Technologies Used
* **Language:** Java (JDK 11+)
* **Paradigms:** OOP, MVC Architecture, DAO Pattern
* **Front-end:** Java Swing & AWT
* **Integration:** `java.net.http`
* **Database:** SQLite and `java.sql` (JDBC)

---
*Developed by Italo Rocha de Almeida Ferreira - Software Engineering Student*
