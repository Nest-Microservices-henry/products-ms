# Orders MicroService

```
docker compose up -d
```

## Development steps

1. Clone the project
2. Create a `.env` file based on the `.env.template` file
3. run prisma migration `npx prisma migrate dev`
4. run nats : docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
5. Start the project with `npm run start:dev`
