<h1 align="center">Nest Fórum 📕</h1>

Fórum desenvolvido com o intuito de permitir que os usuários realizem seu registro para esclarecerem suas dúvidas referentes às suas perguntas de estudo.
Há a possibilidade tanto de professores quanto de alunos responderem às dúvidas.

Para a construção do fórum, foram empregadas estratégias como Clean Architecture e os Princípios do SOLID.
Utilizar esses conceitos facilitou significativamente a organização do projeto e proporcionou uma compreensão mais aprofundada de como uma arquitetura funciona.

## Tecnologias

- [NestJs](https://nestjs.com/)
- [Docker](https://www.docker.com/)
- [CloudFlareR2](https://developers.cloudflare.com/r2/)
- [Redis](https://redis.io/)

## Como rodar 
```bash

Requisitos
- Docker
- Pnpm
- Cloudflare R2
- WSL2


# Faça o clone do repo
  git clone git@github.com:matheusgmello/nest-forum-clean

# Configure as variáveis de ambiente
  configure de acordo com o env example

# Rode a imagem do docker
  Docker compose up -D

# Instale as dependências
  pnpm install

# Execute o projeto
  pnpm run start:dev
  
# Rodar as migrations 
  prisma migrate dev
```
## Testes E2E
- Should cache question details
- Should return cached question details on subsequent calls
- Should reset question details cache when saving the question
- Should send a notification when question best answer is chosen
- Should send a notification when answer is created

## Autor
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/matheusgmello/)](https://www.linkedin.com/in/matheusgmello/)
