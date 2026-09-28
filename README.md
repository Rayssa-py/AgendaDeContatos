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
| **`v1.0.0`** | List + ArrayList | Modularização das funcionalidades com métodos | Concluído |
| **`v1.1.0`** | List + ArrayList | Modularização em arquivos separados (`Uteis` e `Agenda`) | **Versão Atual** |

---

## 📌 Versão Atual: `v1.1.0` — Modularização em Arquivos Separados

Nesta versão, a Agenda de Contatos passou por uma nova etapa de organização estrutural: as rotinas e funções foram divididas em arquivos/classes distintas (`Uteis` e `Agenda`), promovendo a **separação de responsabilidades**.

### 💡 Principais Alterações e Conceitos

* 📁 **Divisão em Arquivos:** Organização do código em múltiplos arquivos para facilitar a leitura e a manutenção
* 🛠️ **Módulo `Uteis`:** Centralização de rotinas auxiliares (ex: entrada de dados, exibições genéricas e validações)
* 📖 **Módulo `Agenda`:** Centralização das regras de negócio e manipulação dos dados dos contatos (`adicionar`, `listar`, `pesquisar`, `atualizar`, `excluir`)
* 🚀 **Classe `Principal`:** Responsável apenas pelo ponto de entrada da aplicação (`main`) e inicialização do menu
* 📦 **Encapsulamento Inicial:** Início do isolamento de funções por domínio/responsabilidade

---

## 📜 Histórico de Versões

### 📍 `v1.0.0` — Modularização das Funcionalidades
* Organização do código procedural através da criação de métodos
* Implementação dos métodos `adicionar()`, `listar()`, `pesquisar()`, `atualizar()` e `excluir()`
* Simplificação da estrutura `switch-case` e uso de parâmetros para compartilhamento de dados

### 📍 `v0.3.0` — Alteração de Contatos
* Implementação da funcionalidade de **Alterar contato**
* Atualização de registros utilizando o método `.set()` do `ArrayList`

### 📍 `v0.2.0` — Armazenamento Dinâmico com ArrayList
* Introdução da API de Coleções (`List` e `ArrayList`)
* Uso de Generics (`<String>`) e manipulação com métodos nativos da API

### 📍 `v0.1.0` — Arrays e Capacidade Fixa
* Gerenciamento de múltiplos contatos via vetores simples (`String[]`)
* Controle de capacidade pré-definida e reorganização física de elementos na remoção

### 📍 `v0.0.0` — Programação Procedural Básica
* Estrutura básica em classe única (`Principal`)
* Armazenamento temporário de apenas **um contato** via variáveis simples

---

## 🗺️ Próximas Versões

- [ ] **`v2.0.0+`** — Introdução da Programação Orientada a Objetos (Classes, Objetos, Atributos e Métodos), Encapsulamento, Padrões DAO e MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
- V0 (Versões iniciais procedurais)
  - v0.0.0 -> Armazenamento simples (1 contato)
  - v0.1.0 -> Armazenamento com Arrays (Capacidade fixa)
  - v0.2.0 -> Armazenamento com List / ArrayList (Tamanho dinâmico)
  - v0.3.0 -> Edição de contatos

- V1 (Modularização e Organização)
  - v1.0.0 -> Organização procedural em métodos
  - v1.1.0 -> Divisão das funcionalidades em arquivos separados (Uteis e Agenda)
