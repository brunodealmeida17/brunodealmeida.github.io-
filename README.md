# Portfólio Bruno de Almeida - GitHub Pages

Este projeto é um portfólio pessoal em formato de mini-SPA usando apenas:

- HTML5
- CSS3
- JavaScript Vanilla

## Funcionalidades

- Navegação por seções sem recarregar a página
- Dashboard com contadores animados
- Timeline profissional interativa
- Skills dinâmicas com barra de progresso
- Projetos com modal
- Simulação de assistente IA usando JavaScript
- Alternância entre tema escuro e claro
- Layout responsivo

## Estrutura

```text
portfolio_dynamic/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Como testar localmente

Abra o arquivo `index.html` diretamente no navegador.

Ou, se preferir usar um servidor local:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Como publicar no GitHub Pages

1. Crie um repositório chamado:

```text
seu-usuario.github.io
```

2. Envie os arquivos para a branch principal:

```bash
git init
git add .
git commit -m "Create dynamic portfolio"
git branch -M main
git remote add origin https://github.com/seu-usuario/seu-usuario.github.io.git
git push -u origin main
```

3. Acesse:

```text

```

## Próximas melhorias sugeridas

- Adicionar foto profissional
- Criar versão em inglês e português
- Integrar com API Django
- Criar um backend para o assistente IA
- Usar OpenAI para responder perguntas sobre o currículo
- Adicionar projetos reais com links para GitHub
