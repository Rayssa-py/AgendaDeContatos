# 📇 Agenda de Contatos

> **Projeto Didático:** Desenvolvido em Java para acompanhar a evolução dos conceitos práticos da disciplina de **Programação Orientada a Objetos (POO)**.

---

## 🎯 Objetivo

Construir uma Agenda de Contatos completa, iniciando com uma solução procedural simples e evoluindo gradualmente para uma aplicação organizada com conceitos de Programação Orientada a Objetos, interface gráfica e persistência de dados.

---

## 📊 Evolução do Projeto

| Versão | Armazenamento / Recursos | Descrição | Status |
| :--- | :--- | :--- | :---: |
| **`v0.0.0`** | Variáveis simples | Permite armazenar apenas **um** contato em memória | Concluído |
| **`v0.1.0`** | Arrays | Permite **vários** contatos com capacidade fixa | Concluído |
| **`v0.2.0`** | List + ArrayList | Permite **vários** contatos com tamanho dinâmico | Concluído |
| **`v0.3.0`** | List + ArrayList | Adiciona a opção de **alteração** de contatos cadastrados | Concluído |
| **`v1.0.0`** | List + ArrayList | **Modularização** das funcionalidades em métodos | Concluído |
| **`v1.1.0`** | List + ArrayList | Separação de responsabilidades em arquivos (`Uteis` e `Agenda`) | Concluído |
| **`v1.1.1`** | List + ArrayList | **Hotfix:** Correção de bug no encerramento (`Sair`) | Concluído |
| **`v2.1.0`** | Arquivo TXT (`java.io`) | **Persistência de dados** em disco via `java.io` | **Versão Atual** |

---

## 📌 Versão Atual: `v2.1.0` — Persistência de Dados em Arquivo Texto (TXT)

Nesta versão, o sistema evolui para **salvar e recuperar dados em disco**. Os contatos cadastrados deixam de ser perdidos ao encerrar a aplicação e passam a ser mantidos em um arquivo texto (`.txt`).

### 💡 Principais Características e Conceitos

* 💾 **Persistência de Dados em Disco:** Integração com o pacote `java.io` para manipular arquivos locais.
* 📄 **Manipulação de Arquivos (`File`):** Verificação de existência e gerenciamento da estrutura de arquivo em disco.
* 📖 **Leitura Estruturada:** Utilização de `FileReader` e `BufferedReader` para leitura do arquivo texto linha a linha durante a inicialização.
* ✍️ **Escrita e Atualização:** Utilização de `FileWriter` e `PrintWriter` para gravação de contatos e sincronização do arquivo após operações de alteração ou exclusão.
* 🔄 **Carregamento e Sincronização Automática:** Leitura automática do arquivo no momento em que a aplicação é aberta e atualização contínua do arquivo texto a cada alteração no cadastro.
* 🛡️ **Tratamento de Exceções:** Gerenciamento de erros de entrada/saída (`IOException`) utilizando blocos `try-catch`.

---

## 📜 Histórico de Versões

### 📍 `v1.1.1` — Correção de Bug (Hotfix)
* Ajuste no fluxo de encerramento do sistema (opção **Sair** do menu)
* Garantia do fechamento correto dos recursos do `Scanner`

### 📍 `v1.1.0` — Modularização em Múltiplos Arquivos
* Divisão do código em arquivos e classes separadas (`Uteis`, `Agenda`, `Principal`)
* Separação clara da interface gráfica de console (menu) da lógica de negócios

### 📍 `v1.0.0` — Modularização com Métodos
* Refatoração do código procedural criando os métodos `adicionar()`, `listar()`, `pesquisar()`, `atualizar()` e `excluir()`
* Simplificação da estrutura do `switch-case` no método `main()`
* Passagem de parâmetros e escopo de variáveis

### 📍 `v0.3.0` — Atualização de Registros
* Implementação da funcionalidade de edição/alteração de contatos
* Uso do método `.set()` do `ArrayList`

### 📍 `v0.2.0` — Armazenamento Dinâmico com ArrayList
* Introdução da API de Coleções do Java (`List` e `ArrayList`)
* Uso de Generics (`<String>`) e iteração com `for-each`

### 📍 `v0.1.0` — Arrays e Capacidade Fixa
* Suporte a múltiplos contatos utilizando vetores (`String[]`) e controle manual de capacidade

### 📍 `v0.0.0` — Programação Procedural Básica
* Versão inicial em classe única (`Principal`), capaz de manter apenas **um contato** por vez

---

## 🗺️ Próximas Versões

- [ ] **`v3.0.0+`** — Introdução formal da Programação Orientada a Objetos (Criação da classe `Contato`, Atributos, Encapsulamento, Construtores, Getters e Setters)
- [ ] **Versões Futuras** — Padrões DAO e MVC, Interface Gráfica com Swing, Persistência em Banco de Dados Relacional via JDBC.

---

## 🏷️ Controle de Versões

As versões estáveis do projeto são identificadas por **tags Git**:

```text
- v0 (Protótipos procedurais em memória)
  - v0.0.0 -> Armazenamento simples (1 contato)
  - v0.1.0 -> Armazenamento com Arrays (Capacidade fixa)
  - v0.2.0 -> Armazenamento dinâmico com List / ArrayList
  - v0.3.0 -> Alteração de contatos cadastrados

- v1 (Refatoração, Modularização e Ajustes)
  - v1.0.0 -> Modularização procedural com métodos
  - v1.1.0 -> Divisão das responsabilidades em classes (Uteis e Agenda)
  - v1.1.1 -> Correção de bug no fluxo de saída

- v2 (Persistência em Arquivo)
  - v2.1.0 -> Persistência de dados em arquivo texto (.txt) via java.io
