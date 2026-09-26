# Dream-RSI — Aprender a descobrir

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

Projeto educativo independente INEMA sobre como históricos de experimentos podem orientar melhores estratégias de pesquisa em IA.

**[Abrir landing + guia](https://inematds.github.io/google-rsi/guia/)** · [Plano educativo](docs/PLANO-EDUCATIVO.md) · [Análise das fontes](docs/ANALISE.md)

## O que existe

Guia em português, cinco figuras originais com crédito, comparação interativa de Lasso e uma atividade de compreensão. O plano descreve oito encontros e um laboratório futuro; não há implementação científica do Dream-RSI neste repositório.

## Executar localmente

```bash
python3 -m http.server 8765
# Abra http://localhost:8765/guia/
```

HTML, CSS e JavaScript inline; sem build, conta ou API. As fontes Google Fonts são opcionais, com fallback local. Imagens em `guia/assets/`.

## Fontes

[Projeto original](https://www.dream-rsi.com/) · [Artigo](https://arxiv.org/html/2609.14858v1) · [Código dos autores](https://github.com/zhengkid/Dream-RSI).

As figuras pertencem aos autores do Dream-RSI. Proveniência em [fontes/imagens.json](fontes/imagens.json). Este projeto não é afiliado ao Google/DeepMind. Conteúdo baseado nas fontes consultadas em 19/09/2026.

Versão 1.0.0.
