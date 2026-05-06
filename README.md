# Workout Tracker

App web estático, mobile-first, feito com HTML/CSS/JS puro para acompanhar treinos no iPhone. Não usa backend, frameworks, bibliotecas externas nem imagens remotas obrigatórias.

## Arquivos

- `index.html`: app completo com CSS e JavaScript inline.
- `manifest.webmanifest`: metadados PWA para instalação.
- `.nojekyll`: evita processamento pelo Jekyll no GitHub Pages.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie estes arquivos para a raiz do repositório.
3. No GitHub, abra `Settings` > `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde a URL do GitHub Pages aparecer.

## Abrir no iPhone

1. Abra a URL publicada no Safari.
2. Toque em `Compartilhar`.
3. Toque em `Adicionar à Tela de Início`.
4. Confirme o nome `Workout`.

O progresso diário, checklist e streak ficam salvos no navegador via `localStorage`.
