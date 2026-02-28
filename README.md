# Apresentação (Reveal.js) — Diretoria de Sistemas

Projeto estático em HTML (Reveal.js) seguindo o roteiro definido.

## Como executar localmente
1. Abra `index.html` no navegador (Chrome/Edge/Firefox).
2. Use **← →** para navegar.
3. Pressione **S** para abrir o *Presenter View* com as notas do apresentador.

> Dica: para evitar bloqueios de mídia no navegador, rode um servidor local.

### Servidor local (opções)
- Python:
  ```bash
  python -m http.server 8000
  ```
  Acesse: http://localhost:8000

- Node (npx):
  ```bash
  npx serve .
  ```

## Estrutura
- `index.html`: slides, layout, animações e *speaker notes*.
- `assets/`: imagens (cover, eixos, encerramento).

## Publicar no GitHub Pages
1. Suba este projeto em um repositório.
2. GitHub → **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / Folder: `/root`
5. Aguarde o link do GitHub Pages.

## Trocar imagens
Substitua os arquivos em `assets/` mantendo os nomes:
- `cover.png`, `encerramento.png`
- `eixo1.png` ... `eixo14.png`

