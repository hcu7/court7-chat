# Court 7 Chat

Mattermost-Setup für Court 7, deployed via Coolify auf https://chat.court7.club.

Container:
- `mattermost` — Mattermost Team Edition 9.11
- `postgres` — Postgres 16 Alpine

Coolify-ENV-Variable benötigt:
- `POSTGRES_PASSWORD` — DB-Password (random per Service-Provisioning)

Diesen Repo NUR zum Coolify-Pull verwenden — das tatsächliche Setup ist in Coolify's API-Config.
