# Shouthfitness — Keepalive

Repo dedicado (público, para minutos ilimitados de GitHub Actions) que mantiene
despierto el backend de Shouthfitness en Render (free tier duerme a los 15 min).

- `keepalive-render.yml`: ping cada 10 min a `/api/health`.
- `heartbeat.yml`: commit vacío semanal para que GitHub no deshabilite el cron a los 60 días.

No contiene código ni secretos de la app.
