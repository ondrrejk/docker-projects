# handle secrets correctly
Never put secrets in:
- Dockerfiles
- Images
- Git repos
- Environment variables in plain text
Better options:
- .env files (ignored by Git)
- Docker secrets
- Vault (later in your journey)