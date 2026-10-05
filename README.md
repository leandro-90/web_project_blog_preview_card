<div align="center">

# 📰 Blog Preview Card

Componente de card de pré-visualização de blog, desenvolvido com **HTML e CSS puros** como solução para um desafio do [Frontend Mentor](https://www.frontendmentor.io?ref=challenge).

[![Deploy](https://img.shields.io/badge/demo-GitHub%20Pages-f4d04e?style=for-the-badge&logo=github&logoColor=black)](https://leandro-90.github.io/web_project_blog_preview_card/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**[🔗 Ver projeto online](https://leandro-90.github.io/web_project_blog_preview_card/)**

</div>

---

## 📑 Sumário

- [Sobre o projeto](#-sobre-o-projeto)
- [Demonstração](#-demonstração)
- [Tecnologias](#-tecnologias)
- [Funcionalidades e detalhes de design](#-funcionalidades-e-detalhes-de-design)
- [Estrutura do projeto](#-estrutura-do-projeto)
- [Como executar localmente](#-como-executar-localmente)
- [Paleta de cores](#-paleta-de-cores)
- [Aprendizados](#-aprendizados)
- [Melhorias futuras](#-melhorias-futuras)
- [Autor](#-autor)
- [Créditos](#-créditos)

---

## 📖 Sobre o projeto

Este projeto reproduz um **card de pré-visualização de artigo de blog**, com ilustração, categoria, data de publicação, título com link, descrição curta e identificação do autor.

Foi construído para praticar os fundamentos da web: **estrutura semântica com HTML** e **estilização com CSS** (Flexbox, tipografia, sombras, bordas arredondadas e estados de interação). **Nenhuma linha de JavaScript foi utilizada.**

### Conteúdo exibido no card

| Elemento    | Conteúdo                                                                         |
| ----------- | -------------------------------------------------------------------------------- |
| Categoria   | Learning                                                                         |
| Publicação  | 21 Dec 2023                                                                      |
| Título      | HTML & CSS foundations                                                           |
| Descrição   | These languages are the backbone of every website, defining structure, content, and presentation. |
| Autor       | Greg Hooper                                                                      |

---

## 🚀 Demonstração

Acesse a versão publicada via GitHub Pages:

👉 **https://leandro-90.github.io/web_project_blog_preview_card/**

---

## 🛠 Tecnologias

- **HTML5**: marcação semântica (`main`, `footer`, `h2`, `img`, `a`)
- **CSS3**: estilização embutida no `index.html`, com Flexbox
- **Git e GitHub**: versionamento do código
- **GitHub Pages**: hospedagem e publicação

> ℹ️ O projeto **não utiliza JavaScript**, frameworks ou bibliotecas externas.

---

## ✨ Funcionalidades e detalhes de design

- Card centralizado na página com **Flexbox**
- **Sombra sólida** deslocada (`7px 7px`) em estilo neo-brutalista
- Bordas arredondadas na ilustração e no card
- Etiqueta de categoria com fundo amarelo e largura ajustada ao conteúdo (`width: max-content`)
- **Efeito hover** no título: a cor do link muda de preto para amarelo
- Descrição com opacidade reduzida e `line-height` ampliado para melhor leitura
- Avatar do autor alinhado ao nome com `display: flex` e `column-gap`
- Rodapé de atribuição com links externos que abrem em nova aba (`target="_blank"`)

---

## 📁 Estrutura do projeto

```
web_project_blog_preview_card/
├── design/            # Materiais de referência do design do desafio
├── images/
│   ├── illustration-article.svg   # Ilustração do artigo
│   └── image-avatar.webp          # Avatar do autor
├── .gitignore
├── index.html         # Estrutura da página e estilos CSS
└── README.md
```

---

## 💻 Como executar localmente

Como o projeto é estático, **não há dependências nem etapa de build**.

**1. Clone o repositório**

```bash
git clone https://github.com/leandro-90/web_project_blog_preview_card.git
```

**2. Acesse a pasta do projeto**

```bash
cd web_project_blog_preview_card
```

**3. Abra o projeto no navegador**

Dê um duplo clique no arquivo `index.html` ou, se preferir, use uma extensão como o **Live Server** do VS Code.

---

## 🎨 Paleta de cores

| Cor                  | Valor                | Uso                                          |
| -------------------- | -------------------- | -------------------------------------------- |
| 🟨 Amarelo           | `#f4d04e`            | Fundo da página, etiqueta e hover do título  |
| ⬛ Preto             | `black`              | Título e sombra do card                      |
| ⬜ Branco            | `white`              | Fundo do card                                |
| 🟦 Azul acinzentado  | `hsl(228, 45%, 44%)` | Links do rodapé de atribuição                |

**Tipografia:** Arial, Helvetica, sans-serif.

---

## 📚 Aprendizados

- Estruturação de uma página com HTML semântico
- Centralização e alinhamento de elementos com Flexbox
- Estilização de textos, imagens, bordas e sombras com CSS
- Uso de pseudo-classes (`:hover`) para interação
- Publicação de um site estático com GitHub Pages
- Fluxo básico de versionamento com Git e GitHub

---

## 👨‍💻 Autor

**Leandro Ferreira**

[![GitHub](https://img.shields.io/badge/GitHub-leandro--90-181717?style=flat-square&logo=github)](https://github.com/leandro-90)

---

## 🙌 Créditos

O desafio e o design original são do [Frontend Mentor](https://www.frontendmentor.io?ref=challenge). O código desta solução foi desenvolvido por [Leandro Ferreira](https://github.com/leandro-90).