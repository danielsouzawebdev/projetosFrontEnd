# Projetos na Prática

Site estático (HTML + CSS puro, sem dependências externas na própria página de material) com três projetos guiados, passo a passo, combinando HTML, CSS, JavaScript e Bootstrap.

## Estrutura

```
.
├── index.html       # página inicial — as quatro trilhas de pré-requisito + os 3 projetos
├── projeto1.html     # Pet Shop — Landing Page (nível básico)
├── projeto2.html     # Lista de Tarefas com Filtros (nível intermediário)
├── projeto3.html     # Painel do Tempo — API real (nível avançado)
├── assets/
│   └── css/
│       └── style.css
└── README.md
```

## Relação com os outros sites

Este site assume que os quatro materiais abaixo já existem como **pastas irmãs**, no mesmo repositório ou nível de diretório:

```
.
├── html-site/
├── css-site/
├── js-site/
├── bootstrap-site/
└── projetos-site/   (este)
```

Os links de pré-requisito em `index.html` e em cada projeto (`../html-site/...`, `../css-site/...` etc.) dependem dessa estrutura. Se os sites forem publicados em repositórios separados, edite esses links para apontar para as URLs reais de cada um.

## Como publicar no GitHub Pages

1. Envie os arquivos para a raiz de um repositório GitHub (mantendo `assets/` no mesmo nível de `index.html`).
2. **Settings** → **Pages** → **Source**: `Deploy from a branch` → branch `main`, pasta `/ (root)`.
3. O link aparece em `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/` em alguns minutos.

## Sobre os projetos

Cada projeto é autoinstrucional: todo arquivo a criar, todo trecho de código, numerado passo a passo, com uma checklist de verificação e desafios extras ao final. O Projeto 3 consome a API pública e gratuita da [Open-Meteo](https://open-meteo.com), que não exige cadastro nem chave de API — os exemplos de código funcionam copiados e colados diretamente.
