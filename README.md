# Indiazinha Links

Repositorio estatico para Netlify.

## Netlify

Este repositorio nao precisa de Node, npm ou build do bot.

Configuracao esperada:

- Base directory: vazio
- Build command: `echo Static site: no build step required`
- Publish directory: `.`

O arquivo `netlify.toml` ja define esses valores para evitar que a Netlify tente publicar uma pasta errada.

## Editar links

Abra `index.html` e altere:

```js
const DISCORD_URL = 'https://discord.gg/gsYENYhGzA';
const SHARE_URL = 'https://indiazinharedes.netlify.app/';
```

Se a Netlify mostrar `Project has been paused`, isso normalmente precisa ser resolvido no painel da Netlify em Usage & billing antes de novos deploys entrarem no ar.
