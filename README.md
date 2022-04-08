# Classroom Microservice

### Techs

1. NestJS
2. Apache Kafka Microservices
3. GraphQL
4. Apollo Federation
5. Prisma

### Execute DEV

```
npm run start:dev
```


### Dependencies

**Docker**

Execute o `docker-compose.yml` na raiz do projeto para subir as imagens necessárias para o funcionamento do projeto. Esse comando deve ser executado apenas uma vez em um dos projetos, visto que esse arquivo está em ambos os repositórios.

```
docker-compose up -d
```

**Projetos**

1. https://github.com/DeeSouza/Microservice-Project-Frontend-Web
2. https://github.com/DeeSouza/Microservice-Project-Purchases
3. https://github.com/DeeSouza/Microservice-Project-Gateway-Apollo-Federation

### Prisma Studio

```
npx prisma studio
```

### Prisma Migration

```
npx prisma migrate dev
```