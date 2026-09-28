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
| **`v0.3.0`** | List + ArrayList | Adiciona a opção de **alteração** de contatos cadastrados | **Versão Atual** |

---

## 📌 Versão Atual: `v0.3.0` — Alteração de Contatos

Nesta versão, a Agenda de Contatos recebeu a implementação da funcionalidade de **alteração de contatos**, aprimorando o gerenciamento dos dados cadastrados.

### 💡 Principais Características e Conceitos

* ✏️ **Nova opção no menu:** Opção dedicada para **Alterar contato**
* 🔍 **Busca Prévia:** Localização do registro antes de permitir a modificação
* 🔄 **Atualização via `set()`:** Atualização dos dados nas coleções (`List` / `ArrayList`) utilizando o método `.set()`
* ♻️ **Reutilização de Lógica:** Reaproveitamento do fluxo de validação e busca para localização precisa do registro

---

## 📜 Histórico de Versões

### 📍 `v0.2.0` — Armazenamento Dinâmico com ArrayList

Terceira versão da Agenda, introduzindo a API de Coleções do Java.

* **Características Principais:**
  * Uso da API de Coleções (`List` e `ArrayList`)
  * Uso de Generics (`<String>`)
  * Alocação e redimensionamento dinâmico de memória
  * Métodos da API (`add`, `get`, `remove`, `size`, `indexOf`, etc.)
  * Iteração simplificada com `for-each`
  * Simplificação das operações de inserção, busca e remoção

---

### 📍 `v0.1.0` — Arrays e Capacidade Fixa

Segunda versão da Agenda, introduzindo o suporte a múltiplos contatos.

* **Características Principais:**
  * Uso de arrays simples (`String[]`) para cada atributo (`nome`, `celular`, `email`)
  * Controle de capacidade máxima pré-definida
  * Manipulação de posições através de índices e estrutura `for`
  * Busca sequencial nos arrays
  * Remoção de elementos com reorganização física do array (deslocamento dos itens)

---

### 📍 `v0.0.0` — Programação Procedural Básica

Primeira versão da aplicação, focada nos fundamentos da linguagem Java.

* **Características Principais:**
  * Classe única (`Principal`) com todo o código contido no método `main()`
  * Armazenamento temporário de apenas **um contato** (um novo cadastro substitui o anterior)
  * Variáveis simples: `nome`, `celular` e `email`

* **Recursos Utilizados:**
  * Menu interativo via console com `Scanner`
  * Estruturas condicionais (`if-else`, `switch-case`) e de repetição (`while`)

* **Funcionalidades:**
  * ➕ Adicionar contato
  * 📋 Listar contato
  * 🔍 Procurar contato
  * ❌ Excluir contato
  * 🚪 Sair

---

## 🗺️ Próximas Versões

- [ ] **`v0.4.0+`** — Modularização, introdução de Classes e Objetos, Encapsulamento, Padrões DAO e MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
v0.0.0  -> Programação Procedural Básica (1 contato)
v0.1.0  -> Armazenamento com Arrays (Capacidade fixa)
v0.2.0  -> Armazenamento com List / ArrayList (Tamanho dinâmico)
v0.3.0  -> Funcionalidade de Alterar Contato
