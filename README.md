# KP Móveis Planejados

Site da KP Móveis Planejados (Sorocaba - SP). HTML, CSS e JS puros, com servidor Node sem dependências.

## Rodar

```bash
node server.js
```

Abre em http://localhost:3000. `PORT` e `ADMIN_TOKEN` são variáveis de ambiente opcionais.

## Estrutura

- `public/` — site estático (pode ir para hospedagem estática; o formulário cai direto no WhatsApp sem o servidor)
- `server.js` — arquivos estáticos, `POST /api/orcamento`, `GET /api/leads` (exige `ADMIN_TOKEN`)
- `data/leads.jsonl` — pedidos recebidos (fora do Git)

## Antes de publicar

Trocar o domínio provisório `kpmoveisplanejados.com.br` em `public/index.html`, `public/sitemap.xml`, `public/robots.txt` e `public/llms.txt`.
