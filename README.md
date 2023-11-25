# Projeto Desafio - Blindando Código DIO com C# e SQL Server Management

## Descrição

Este projeto é um desafio proposto pela Digital Innovation One (DIO) e consiste em desenvolver uma aplicação em C# que utiliza o SQL Server Management para criar um sistema de gerenciamento de produtos. O objetivo é praticar conceitos de programação segura e blindagem contra possíveis vulnerabilidades no código.

## Funcionalidades

- Cadastro de Produtos: Permite o cadastro seguro de novos produtos, incluindo informações como nome, descrição, preço e quantidade em estoque.

- Consulta de Produtos: Possibilita a consulta de produtos cadastrados, exibindo detalhes sobre cada item.

- Atualização de Produtos: Permite a atualização segura das informações dos produtos, garantindo a integridade dos dados.

- Remoção de Produtos: Permite a remoção segura de produtos do sistema, evitando operações indevidas.

## Tecnologias Utilizadas

- C#: Linguagem de programação orientada a objetos utilizada para desenvolver a lógica da aplicação.

- SQL Server Management: Sistema de gerenciamento de banco de dados utilizado para armazenar e recuperar informações sobre os produtos.

## Configuração

1. Clone o repositório para o seu ambiente local.
   ```bash
   git clone https://github.com/seu-usuario/nome-do-projeto.git
   ```

2. Abra o projeto em um ambiente de desenvolvimento integrado compatível com C#.

3. Certifique-se de ter um servidor SQL Server disponível. Atualize as configurações de conexão com o banco de dados no código, se necessário.

4. Execute o script SQL fornecido para criar a estrutura da tabela de produtos no banco de dados.

5. Execute a aplicação e teste as funcionalidades de cadastro, consulta, atualização e remoção de produtos.

## Script SQL

```sql
-- Script para criação da tabela de produtos
CREATE TABLE Produtos (
    Id INT PRIMARY KEY IDENTITY(1,1),
    Nome NVARCHAR(100) NOT NULL,
    Descricao NVARCHAR(255),
    Preco DECIMAL(18,2) NOT NULL,
    QuantidadeEstoque INT NOT NULL
);
```

## Autor

[Giancarlo com Digital Innovation One - DIO]
