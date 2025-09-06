# AppRecycleView

Um aplicativo Android simples que demonstra o cadastro de usuários e a exibição da lista de usuários cadastrados utilizando `RecyclerView`.

## Descrição

Este projeto é um aplicativo Android básico desenvolvido em Kotlin. Foi criado como um Trabalho Prático (TP) para a disciplina de Programação para Dispositivos Móveis. O aplicativo permite que o usuário cadastre nome, e-mail e telefone. Em seguida, os usuários cadastrados são exibidos em uma lista em uma tela separada, fazendo uso do componente `RecyclerView` para uma exibição eficiente da lista.

## Funcionalidades

* **Tela de Cadastro:** Permite que novos usuários sejam cadastrados com nome, e-mail e telefone.
* **Lista de Usuários:** Exibe os usuários cadastrados em uma lista rolável usando `RecyclerView`.
* **Adapter Personalizado:** Utiliza um `UsuarioAdpter` para vincular os dados da lista de usuários aos itens da `RecyclerView`.
* **Modelo de Dados e DAO:** Estrutura simples com um modelo `Usuario` e um `UsuarioDao` para gerenciar os dados em memória.

## Tecnologias Utilizadas

* **Linguagem:** Kotlin
* **UI:** Android XML com ConstraintLayout
* **Componentes:** RecyclerView, FloatingActionButton
* **Build:** Gradle

