# Monetus

Automação de gestão de assinaturas e mensagens via WhatsApp, construída com n8n integrando Supabase e OpenAI.

## Funcionalidades

- Rotas de mensagens e eventos de assinatura via webhooks
- Integração com WhatsApp (Evolution API)
- Processamento de linguagem natural com OpenAI
- Persistência de dados com Supabase
- Gestão automatizada de assinaturas

## Stack

- **n8n** — orquestração de fluxos
- **Supabase** — banco de dados e autenticação
- **OpenAI API** — processamento de mensagens
- **Evolution API** — integração WhatsApp

## Como usar

1. Importe [`MonetusFinal.json`](MonetusFinal.json) em uma instância de teste do n8n
2. Reconecte as credenciais: Supabase, OpenAI e Evolution API
3. Configure Header Auth nos dois webhooks
4. Configure o remetente de eventos para usar os mesmos cabeçalhos

> A versão publicada está inativa — links de assinatura e nomes de instância foram substituídos por marcadores. Use dados fictícios para teste.

## Referências

- [Importação de fluxos no n8n](https://docs.n8n.io/build/manage-workflows/export-and-import)
- [Configuração de webhooks](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.webhook)

## Autor

**João Vitor Cassiano** — [@joaocnds](https://github.com/joaocnds)
