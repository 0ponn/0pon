# 0pon.com

Portfolio landing page for 0pon.com services.

## Live

- https://0pon.com
- https://www.0pon.com

## Features

- Links to all apps: witchat, enjoyyy, textarea, cage, matrix, forums
- Single HTML file, served via Python http.server
- Cloudflare tunnel for HTTPS

## Local Development

```bash
python3 -m http.server 8081
```

## Deployment

Runs as a systemd service on ZimaBoard. See NixOS configuration for details.
