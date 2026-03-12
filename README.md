# QA API Testing - Postman

Projeto de testes de API utilizando Postman.

## Objetivo

Validar endpoints de uma API simulando cenários reais de testes.

## Ferramentas

- Postman
- Newman
- GitHub

## Endpoints testados

- Login
- Listagem de produtos
- Criar usuário
- Buscar pedido

## Tipos de validação

- Status code
- Response time
- Estrutura JSON
- Validação de campos obrigatórios

## Executar testes via CLI

Instalar Newman:

npm install -g newman

Executar:

newman run collections/ecommerce-api.postman_collection.json

