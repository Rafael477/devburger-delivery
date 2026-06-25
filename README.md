# App de Entrega

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) ![Stack](https://img.shields.io/badge/stack-HTML%20%2B%20CSS%20%2B%20JavaScript-blue)

## Demo
Acesse a versão publicada: [App de Entrega](https://rafael477.github.io/App-de-entrega/)

## Descrição
Aplicação web estática para apresentação de cardápio de hamburgueria, com layout visual para produtos, bebidas e experiência de compra em página única.

## Objetivo
Criar uma vitrine digital simples para um negócio de delivery, facilitando a visualização do menu e servindo como base para evoluir para um sistema de pedidos online.

## Tecnologias utilizadas
- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Font Awesome
- Node.js para tooling local do Tailwind

## Funcionalidades
- Exibição de menu com produtos e imagens.
- Seção visual de bebidas e hambúrgueres.
- Estilos organizados em `styles/`.
- Assets centralizados em `assets/`.

## Estrutura de pastas
```text
.
├── assets/              # Imagens dos produtos
├── styles/              # CSS principal e saída do Tailwind
├── index.html           # Página principal
├── script.js            # JavaScript do projeto
├── tailwind.config.js   # Configuração do Tailwind
├── package.json         # Metadados/dependências
└── package-lock.json    # Lockfile npm
```

## Como rodar o projeto
```bash
npm install
```
Depois abra `index.html` no navegador.

## Variáveis de ambiente
Este projeto não utiliza variáveis de ambiente atualmente.

## Scripts disponíveis
Não há scripts npm configurados no `package.json` no momento.

## Melhorias futuras
- Configurar script npm para build/watch do Tailwind.
- Adicionar carrinho e finalização de pedido.
- Integrar envio de pedidos via WhatsApp ou API.

## Autor
Rafael Aniceto da Silva do Nascimento
