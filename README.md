# Nest Fórum 

Fórum desenvolvido com o intuito de permitir que os usuários realizem registros para esclarecerem suas dúvidas referentes às suas perguntas de estudo. Tanto professores quanto alunos têm a possibilidade de responder às dúvidas.

# Configurações 

### Requisitos

- [Node](https://nodejs.org/en/docs)
- [Docker](https://www.docker.com/)
- [CloudFlareR2](https://developers.cloudflare.com/r2/)

**Clone o projeto e acesse a pasta**

``` bash
git clone git@github.com:matheusgmello/nest-forum-clean.git && cd nest-forum-clean
```
- Instale as dependências(`pnpm run dev`)
- Configure o Docker(`docker compose up -d`)
- Configure as Variáveis de ambiente no (`.env`)
- Configure o banco de dados(`prisma migrate dev`)
- Rode e teste a aplicação(`pnpm run start:dev`)

## Testes E2E
- `Deve armazenar em cache os detalhes da pergunta.`
- `Deve retornar os detalhes da pergunta em cache em chamadas subsequentes.`
- `Deve redefinir o cache dos detalhes da pergunta ao salvar a pergunta.`
- `Deve enviar uma notificação quando a melhor resposta da pergunta for escolhida.`
- `Deve enviar uma notificação quando uma resposta for criada.`

## Tecnologias

- [NestJs](https://nestjs.com/)
- [Docker](https://www.docker.com/)
- [CloudFlareR2](https://developers.cloudflare.com/r2/)
- [Redis](https://redis.io/)

<!--START_SECTION:footer-->
<br />

## 🔗 Connect with me
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matheusgmello)
[![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://www.reddit.com/user/math7zw)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/matheusgmello/)

<!--END_SECTION:footer-->