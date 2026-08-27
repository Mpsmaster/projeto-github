# projeto-github

Projeto desenvolvido durante o Workshop de GitHub da COTI Informática.

Este repositório contém um projeto front-end simples criado como exercício durante o workshop. Ele usa apenas tecnologias web básicas e é ideal para aprender fluxo de trabalho com Git e GitHub.

## Linguagens e tecnologias

- HTML — marcação das páginas (arquivos `.html`, por exemplo `index.html`).
- CSS — estilos e layout (arquivos `.css` normalmente em uma pasta `css/`).
- JavaScript — comportamento e interatividade (arquivos `.js` normalmente em uma pasta `js/`).

O projeto é estático e roda em qualquer navegador moderno sem necessidade de servidor backend.

## Estrutura esperada do repositório

- `index.html` — página principal
- `css/` — arquivos de estilo (ex.: `css/style.css`)
- `js/` — scripts JavaScript (ex.: `js/app.js`)
- `images/` — imagens e outros ativos

A estrutura acima é uma sugestão; ajuste conforme os arquivos reais do repositório.

## Como abrir e rodar o projeto no Visual Studio Code (VS Code)

Pré-requisitos:
- Visual Studio Code instalado
- (Opcional) Git para clonar o repositório
- (Recomendado) Extensão Live Server para facilitar desenvolvimento

Passos:

1. Clone o repositório ou baixe o ZIP:

   ```bash
   git clone https://github.com/Mpsmaster/projeto-github.git
   ```

2. Abra a pasta do projeto no VS Code:

   ```bash
   cd projeto-github
   code .
   ```

3. Instale a extensão Live Server (se ainda não tiver):
   - Abra o painel Extensões (Ctrl+Shift+X ou Cmd+Shift+X) e pesquise por "Live Server" (desenvolvedor: Ritwick Dey). Instale-a.

4. Rode o projeto:
   - Clique com o botão direito em `index.html` no Explorador do VS Code e selecione "Open with Live Server"; ou clique em "Go Live" no canto inferior direito.
   - O Live Server abrirá uma página no navegador, tipicamente em `http://127.0.0.1:5500/`.

Alternativas (sem Live Server):

- Usando Python 3 (tem que estar na pasta do projeto):

  ```bash
  python -m http.server 8000
  # abra http://localhost:8000 no navegador
  ```

- Usando um servidor simples do Node (http-server):

  ```bash
  npx http-server .
  # abra a URL informada pelo comando
  ```

5. Faça alterações nos arquivos no VS Code. Com Live Server as mudanças são recarregadas automaticamente no navegador.

## Contribuições

Este repositório foi criado como material didático do workshop. Contribuições e melhorias são bem-vindas:
- Abra uma issue para sugerir melhorias ou relatar problemas.
- Crie um pull request com correções ou novos exemplos.

## Créditos
Projeto e materiais: Workshop GitHub — COTI Informática.

---

Se você quiser, posso listar os arquivos atuais do repositório e ajustar este README para refletir a estrutura real — quer que eu faça isso agora?