# Quick n8n Setup Guide
## Install and Run n8n
1. Install n8n globally: `npm install -g n8n`
2. Start n8n with tunneling: `n8n start --tunnel`

## Docker Setup
1. Set permissions for the `.n8n` directory: `sudo chown -R $(whoami) ~/.n8n`

## Integrate with ngrok and Gmail
1. Sign up for ngrok and get your token (e.g., `2seNw5CImmo95X31IjA6m......`).
2. Start the Docker container.
3. Run ngrok to tunnel n8n: `ngrok http http://0.0.0.0:5678`
4. Use the ngrok URL to access n8n and start working.


