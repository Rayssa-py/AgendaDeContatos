# 📇 Agenda de Contatos

> **Projeto Didático:** Desenvolvido em Java para acompanhar a evolução dos conceitos práticos da disciplina de **Programação Orientada a Objetos (POO)**.

---

## 🎯 Objetivo

Construir uma Agenda de Contatos completa, iniciando com uma solução procedural simples e evoluindo gradualmente para uma aplicação organizada com conceitos de Programação Orientada a Objetos, interface gráfica e persistência de dados.

---

## 📊 Evolução do Projeto

| Versão | Armazenamento | Descrição |
| :--- | :--- | :--- |
| **`v0.0.0`** | Variáveis simples | Permite armazenar apenas **um** contato |
| **`v0.1.0`** | Arrays | Permite **vários** contatos com capacidade fixa *(Atual)* |
| **`v0.2.0`** | List + ArrayList | Permitirá vários contatos com tamanho dinâmico |

---

## 📌 Versão Atual: `v0.1.0`

Nesta versão, a Agenda de Contatos evoluiu para utilizar **arrays**, possibilitando o armazenamento e o gerenciamento de múltiplos contatos no sistema.

### 💡 Principais Conceitos Trabalhados
* 🧮 **Arrays & Índices:** Manipulação e acesso a posições de memória
* 🔁 **Estrutura `for`:** Varredura e iteração sobre os contatos
* 📏 **Capacidade Fixa:** Controle da quantidade de elementos vs. limite máximo do vetor
* 🔍 **Pesquisa:** Busca estruturada de contatos cadastrados
* 🔄 **Exclusão e Reorganização:** Remoção de elementos mantendo a integridade dos dados no array

---

## 📜 Histórico de Versões

### 📍 `v0.0.0` — Programação Procedural Básica

Primeira versão da aplicação, focada nos fundamentos da linguagem Java.

* **Características Principais:**
  * Classe única (`Principal`) com todo o código contido no método `main()`
  * Armazenamento temporário de apenas **um contato** por variáveis simples (`nome`, `celular`, `email`)
  * Um novo cadastro substitui o contato armazenado anteriormente

* **Recursos Utilizados:**
  * Menu interativo via console
  * Entrada de dados via `Scanner`
  * Estruturas condicionais (`if-else`, `switch-case`) e de repetição (`while`)

* **Funcionalidades:**
  * ➕ Adicionar contato
  * 📋 Listar contato
  * 🔍 Procurar contato
  * ❌ Excluir contato
  * 🚪 Sair

---

## 🗺️ Próximas Versões

- [ ] **`v0.2.0`** — Armazenamento dinâmico com `List` e `ArrayList`
- [ ] **Versões Posteriores** — Modularização, Classes, Encapsulamento, DAO, MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
v0.0.0  -> Programação Procedural Básica (1 contato)
v0.1.0  -> Armazenamento com Arrays (Vários contatos, capacidade fixa)
v0.2.0  -> Armazenamento com List / ArrayList (Tamanho dinâmico)
