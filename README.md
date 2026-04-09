# Bóris Projetos

Base pública separada para projetos especiais do Bóris.

## Estrutura atual

- `index.html`: hub público de projetos
- `styles.css`: identidade visual do hub
- `assets/`: ativos compartilhados do domínio
- `enap/`: primeiro projeto publicado

## Hierarquia pensada

- `projetos.euboris.com.br/`
- `projetos.euboris.com.br/enap`

## Link provisório publicado

- `https://boris-tools-boris-projetos.valwa8.easypanel.host/`

## Como servir localmente

```bash
cd /Users/eu.rochamateus/Documents/Codex/AgentOS/spaces/boris/areas/produto/workspaces/boris-projetos
python3 -m http.server 8088
```

## Deploy com Docker

Este repositório já inclui:

- `Dockerfile`
- `.dockerignore`

Para plataformas como Easypanel, basta selecionar a opção `Dockerfile`.
