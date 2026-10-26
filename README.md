# Orisema Website

Portal institucional da comunidade open source **Orisema**.

> Uma ideia nasce. Muitas mãos a fazem crescer.

## Desenvolvimento

Requer Node.js 20.19+ ou 22.12+.

```bash
npm install
npm run dev
npm run build
```

## Deploy no Cloudflare Pages

1. Conecte o repositório `Orisema/Orisema-Website` ao Cloudflare Pages.
2. Framework: **Astro**; comando: `npm run build`; saída: `dist`.
3. Associe o domínio `orisema.tec.br` nas configurações do Pages.
4. Confira DNS e HTTPS antes de anunciar o site.

Não crie registros A apontando para endereços arbitrários. Prefira o fluxo de domínio personalizado do Pages.

## Licença

Apache-2.0.
