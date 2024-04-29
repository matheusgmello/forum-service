# Example of a forum with DDD architecture and SSE

Forum developed to study Domain-Driven Design (DDD) architecture and communication technology like Server-Sent Events (SSE), where students and teachers can ask questions and answer doubts.

# Configs 

### Requirements

- [Node](https://nodejs.org/en/docs)
- [Docker](https://www.docker.com/)
- [CloudFlareR2](https://developers.cloudflare.com/r2/)

**Clone the project and access the folder**

``` bash
git clone git@github.com:matheusgmello/forum-ddd-sse.git && cd forum-ddd-sse
```
- Install dependencies(`pnpm run dev`)
- Configure Docker (`docker compose up -d`)
- Configure environment variables in (`.env`)
- Configure the database(`prisma migrate dev`)
- Run and test the application(`pnpm run start:dev`)

## Testes E2E

- `Should cache question details`
- `Should return cached question details in subsequent calls`.
- `Should reset the question details cache upon saving the question`.
- `Should send a notification when the best answer for the question is chosen`.
- `Should send a notification when an answer is created`.

## Fórum (DDD)

- Forum Experts
  - Conversations

- Ubiquitous Language

- User
  - Member
  - Moderator
  - Administrator
  - Visitor

- Topics

- Posts

- Forum Events

- Subforums (Bounded Contexts)

- Sticky Topics

- Features

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
