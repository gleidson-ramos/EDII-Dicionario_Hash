# 📘 Sistema de Perfis Facebook em Python
Projeto de um sistema simples de gerenciamento de perfis inspirado em uma rede social, desenvolvido em ``Python``.
O programa permite criar usuários, adicionar amigos, buscar perfis, excluir usuários e visualizar os perfis cadastrados por meio de um menu interativo no terminal.

## 🚀 Funcionalidades
O sistema possui as seguintes funcionalidades:

### 👤 Criar Perfil
- Cadastra um novo usuário.
- Armazena nome, idade e cidade.
- Cria uma lista de amigos para o usuário.

### 🤝 Adicionar Amigos
- Permite adicionar dois usuários como amigos.
- A amizade é registrada para os dois usuários.

### 🔎 Buscar Perfil
- Pesquisa um usuário pelo nome.
- Exibe idade, cidade e lista de amigos.

### 🗑️ Excluir Perfil
- Remove um usuário do sistema.
- Remove também esse usuário da lista de amigos dos demais perfis.

### 📋 Exibir Usuários
- Lista todos os usuários cadastrados em ordem alfabética.

### 🗂️ Exibir Facebook Completo
- Mostra todos os usuários e suas respectivas informações.

### 🚪 Sair
- Encerra a execução do programa.

## 📂 Estrutura dos dados

Os usuários são armazenados em um ``dicionário`` chamado facebook. Cada usuário possui três informações principais:
```bash
facebook = { "João": { "idade": 25, "cidade": "Salvador", "amigos": ["Maria", "Pedro"]} }
```
A estrutura pode ser representada da seguinte maneira:
```bash
facebook
 └── nome do usuário
      ├── idade
      ├── cidade
      └── amigos
           ├── amigo 1
           ├── amigo 2
           └── ...
```

## 📄 Sobre o Projeto
Projeto desenvolvido para a disciplina de Estrutura de Dados II (EDII), utilizando a estrutura de dados para representar uma rede social.