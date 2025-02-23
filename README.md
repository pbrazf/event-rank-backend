# **Event Rank**

Event Rank é uma API desenvolvida com Node.js e Fastify para gerenciar o ranking de convidados de um evento. Cada participante recebe um link único, e a cada acesso, sua contagem é incrementada. Este projeto foi realizado como parte do NLW Connect da Rocketseat.

---

## O que é o Event Rank?
O Event Rank permite acompanhar e contabilizar os acessos dos convidados de um evento por meio de links personalizados. A aplicação usa Redis para a contagem de acessos em tempo real e PostgreSQL para armazenar os dados dos participantes.

---

## Principais Funcionalidades
Geração de links personalizados: Cada participante recebe um link único para compartilhamento.
Contagem de acessos em tempo real: Cada clique em um link incrementa a contagem no Redis.
Armazenamento de participantes: Controle de inscritos utilizando PostgreSQL.
Documentação com Swagger: API documentada e acessível para testes interativos.
Containerização com Docker: Facilidade no deploy e execução do projeto.

---

## Tecnologias Utilizadas
Node.js + Fastify – Backend leve e performático
Redis – Contagem rápida e eficiente dos acessos
PostgreSQL + Drizzle ORM – Armazenamento e gerenciamento dos inscritos
TypeScript – Código mais seguro e tipado
Docker – Padronização do ambiente e facilidade no deploy
Swagger – Documentação interativa da API

---

## Objetivos
Este projeto foi uma experiência essencial para aprofundar conhecimentos em:

1. Desenvolvimento de APIs performáticas com Fastify
2. Integração com Redis e PostgreSQL
3. Uso de Docker para facilitar a execução e o deploy
4. Validação de dados com Zod
5. Estruturação e boas práticas no desenvolvimento back-end

---

## Como Executar Localmente?
Caso queira testar ou contribuir, siga os passos abaixo:
```
bash
# Clone o repositório
git clone git@github.com:pbrazf/event-rank.git

# Instale as dependências
npm install

# Inicie os containers Docker (Redis e PostgreSQL)
docker-compose up -d

# Inicie a aplicação
npm run dev
```

---

Agora a API estará rodando e pronta para receber requisições! 🚀
