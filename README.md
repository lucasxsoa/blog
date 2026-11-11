# Blog pessoal

Blog minimalista feito com Jekyll e publicado automaticamente no GitHub Pages.

## Personalização rápida

1. Em `_config.yml`, ajuste o nome e a descrição quando quiser.
2. Edite `sobre.md` e `contato.md`.
3. Remova ou substitua o texto de exemplo em `_posts/`.

## Publicar um novo texto

Crie um arquivo em `_posts` com o nome `AAAA-MM-DD-titulo-curto.md`:

```md
---
layout: post
title: "Título do texto"
---

Seu texto começa aqui.
```

Ao salvar e enviar a alteração para a branch `main`, o GitHub Pages republica o blog automaticamente.

## Ativar o GitHub Pages

No repositório, abra **Settings → Pages → Build and deployment** e selecione **GitHub Actions**. Depois, acompanhe a primeira publicação na aba **Actions**.

