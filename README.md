# Netflix Catalog Manager - Azure

Projeto desenvolvido utilizando Microsoft Azure com arquitetura serverless, simulando um gerenciador de catálogo de filmes e séries.

## Objetivo

Desenvolver uma aplicação em nuvem utilizando Azure Functions integradas com serviços de armazenamento e banco de dados.

## Serviços Utilizados

- Azure Functions
- Azure Storage Account
- Azure Cosmos DB
- API REST

## Funcionalidades

1. Upload de arquivos para o Storage Account.
2. Inserção de registros no CosmosDB.
3. Listagem de registros armazenados.
4. Filtro de registros por parâmetro (ex: gênero).

## Exemplo de Registro

{
  "id": "1",
  "titulo": "Breaking Bad",
  "genero": "Drama",
  "ano": 2008
}

## Conclusão

O projeto demonstra a aplicação de conceitos de Cloud Computing utilizando arquitetura serverless na Azure, integrando funções HTTP com banco NoSQL e armazenamento em nuvem.
