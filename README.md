# Globoplay Kids — protótipos de TV

Dois protótipos navegáveis do app de TV do Globoplay Kids (3 a 6 anos). Cada um é um
arquivo HTML autocontido: abre direto no navegador, sem servidor e sem dependências.

| Arquivo | Abordagem |
| --- | --- |
| `roleta.html` | **V2 — Roleta.** Seletor circular de universos + leque de destaques. |
| `galaxias.html` | **V6 — Galáxias.** Plano explorável, uma galáxia por universo. |
| `index.html` | Página de entrada com os dois. |

## Publicar no GitHub Pages

1. Suba os arquivos na raiz do repositório (ou numa pasta `docs/`).
2. Em **Settings → Pages**, escolha a branch e a pasta.
3. A entrada é `index.html`.

Os dois HTML são grandes (~10 MB cada) porque carregam todas as artes embutidas. Ficam
abaixo do limite de 100 MB por arquivo do GitHub e não precisam de Git LFS.

## Como testar

- Desenhados para **1920×1080**; cada um se escala para a janela.
- Navegação por **setas + Enter** (D-pad de TV) ou clique.
- **Marina** entra direto na home (visita recorrente); **Pedro** passa pela pergunta de
  idade (primeiro acesso).
- Parar o foco num título por cerca de um segundo abre a **prévia**.
- Clicar no **cronômetro** dispara o aviso de fim de tempo de tela.
