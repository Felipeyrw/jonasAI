# 🏡 Jonas

**Jonas** é um assistente de IA para imobiliárias que automatiza o atendimento via WhatsApp. Desenvolvido para oferecer uma experiência natural ao cliente, o sistema compreende o contexto das conversas, consulta uma base de conhecimento utilizando RAG (Retrieval-Augmented Generation) e auxilia clientes na busca pelo imóvel ideal.

## ✨ Funcionalidades

- Atendimento automatizado pelo WhatsApp
- Conversas naturais utilizando IA
- Memória de contexto durante a conversa
- Concatenação de mensagens consecutivas do usuário antes da geração da resposta
- Simulação de digitação para tornar a interação mais humana
- Pesquisa inteligente de imóveis através de RAG
- Busca de imóveis por:
  - Cidade
  - Bairro
  - Faixa de preço
  - Tipo de imóvel
  - Quantidade de quartos
- Qualificação automática de leads
- Coleta de informações do cliente
- Histórico de conversas
- Automações desenvolvidas em n8n
- Integração com banco de dados
- Integração com WhatsApp via Evolution API

---

## 🧠 Como funciona

1. O cliente envia uma mensagem pelo WhatsApp.
2. O sistema aguarda alguns segundos para agrupar mensagens enviadas em sequência.
3. A IA interpreta a intenção do usuário.
4. Caso necessário, consulta a base de conhecimento utilizando RAG.
5. A resposta é gerada considerando todo o contexto da conversa.
6. Antes do envio, o sistema simula o indicador de "digitando..." para tornar a interação mais natural.

---

## 🏗️ Tecnologias

- n8n
- OpenAI
- Evolution API
- PostgreSQL
- Docker
- RAG (Retrieval-Augmented Generation)

---

## 📂 Arquitetura

```
WhatsApp
      │
Evolution API
      │
     n8n
      │
 ┌────┴────┐
 │         │
IA      Banco de Dados
 │         │
 └────┬────┘
      │
     RAG
      │
Resposta ao cliente
```

---

## 🎯 Objetivos

- Reduzir o tempo de resposta.
- Automatizar o atendimento inicial.
- Melhorar a qualificação de leads.
- Facilitar a busca por imóveis.
- Oferecer um atendimento humanizado.

---

## 🚀 Possíveis melhorias

- Agendamento automático de visitas
- Integração com CRM
- Integração com Google Calendar

---

## 📄 Licença

Este projeto foi desenvolvido para fins de demonstração e portfólio.
