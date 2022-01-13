# Setup
- Create `.env` file [Options here](#env-file-config).
- Edit `start.sh`, editing port & app name.
- Make `start.sh` executable.
- Run `./start.sh`.
- Proxy exposed port.

## Env file config
```
DISCORD_CLIENT_ID=discord-client-id
DISCORD_CLIENT_SECRET=discord-client-secret
DISCORD_BOT_TOKEN=discord-bot-token
DISCORD_API_URL=https://discord.com/api
DISCORD_GUILD_ID=927648040473464873

ROOT_DISCORD_IDS=92764084328269417,92764084328269417

CURRENCY=USD

STRIPE_WEBHOOK_SECRET=stripe-webhook
STRIPE_API_KEY=stripe-api-key

SESSION_SECRET=long-secure-string
```