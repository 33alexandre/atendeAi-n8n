# AtendeAi-n8n

![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![WAHA](https://img.shields.io/badge/WAHA-WhatsApp_API-green)
![Groq](https://img.shields.io/badge/Groq-AI-blue)
![Redis](https://img.shields.io/badge/Redis-Memory-red)
![Docker](https://img.shields.io/badge/Docker-Container-blue)


## Descrição

O projeto integra múltiplas tecnologias para construir um fluxo automatizado de atendimento via WhatsApp. As mensagens recebidas são processadas por um workflow no n8n, encaminhadas para um modelo de linguagem (Groq) e respondidas automaticamente, com suporte a memória de contexto utilizando Redis.



## Funcionalidades

* Recebimento de mensagens via WhatsApp
* Geração automática de respostas com IA
* Persistência de contexto de conversa com Redis
* Processamento de eventos via webhook
* Execução em ambiente containerizado com Docker


## Arquitetura

* WAHA recebe a mensagem do WhatsApp
* n8n processa o evento via webhook
* O modelo de IA (Groq) gera a resposta
* Redis armazena e recupera o histórico da conversa
* A resposta é enviada automaticamente ao usuário


## Tecnologias utilizadas

* n8n (automação de workflows)
* WAHA (API de integração com WhatsApp)
* Groq (modelo de linguagem)
* Redis (armazenamento de memória)
* Docker (containerização)


## Como utilizar

1. Importe o arquivo `atendeAi.json` no n8n
2. Configure as credenciais necessárias (WAHA, Redis, Groq)
3. Ajuste a URL do serviço WAHA conforme o ambiente
4. Execute o workflow


