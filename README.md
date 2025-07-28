# Recriando a Wikipdia com Layout Moderno | Dio
# Página Semântica – Alice in Borderland (Série de TV)

Este projeto recria a página da Wikipédia da série *Alice in Borderland*, com foco em **acessibilidade**, **estrutura semântica** e **uso correto de HTML5**.

## 🎯 Objetivo

O objetivo deste projeto é demonstrar o uso de HTML semântico, organização de conteúdo por seções, e aplicação de boas práticas de acessibilidade, como `aria-labels`, navegação por âncoras e marcações apropriadas com `<figure>`, `<figcaption>`, `<nav>`, `<main>`, `<aside>`, entre outras.

---

## 📁 Estrutura do Projeto

/
├── index.html # Página principal
├── assets/
│ ├── css/
│ │ └── style.css # Estilos da página
│ └── images/
│ ├── wikipedia.png
│ ├── wikipedia-wordmark-fr.svg
│ └── wikipedia-tagline-pt.svg


---

## 🧱 Tecnologias Utilizadas

- HTML5
- CSS3 (básico, sem frameworks)
- Estrutura inspirada na Wikipédia
- Responsividade básica com grid CSS

---

## 📌 Funcionalidades

- Navegação interna com âncoras (`<a href="#id">`)
- Layout de três colunas (`sidebar` + `main` + `anchors`)
- Uso de `<figure>` e `<figcaption>` para vídeos e imagens
- Elementos visuais com `alt` e `aria-hidden` apropriados
- Links de referência no final do conteúdo com `<aside>`

---

## ✅ Acessibilidade

- Uso de landmarks: `<header>`, `<nav>`, `<main>`, `<footer>`, `<aside>`
- Textos alternativos (`alt`) e descrições de vídeo (`figcaption`)
- Navegação por teclado facilitada
- Separação clara entre conteúdo e navegação
- Estrutura semântica facilita leitores de tela

---

## 📸 Pré-visualização

A página simula um artigo da Wikipédia com conteúdo fictício sobre a série "Alice in Borderland", contendo:

- Sinopse
- Elenco
- Curiosidades
- Trailer do YouTube incorporado
- Tabela de informações técnicas (ex. país, gênero, episódios)

---

## 💡 Melhorias Futuras

- Adicionar responsividade total com media queries
- Incluir suporte a temas claro/escuro
- Expandir conteúdo real e usar dados estruturados (microdata/schema)

---

## 👩‍💻 Autor

Projeto criado por **Marianna Dorta** como parte de um desafio na **Digital Innovation One (DIO)**.

---

## 📄 Licença

Este projeto é de uso educacional e não possui fins comerciais. Créditos das imagens e vídeos à Wikipédia e Netflix.

