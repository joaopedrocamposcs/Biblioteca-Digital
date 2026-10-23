# Biblioteca Digital

Sistema web para catalogar e consultar livros em um ambiente digital, com páginas para início, catálogo, detalhes do livro, login e administração.

## Visão Geral
A Biblioteca Digital é um projeto em desenvolvimento para organizar um acervo bibliográfico em formato digital. A aplicação tem como objetivo facilitar a navegação por livros, apresentar informações dos títulos e permitir o acesso administrativo para gerenciar o conteúdo.

## Objetivo
- Organizar livros em um catálogo;
- Exibir detalhes de cada obra;
- Permitir acesso por login;
- Criar uma área administrativa para gerenciamento do acervo;
- Oferecer uma interface simples e funcional.

## Funcionalidades
- Página inicial;
- Catálogo de livros;
- Página de detalhes do livro;
- Tela de login;
- Área administrativa;
- Estrutura responsiva para diferentes telas;
- Interações com JavaScript.

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript

## Estrutura do Projeto
```text
Biblioteca-Digital/
├── README.md
├── app.js
├── Estetica/
│   ├── script.js
│   └── style.css
├── Estrutura_html/
│   ├── admin.html
│   ├── catalago.html
│   ├── index.html
│   ├── livro.html
│   └── login.html
└── documentação.txt
```

## Como Executar
1. Abra a pasta do projeto no navegador.
2. Acesse a página inicial em:
   `Estrutura_html/index.html`
3. Ou rode um servidor local para visualizar melhor:

```bash
cd "C:\Users\joaop\OneDrive\Desktop\Biblioteca-Digital"
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/Estrutura_html/index.html
```

## Status do Projeto
O projeto está em fase inicial, com estrutura básica pronta e páginas estáticas. Ainda não há banco de dados ou backend integrado.

## Próximos Passos
- Implementar banco de dados para os livros;
- Criar sistema de autenticação;
- Desenvolver área administrativa completa;
- Adicionar busca e filtros;
- Melhorar a responsividade e o design;
- Integrar front-end com backend.

## Conclusão
A Biblioteca Digital é um projeto inicial de gestão de acervo literário, com uma base sólida em HTML, CSS e JavaScript. Ele pode evoluir para uma aplicação completa de biblioteca digital com funcionalidades de catálogo, administração e autenticação.
