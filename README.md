# 📇 Agenda de Contatos

> **Projeto Didático:** Desenvolvido em Java para acompanhar a evolução dos conceitos práticos da disciplina de **Programação Orientada a Objetos (POO)**.

---

## 🎯 Objetivo

Construir uma Agenda de Contatos completa, iniciando com uma solução procedural simples e evoluindo gradualmente para uma aplicação organizada com conceitos de Programação Orientada a Objetos, interface gráfica e persistência de dados.

---

## 📊 Evolução do Projeto

| Versão | Armazenamento | Descrição | Status |
| :--- | :--- | :--- | :---: |
| **`v0.0.0`** | Variáveis simples | Permite armazenar apenas **um** contato | Concluído |
| **`v0.1.0`** | Arrays | Permite **vários** contatos com capacidade fixa | Concluído |
| **`v0.2.0`** | List + ArrayList | Permite **vários** contatos com tamanho dinâmico | Concluído |
| **`v0.3.0`** | List + ArrayList | Adiciona a opção de **alteração** de contatos | Concluído |
| **`v1.0.0`** | List + ArrayList | **Modularização** das funcionalidades com métodos | Concluído |
| **`v1.1.0`** | List + ArrayList | Modularização em arquivos separados (`Uteis` e `Agenda`) | Concluído |
| **`v1.1.1`** | List + ArrayList | Arquivos separados e **correção de bug** no fluxo de saída | **Versão Atual** |

---

## 📌 Versão Atual: `v1.1.1` — Modularização e Correção de Bug

Nesta versão, a Agenda de Contatos consolidou a separação em múltiplos arquivos/classes (`Uteis` e `Agenda`) e recebeu uma **correção de bug** no fluxo de encerramento da aplicação.

### 💡 Principais Destaques e Correções

* 🐛 **Correção de Bug (Fix):** Ajuste na lógica de controle do laço do menu para garantir que a opção **Sair** encerre a aplicação corretamente sem erros de execução.
* 📁 **Separação de Responsabilidades (`Uteis` e `Agenda`):**
  * **`Uteis`:** Centraliza rotinas auxiliares de leitura via `Scanner` e formatação de saídas.
  * **`Agenda`:** Regras de negócio e operações diretas sobre os dados (`adicionar`, `listar`, `pesquisar`, `atualizar`, `excluir`).
  * **`Principal`:** Responsável estritamente pelo ponto de entrada (`main`) e controle de navegação do menu.

---

## 📜 Histórico de Versões

### 📍 `v1.1.0` — Modularização em Arquivos Separados
* Organização do código em múltiplos arquivos para melhorar a legibilidade
* Isolamento de funções genéricas de entrada/saída no módulo `Uteis`
* Isolamento das regras da agenda no módulo `Agenda`

### 📍 `v1.0.0` — Modularização das Funcionalidades
* Organização do código procedural através de métodos na mesma classe
* Criação dos métodos `adicionar()`, `listar()`, `pesquisar()`, `atualizar()` e `excluir()`
* Simplificação da estrutura `switch-case` e passagem de parâmetros

### 📍 `v0.3.0` — Alteração de Contatos
* Funcionalidade de **Alterar contato** utilizando o método `.set()` do `ArrayList`

### 📍 `v0.2.0` — Armazenamento Dinâmico com ArrayList
* Transição para a API de Coleções (`List` e `ArrayList`) com `Generics` (`<String>`)

### 📍 `v0.1.0` — Arrays e Capacidade Fixa
* Manipulação de múltiplos registros através de vetores simples (`String[]`)

### 📍 `v0.0.0` — Programação Procedural Básica
* Primeira versão com classe única (`Principal`), armazenando apenas **um contato** por vez

---

## 🗺️ Próximas Versões

- [ ] **`v2.0.0+`** — Introdução da Programação Orientada a Objetos (Classes, Objetos, Atributos e Métodos), Encapsulamento, Padrões DAO e MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
- V0 (Versões procedurais iniciais)
  - v0.0.0 -> Armazenamento simples (1 contato)
  - v0.1.0 -> Armazenamento com Arrays (Capacidade fixa)
  - v0.2.0 -> Armazenamento com List / ArrayList (Tamanho dinâmico)
  - v0.3.0 -> Edição de contatos

- V1 (Modularização, Organização e Refatoração)
  - v1.0.0 -> Organização procedural em métodos
  - v1.1.0 -> Divisão em arquivos separados (Uteis e Agenda)
  - v1.1.1 -> Correção de bug na opção SAIR
