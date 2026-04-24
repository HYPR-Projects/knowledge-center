# HYPR Knowledge Center

Hub interno da HYPR com links, ferramentas e dashboards do time.

## Stack
Site estático (HTML + CSS + JS inline). Sem build step.

## Deploy
Deploy automático via Vercel. Qualquer push na branch `main` dispara novo deploy.

## Estrutura
- `index.html` — página principal do hub
- `admin.html` — painel admin
- `vercel.json` — configuração de headers, cache e clean URLs
- assets: `logo.png`, `login-bg.webp`, favicons

## Dev local
Basta abrir `index.html` no browser ou rodar qualquer servidor estático:

```bash
npx serve .
# ou
python3 -m http.server 8000
```
