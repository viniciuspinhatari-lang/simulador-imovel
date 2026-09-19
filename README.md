# Simulador de financiamento imobiliário

Página única, sem dependências de build. Todo o código está em `index.html`
(Google Fonts é a única coisa carregada de fora). Os dados ficam salvos no
navegador de quem usa — não há servidor nem banco.

## Publicar uma nova versão

Edite `index.html` e rode, de dentro desta pasta:

```
npx wrangler pages deploy
```

É só isso. O `wrangler.toml` já define o projeto (`simulador-imovel`) e a pasta
publicada (`.`). O comando devolve a URL do deploy.

## Primeira vez numa máquina nova

```
npx wrangler login
```

Abre o navegador para autorizar a conta Cloudflare. Depois disso o comando de
deploy acima funciona direto.

## O que NÃO é publicado

`wrangler.toml`, `.assetsignore` e este `README.md` — listados em `.assetsignore`.

## Conta

Cloudflare account id: `5e1a6e64225fb86ea4326186172dce54`
Projeto Pages: `simulador-imovel`
