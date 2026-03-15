# Matrix Server Deployment

Self-hosted Matrix chat server using Synapse, Element Web, Nginx, and Azure VM.

## Components

- Synapse (Matrix server)
- Element Web (web client)
- Nginx reverse proxy
- Let's Encrypt TLS
- Azure VM hosting

## Domain

chat.greycell.online

## Key Features

- HTTPS enabled
- Federation working
- Nginx reverse proxy
- Cloudflare DNS
- Docker deployment

## Important Paths

Synapse config:
~/matrix-synapse/data/homeserver.yaml

Element web:
~/element-web

Nginx config:
 /etc/nginx/sites-available/matrix

## Deployment Overview

1. Create Azure VM
2. Install Docker and Docker Compose
3. Deploy Synapse
4. Deploy Element Web
5. Configure Nginx reverse proxy
6. Configure DNS in Cloudflare
7. Issue TLS certificate using Certbot
