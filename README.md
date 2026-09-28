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
| **`v1.0.0`** | List + ArrayList | **Modularização** das funcionalidades com métodos | **Versão Atual** |

---

## 📌 Versão Atual: `v1.0.0` — Modularização das Funcionalidades

Nesta versão, a Agenda de Contatos passou por um processo de **refatoração**, onde o código procedural contido na classe principal foi organizado e dividido em **métodos**, melhorando a legibilidade e a manutenção do sistema.

> 💡 **Nota:** A versão `v1.0.0` mantém todas as funcionalidades da `v0.3.0`, alterando principalmente a estrutura e organização interna do código.

### ⚙️ Principais Alterações
* 🧩 **Modularização:** Divisão da aplicação em rotinas reutilizáveis
* 🛠️ **Criação de Métodos Específicos:**
  * `adicionar()` — Inserção de novos dados
  * `listar()` — Exibição dos contatos cadastrados
  * `pesquisar()` — Busca sequencial de registros
  * `atualizar()` — Alteração dos dados existentes
  * `excluir()` — Remoção de contatos
* 🔀 **Simplificação do Menu:** O bloco `switch-case` no método `main()` passa apenas a delegar as chamadas aos métodos correspondentes
* 📤 **Passagem de Parâmetros:** Compartilhamento seguro das listas entre os métodos

### 💾 Armazenamento
Os dados permanecem em memória utilizando três listas paralelas do tipo `List<String>`:
* `nomes`
* `celulares`
* `e-mails`

### 💡 Conceitos Trabalhados
* Métodos, Parâmetros e Argumentos
* Retorno de funções e tipo `void`
* Escopo e tempo de vida de variáveis
* Modularização e Refatoração de Código

---

## 📜 Histórico de Versões

### 📍 `v0.3.0` — Alteração de Contatos
* Implementação da funcionalidade de **Alterar contato**
* Atualização dos dados nas coleções utilizando o método `.set()`
* Reutilização da lógica de validação e busca para localização precisa dos registros

### 📍 `v0.2.0` — Armazenamento Dinâmico com ArrayList
* Introdução da API de Coleções (`List` e `ArrayList`)
* Uso de Generics (`<String>`) e alocação dinâmica de memória
* Manipulação com métodos nativos (`add`, `get`, `remove`, `size`, `indexOf`)
* Iteração simplificada com `for-each`

### 📍 `v0.1.0` — Arrays e Capacidade Fixa
* Gerenciamento de múltiplos contatos via vetores simples (`String[]`)
* Controle de capacidade máxima pré-definida
* Manipulação manual de posições, índices e laço `for`
* Reorganização física do array na remoção de elementos

### 📍 `v0.0.0` — Programação Procedural Básica
* Aplicação em classe única (`Principal`) e todo o código no método `main()`
* Armazenamento temporário de apenas **um contato** via variáveis simples (`nome`, `celular`, `email`)
* Menu via console utilizando `Scanner`, `if-else`, `switch-case` e `while`

---

## 🗺️ Próximas Versões

- [ ] **`v1.1.0+` / `v2.0.0`** — Introdução da Programação Orientada a Objetos (Classes, Objetos, Atributos e Métodos), Encapsulamento, Padrões DAO e MVC, Interface Gráfica (Swing), JDBC e Banco de Dados.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
- V0 (Versões iniciais procedurais)
  - v0.0.0 -> Armazenamento simples (1 contato)
  - v0.1.0 -> Armazenamento com Arrays (Capacidade fixa)
  - v0.2.0 -> Armazenamento com List / ArrayList (Tamanho dinâmico)
  - v0.3.0 -> Edição de contatos

- V1 (Modularização do código)
  - v1.0.0 -> Organização do código procedural em Métodos
