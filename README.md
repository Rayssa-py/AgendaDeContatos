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
| **`v0.2.0`** | List + ArrayList | Permite **vários** contatos com tamanho dinâmico | **Versão Atual** |

---

## 📌 Versão Atual: `v0.2.0` — Coleções Dinâmicas

Nesta versão, a Agenda de Contatos evoluiu para utilizar a API de Coleções do Java (`List` e `ArrayList`), permitindo o armazenamento e gerenciamento dinâmico de contatos sem a necessidade de limitar previamente a capacidade máxima.

### 💡 Principais Conceitos Trabalhados

* 📦 **Interface `List` & Classe `ArrayList`:** Manipulação de coleções dinâmicas de dados
* 🏷️ **Generics (`<String>`):** Tipo seguro para garantir que a lista armazene apenas o tipo esperado
* 📈 **Redimensionamento Dinâmico:** Alocação automática de memória conforme novos contatos são inseridos
* 🛠️ **Métodos da API:**
  * `add()` — Inserção de novos elementos
  * `get()` — Acesso a um elemento específico pelo índice
  * `remove()` — Remoção simples de contatos
  * `size()` — Retorno da quantidade atual de elementos
  * `indexOf()` — Localização de elementos
* 🔁 **Iteração com `for-each`:** Leitura e varredura simplificada e mais legível da coleção
* ⚡ **Simplificação de Código:** Operações de busca, exclusão e reorganização automatizadas pela própria API

---

## 📜 Histórico de Versões

### 📍 `v0.1.0` — Arrays e Capacidade Fixa

Segunda versão da Agenda, introduzindo o gerenciamento de múltiplos registros via vetores.

* **Características Principais:**
  * Uso de arrays simples (`String[]`) para cada atributo (`nome`, `celular`, `email`)
  * Controle de capacidade máxima pré-definida
  * Manipulação de posições através de índices e estrutura `for`
  * Pesquisa sequencial para localizar contatos
  * Remoção de elementos com reorganização física do array (deslocamento dos itens subsequentes)

---

### 📍 `v0.0.0` — Programação Procedural Básica

Primeira versão da aplicação, focada nos fundamentos da linguagem Java.

* **Características Principais:**
  * Classe única (`Principal`) com todo o código dentro do método `main()`
  * Armazenamento temporário de apenas **um contato** (um novo cadastro substitui o anterior)
  * Variáveis simples: `nome`, `celular` e `email`

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

- [ ] **`v0.3.0+`** — Modularização, introdução de Classes e Objetos, Encapsulamento, Padrões DAO e MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
v0.0.0  -> Programação Procedural Básica (1 contato)
v0.1.0  -> Armazenamento com Arrays (Capacidade fixa)
v0.2.0  -> Armazenamento com List / ArrayList (Tamanho dinâmico)
