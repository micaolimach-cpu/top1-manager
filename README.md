# Top 1 Manager

Jogo de gestão de futebol em navegador, com foco em carreira, competições brasileiras, escalação tática, mercado, base, estádio e decisões de treinador.

## Build atual: V36

A V36 está publicada no repositório com `index.html` como entrada principal. A base V35 original foi preservada em `index[1].html` e o patch V36 é carregado sobre ela para manter compatibilidade enquanto o projeto continua sendo modularizado.

Principais melhorias da V36:
- navegação mobile em barra inferior;
- campo tático protegido contra movimentos acidentais por toque;
- camisas mais minimalistas;
- sons distintos de apito e eventos de partida;
- rádio da partida;
- resumo da rodada restaurado;
- preservação de rolagem e melhorias gerais de estabilidade.

## Estrutura principal

- `index.html` — entrada principal do jogo;
- `index[1].html` — base V35 preservada;
- `js/26-v36-polish.js` — patch V36;
- `v36-polish.css` — estilos V36;
- `manifest.webmanifest` e `sw.js` — PWA/offline;
- `icon-192.png`, `icon-512.png` e `top1-manager-logo.png` — identidade visual;
- `rules.html` — página de regras.
