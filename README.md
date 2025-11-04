# Página de Contato

Uma página simples de contato em HTML/CSS para uso local ou hospedagem em servidor Apache (XAMPP). Este pequeno projeto contém um formulário estático que envia para uma página de confirmação (`enviado.html`) e estilos básicos em `css/styles.css`.

## Visão geral

- Objetivo: fornecer uma página de contato leve e fácil de personalizar para sites estáticos.
- Tecnologias: HTML5, CSS puro.
- Uso típico: páginas institucionais, portfólios ou como base para integrar com um backend ou serviço de formulário.

## Estrutura do projeto

```
pagina-contato/
├── index.html        # Página principal com o formulário de contato
├── enviado.html      # Página de confirmação (após envio)
├── css/
│   └── styles.css    # Estilos da página
└── img/              # Imagens usadas no projeto (logo, ícones, etc.)
```

## Pré-requisitos

- Para abrir localmente: qualquer navegador moderno (Chrome, Edge, Firefox, etc.).
- Para testar via servidor local (recomendado ao usar `action` em formulários apontando para backend PHP): XAMPP instalado e em execução.

## Como executar (duas opções)

1) Abrir direto no navegador

- Abra `index.html` diretamente no navegador (arrastar o arquivo para a janela do navegador ou usar "Abrir arquivo").

2) Usando XAMPP / Apache (recomendado se você pretende integrar com backend)

- Copie a pasta `pagina-contato` para `C:\xampp\htdocs` (se ainda não estiver lá).
- Inicie o Apache pelo painel do XAMPP.
- Abra no navegador: http://localhost/pagina-contato/
