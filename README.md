# HIDDENIA — OSONE

Projeto experimental de assistente digital multimodal, com interface web e serviços de integração.

## Escopo

- Interação por texto e voz.
- Workspace de código, documentos e criação de conteúdo.
- Memória local e pesquisa contextual em documentos.
- Interfaces de integração com mapas, serviços de comunicação e transmissões ao vivo.

As funcionalidades estão em desenvolvimento e podem depender de configurações e serviços externos.

## Tecnologias

React, TypeScript, Vite, Node.js, Express, Firebase, WebSocket e Gemini.

## Desenvolvimento local

```bash
git clone https://github.com/Adalberto069/HIDDENIA.git
cd HIDDENIA
npm install
```

Configure as variáveis de ambiente conforme [ .env.example](.env.example), sem incluir chaves privadas no controle de versão.

```bash
npm run dev
npm run lint
npm run build
```

## Estrutura

| Diretório | Finalidade |
| --- | --- |
| src/components | Componentes da interface |
| src/services | Integrações externas |
| src/lib | Utilitários, áudio e memória |
| api | Entrada da API |
| src/documentos_osone | Documentação conceitual |

**Status:** projeto experimental.
