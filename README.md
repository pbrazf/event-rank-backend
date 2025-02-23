# event-rank-backend
Back-end desenvolvido em Node.js com Fastify para gerenciar o ranking de convidados de um evento. Cada participante recebe um link único, e a cada acesso, sua contagem é incrementada. A aplicação utiliza Redis para contagem de acessos e PostgreSQL para controle de inscritos, além de estar containerizada com Docker para execução e o deploy.
