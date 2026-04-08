# AtendeAi-n8n

![n8n](https://img.shields.io/badge/n8n-Automation-red)
![WAHA](https://img.shields.io/badge/WAHA-WhatsApp_API-green)
![Groq](https://img.shields.io/badge/Groq-AI-black)
![Redis](https://img.shields.io/badge/Redis-Memory-red)
![Docker](https://img.shields.io/badge/Docker-Container-blue)

## Descrição

Automação de WhatsApp com IA que recebe mensagens, gera respostas automaticamente e mantém o contexto da conversa. O fluxo é orquestrado no n8n, com integração ao WAHA para comunicação, Groq para geração de respostas e Redis para memória persistente.

## Funcionalidades

* Recebimento e resposta automática de mensagens
* Geração de respostas com inteligência artificial
* Memória de conversa com Redis
* Processamento via webhook no n8n

## Arquitetura

* WAHA recebe a mensagem do usuário
* n8n processa o fluxo
* Groq gera a resposta
* Redis mantém o contexto
* A resposta é enviada automaticamente

## Tecnologias

* n8n
* WAHA
* Groq
* Redis
* Docker

## Como usar

1. Importe o arquivo `atendeAi.json` no n8n
2. Configure WAHA, Redis e Groq
3. Execute o workflow
