# Gateway Checker Bot

Telegram bot that scans URLs for payment gateways, captchas, Cloudflare, GraphQL endpoints, etc.

## Setup

1. Create a Telegram bot and get the token
2. Get your channel numeric ID (e.g. via @raw_id_bot)
3. Add them as environment variables:
   - `TOKEN`
   - `CHANNEL_ID`

## Deploy

### Locally:
```bash
pip install -r requirements.txt
TOKEN="..." CHANNEL_ID="-100..." ./start.
