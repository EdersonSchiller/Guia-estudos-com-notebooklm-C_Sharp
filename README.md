# 🚀 Roteiro de Estudos & Desenvolvimento System: C# Desktop Architecture

Este repositório contém um guia prático e teórico completo estruturado para o estudo e desenvolvimento de uma aplicação de cadastro desktop moderna em **C#** e **.NET**, abordando desde os conceitos fundamentais de Programação Orientada a Objetos (POO) até padrões de arquitetura corporativa e boas práticas de segurança.

---

## 📌 Visão Geral do Projeto

O objetivo principal deste roteiro é consolidar o aprendizado do ciclo de vida de uma aplicação desktop em C#. O projeto foca no isolamento de responsabilidades através de uma **Arquitetura em Camadas (Layered Architecture)**, garantindo a construção de um sistema escalável, seguro e de fácil manutenção.

---

## 🏗️ Arquitetura e Estrutura do Sistema

A aplicação é dividida modularmente nas seguintes camadas:

* **`Models` (Modelo de Dados):** Classes de domínio e POCOs (Plain Old CLR Objects) representativas das entidades do sistema.
* **`Data / DAL` (Acesso a Dados via ADO.NET):** Gerenciamento da persistência de dados utilizando a biblioteca nativa `ADO.NET` para controle granular de consultas e comandos SQL.
* **`UI` (Interface Gráfica em Windows Forms):** Formulários e componentes visuais para interação direta e fluida com o usuário.

---

## 🔑 Principais Tópicos & Tecnologias Abordadas

### 1. Programação Orientada a Objetos (POO)
- Aplicação prática dos 4 pilares: *Encapsulamento*, *Herança*, *Polimorfismo* e *Abstração*.
- Organização do domínio do problema em modelos coesos.

### 2. Acesso a Dados e Segurança (ADO.NET)
- Conexão e manipulação de Banco de Dados relacional.
- Uso de `SqlCommand`, `SqlDataReader` e conexões seguras.
- **Prevenção contra SQL Injection:** Implementação rigorosa de *Parameterized Queries* (consultas parametrizadas).

### 3. Programação Assíncrona (`async` / `await`)
- Execução de tarefas de I/O de banco de dados e APIs em background.
- Garantia de responsividade da interface gráfica (Windows Forms) sem travamentos durante requisições demoradas.

### 4. Integração com APIs Externas & Manipulação de Arquivos
- Consumo de serviços Web RESTful usando `HttpClient`.
- Leitura, gravação e processamento de arquivos locais (JSON, CSV, TXT) para importação/exportação de dados.

---

## 🧠 Objetivos de Aprendizado & Avaliação

Este material serve como base tanto para desenvolvimento prático quanto para preparação teórica/técnica, abordando:
- [x] Conceitos teóricos de arquitetura de software desktop.
- [x] Resolução de desafios práticos de codificação C#.
- [x] Boas práticas de tratamento de exceções e manipulação de dados.
- [x] Estratégias para avaliações teóricas e práticas de desenvolvimento.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C# (.NET)
- **Interface:** Windows Forms (WinForms)
- **Acesso a Dados:** ADO.NET / SQL Server (ou SQLite)
- **Protocolos & Formatos:** HTTP, REST, JSON

---

https://notebook.google.com/notebook/56e1b9d5-7257-4d24-a78d-36c47c1e35f3

