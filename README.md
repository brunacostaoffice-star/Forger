# Forger — Treino do Thiago

Aplicativo pessoal de treino com ficha A–D, histórico, evolução, medidas e backup local.

## Publicação no GitHub e Vercel

1. Envie todos os arquivos desta pasta para a raiz do repositório.
2. No Vercel, importe o repositório.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio.
5. Output Directory: deixe vazio.
6. Publique.

O arquivo principal é `index.html`.

## Estrutura

- `index.html`: aplicativo completo.
- `manifest.json`: instalação como aplicativo/PWA.
- `sw.js`: cache básico para funcionamento offline.
- `icons/`: ícones do aplicativo.

Os dados de treino são armazenados no navegador por meio de `localStorage`. Para trocar de aparelho ou navegador, use a função de backup dentro do próprio app.
