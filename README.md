# Admin Delta Customer Portal

## Run the frontend

From `client`, copy `.env.example` to `.env`, then run:

```sh
docker compose up --build
```

By default this starts the development frontend at `http://localhost:5174`.
Set `ENVIRONMENT=production` in `client/.env` to start only the production
frontend at `http://localhost:8081`. Use `ENVIRONMENT=development` for
development.