# Site — A Pharmacinha

Landing page estática (HTML + Tailwind via CDN + JS puro), pronta para o GitHub Pages.

## Estrutura

```
index.html          → página completa (HTML + CSS + JS num único arquivo)
images/
  fachada-atual.jpg        → foto atual da loja (Hero)
  inauguracao-antiga.jpg   → foto antiga da inauguração (Sobre)
  construcao.jpg           → foto da obra do prédio atual (Sobre)
  antes-e-depois.jpg       → colagem antes/depois (Sobre)
```

## Antes de publicar — dados a confirmar/substituir

Marcados com `TODO` ou comentário no próprio `index.html`:

- **Número de WhatsApp**: hoje está como `5516000000000` (placeholder) em 5 lugares
  (header, hero, faixa de conversão, rodapé, botão flutuante). Buscar/substituir por
  `https://wa.me/55DDDNÚMERO`.
- **Endereço, telefone fixo e horário de funcionamento** no rodapé — hoje têm valores
  de exemplo.
- **Ano de fundação (1997)** na linha do tempo — calculado a partir dos "29 anos"
  citados no briefing. Vale confirmar a data exata.
- **Depoimentos** — os três da seção "Quem já veio, confia" são ilustrativos.
  Recomendo trocar por avaliações reais (Google, Instagram) assim que possível.

## Publicando no GitHub Pages

1. Suba `index.html` e a pasta `images/` para a raiz do repositório `Pharmacinha`.
2. Em *Settings → Pages*, selecione a branch `main` e a pasta `/ (root)`.
3. O site fica disponível em `https://vit0r-maker.github.io/Pharmacinha/`.

## Nota técnica

O projeto usa o Tailwind CSS via CDN (`cdn.tailwindcss.com`), como pedido no
briefing — ótimo para lançar rápido, mas ele compila o CSS no navegador do
visitante a cada acesso (mais lento que um build). Se o tráfego crescer, vale
migrar para o Tailwind CLI com um build estático e purge do CSS não usado.
# Pharmacinha
