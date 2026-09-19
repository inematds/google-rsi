# Validação — 19/09/2026

## Guia

- Navegador Chromium real via Playwright: larguras 320, 390, 768 e 1440px, sem overflow horizontal da página.
- Cinco imagens locais carregadas e âncoras internas resolvidas.
- Comparador: 550 → 317 (42,4%) e 3.200 → 1.879 (41,3%); números calculados a partir da tabela original.
- Quiz: respostas correta e incorreta apresentam explicação; estado selecionado acessível.
- Tema claro/escuro: alternância e persistência após recarregar confirmadas.
- Console: nenhum erro JavaScript observado.
- Links locais: todos existem; nenhum placeholder do template restante.
- Revisão visual em desktop/mobile e tema claro; corrigida a altura responsiva do hero e o contraste do texto dos botões claros.
- Figuras originais preservadas; SHA-256 e origem em fontes/imagens.json.
- Capa social renderizada como composição tipográfica do projeto com a figura original creditada; não é imagem científica nova.

## Catálogo

Worktrees isoladas preservam alterações existentes no portal e nas buscas. Fonte do portal regenerada com `npm run gen:data`; traduções EN/ES geradas pelo script existente. Os nove testes do portal e TypeScript (`tsc --noEmit --incremental false`) passaram.

## Limites

O vídeo não foi retranscrito; foi analisado o resumo integral fornecido e confrontado com fontes primárias. Os anexos no clipboard remoto não concluíram a leitura. Não houve execução do código científico Dream-RSI, que não é o propósito desta entrega.
