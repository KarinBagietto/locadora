# 🎬 Locadora de Filmes

Bem-vindo(a) ao projeto **Locadora de Filmes**, um sistema simples, mas cheio de funcionalidades, desenvolvido em **Python** para rodar no terminal.  
A proposta é recriar a experiência de uma locadora clássica, onde é possível cadastrar clientes e filmes, realizar e gerenciar aluguéis, além de manter tudo salvo em arquivos para consultas futuras.  

---

## ✨ O que você pode fazer
- 👤 **Cadastrar clientes** com verificação de CPF duplicado  
- 🎞️ **Cadastrar filmes** com título, gênero, ano e código  
- 📋 **Consultar a lista de clientes** já cadastrados  
- 🍿 **Visualizar filmes disponíveis** para aluguel  
- 🎟️ **Alugar filmes** para clientes  
- 🔄 **Devolver filmes** alugados  
- 🔍 **Pesquisar filmes** por nome ou gênero  
- 🗂️ **Ordenar a lista de filmes** por título ou ano  

---

## 🏗️ Estrutura do sistema
O sistema foi construído com **Programação Orientada a Objetos**, utilizando três classes principais:

- **Filme** → Representa cada filme com título, gênero, ano, código e status de disponibilidade  
- **Cliente** → Representa o cliente com nome e CPF  
- **Locadora** → Gerencia a lista de clientes, filmes e operações de aluguel e devolução  

Os dados são salvos em **arquivos CSV** (`filmes.csv`, `clientes.csv`, `emprestimos.csv`), garantindo que nada seja perdido ao encerrar o programa.  

---

🛠️ Tecnologias

Python 3

CSV para persistência dos dados

VS Code (editor recomendado)

