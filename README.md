# Meu Portal de Entretenimento Digital

Este projeto consiste em uma página web responsiva que funciona como um portal de entretenimento digital, abordando tópicos sobre filmes, séries, música, podcasts, games e tecnologia. 

O projeto foi construído utilizando HTML5 e CSS3 puro, aplicando boas práticas de estruturação e resets de estilo para garantir consistência visual entre diferentes navegadores.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página (`<header>`, `<main>`, `<section>`, `<footer>`).
- **CSS3:** Estilização responsiva utilizando Flexbox e Media Queries.
- **Reset CSS:** Normalização de estilos baseada no modelo de Eric Meyer.

---

## 📁 Estrutura de Arquivos

```text
.
├── index.html          # Arquivo principal com a estrutura HTML do portal
├── reset.css           # CSS Reset para remoção de margens e padronização de elementos
├── estilo.css          # Estilos principais do portal (layout, flexbox e responsividade)
└── imagens/            # Diretório de mídia contendo as imagens da página
    ├── cine.avif
    ├── film.avif
    ├── micr.avif
    ├── inst.avif
    ├── game.avif
    └── disp.avif
```

---

## 🚀 Funcionalidades e Destaques

1. **Reset CSS Integrado:**
   - Carregado antes dos estilos principais no `index.html` para zerar padronizações divergentes entre navegadores.

2. **Layout Responsivo (Flexbox):**
   - As seções de conteúdo (`.secao`) se organizam lado a lado em telas maiores utilizando `display: flex`.
   - Ajuste automático para visualização mobile (telas com até 600px) através de `@media query`, empilhando os cards verticalmente.

3. **Inclusão de CSS de Múltiplas Formas:**
   - **External CSS:** `reset.css` e `estilo.css`.
   - **Internal CSS:** Estilos definidos na tag `<style>` do `index.html` para regras gerais (`body`, `h1`, `.introducao`).
   - **Inline CSS:** Estilização direta na tag `<footer>`.

4. **Seções de Conteúdo:**
   - **Filmes e Séries:** Destaques e lançamentos cinematográficos.
   - **Música e Podcasts:** Estilos musicais, playlists e episódios de podcasts.
   - **Games e Tecnologia:** Notícias sobre jogos, inovação e inteligência artificial.

---

## 🔧 Como Executar o Projeto

1. Clone ou baixe os arquivos do repositório.
2. Certifique-se de manter a estrutura de pastas conforme apresentada acima (incluindo a pasta `imagens/` com os arquivos correspondentes).
3. Abra o arquivo `index.html` em qualquer navegador web de sua preferência.