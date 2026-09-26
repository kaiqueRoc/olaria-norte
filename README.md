# Olaria Norte — Cerâmica feita à mão

Landing page conceitual para a **Olaria Norte**, um ateliê de cerâmica artesanal em Belo Horizonte. Projeto desenvolvido como case de portfólio (design/direção de arte), simulando um site real de e-commerce + institucional para uma marca de cerâmica.

🔗 **Site publicado:** _adicione aqui o link do GitHub Pages depois de ativar_

## Sobre o projeto

O site apresenta a marca Olaria Norte com uma linguagem visual editorial — tons terrosos, serifada para títulos, muito espaço em branco — e cobre toda a jornada de um site de marca de produto:

- **Hero** com chamada principal e link para a coleção
- **Coleção Serra** — vitrine de peças (tigela, caneca, prato, jarra) em layout bento, com preço e botão "Adicionar à sacola"
- **Do barro à mesa** — seção de processo/ateliê, contando como as peças são feitas
- **Aulas de torno** — três pacotes de aulas com preço e CTA de reserva
- **Diário do ateliê** — mini-blog com posts sobre o dia a dia da produção
- **Newsletter** — formulário de e-mail para avisos de nova fornada, com validação em JS

## Tecnologias

Site estático, sem build nem dependências:

- HTML5 semântico
- CSS puro (custom properties, grid, flexbox) — inclui suporte a **modo claro/escuro** automático via `prefers-color-scheme`
- JavaScript vanilla (interações da sacola e do formulário de newsletter)
- Fonte [Bodoni Moda](https://fonts.google.com/specimen/Bodoni+Moda) + [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk), via Google Fonts
- Imagens de [Unsplash](https://unsplash.com), sob a [Unsplash License](https://unsplash.com/license)

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + JS em um único arquivo)
└── README.md
```

## Rodando localmente

Não precisa de servidor nem instalação — é um único arquivo HTML autocontido:

```bash
git clone https://github.com/SEU-USUARIO/olaria-norte.git
cd olaria-norte
open index.html   # ou clique duas vezes no arquivo
```

## Publicando no GitHub Pages

1. Faça upload do `index.html` para um repositório público no GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`
4. Salve — em alguns minutos o site fica no ar em `seuusuario.github.io/nome-do-repo`

## Créditos

- Design e desenvolvimento: **Kaique**
- Projeto conceitual/fictício, criado para fins de portfólio — a marca Olaria Norte não existe
- Fotografias: Unsplash (fotógrafos individuais creditados nos metadados do arquivo)
