# Modelo de Banco de Dados para E-commerce (EER)

Este repositório apresenta a modelagem de um banco de dados relacional, no formato EER (Entidade-Relacionamento Estendido), para um sistema de e-commerce.

## Visão Geral
O modelo foi desenvolvido para representar as principais operações de um e-commerce, abrangendo o cadastro de clientes, gestão de pedidos, produtos, controle de estoque, fornecedores, vendedores terceiros, formas de pagamento e entregas.

## Estrutura do Modelo
A modelagem contempla as seguintes entidades principais:

- Cliente (Pessoa Física e Pessoa Jurídica)
- Pedido
- Produto
- Estoque
- Fornecedor
- Vendedor Terceiro
- Forma de Pagamento
- Entrega

Para garantir a integridade dos dados, foram utilizadas tabelas associativas para representar relacionamentos muitos-para-muitos, como:
- Pedido x Produto
- Produto x Fornecedor
- Produto x Vendedor Terceiro

## Objetivo do Projeto
Demonstrar a aplicação de conceitos fundamentais de modelagem de banco de dados relacional, incluindo definição de entidades, relacionamentos, normalização e integridade referencial, em um cenário prático de e-commerce.

## Conteúdo do Repositório
- Diagrama EER do banco de dados em formato PNG
- Arquivo README com a descrição do projeto

## Contexto
Projeto desenvolvido como parte de atividades práticas da plataforma Digital Innovation One (DIO).
