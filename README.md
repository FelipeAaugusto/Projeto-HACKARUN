# SmartMall AI — projeto consolidado

Este repositório reúne uma cópia consultável do trabalho publicado pela organização [SmartMall-AI](https://github.com/SmartMall-AI): documentação, aplicação web e API. Ele facilita a leitura conjunta e a apresentação; os repositórios da organização continuam sendo as fontes oficiais de desenvolvimento.

## Demonstração e materiais

- [Demonstração online](https://smartmall-ai-demo.vercel.app)
- [API interativa](https://smartmall-ai-demo-api-8mez.onrender.com/docs)
- [Vídeo de referência da ideia de transcrição de mensagens de rádio](https://www.youtube.com/shorts/nIa-9M6grfo?si=IiV3afbBTyGLgbxB)
- [Planejamento técnico inicial (PDF)](docs/planejamento_tecnico_inicial.pdf)
- [Documentação consolidada](documentacao/README.md)
- [Registro das fontes e revisões copiadas](ORIGENS.md)

A demonstração usa contas e dados fictícios compartilhados, e a IA aparece em modo simulado. Perfis não implementam autenticação nem autorização reais. A tela de rádio atual registra texto digitado localmente; não captura nem transcreve áudio. O vídeo é uma referência de produto para explorar essa possibilidade, não uma funcionalidade já entregue.

## Estrutura

| Pasta | Conteúdo |
| --- | --- |
| [`frontend/`](frontend/) | React, TypeScript, Vite, telas e cliente da API |
| [`backend/`](backend/) | FastAPI, PostgreSQL, migrações e endpoints |
| [`documentacao/`](documentacao/) | Escopo, arquitetura, contrato da API, implantação, validação e backlog |
| [`organizacao/`](organizacao/) | Índice e links dos repositórios oficiais |
| [`docs/`](docs/) | Planejamento técnico inicial em PDF, mantido do repositório de destino |

## Executar localmente

Use os guias completos em [`backend/README.md`](backend/README.md) e [`frontend/README.md`](frontend/README.md). Em resumo, inicie PostgreSQL e a API na porta `8000`, configure `VITE_API_BASE_URL=http://localhost:8000/api/v1` no frontend e depois rode `npm ci` e `npm run dev` na pasta `frontend/`. Nunca versione arquivos `.env` ou chaves de provedores.

## Fontes canônicas

- [Organização SmartMall-AI](https://github.com/SmartMall-AI)
- [Frontend oficial](https://github.com/SmartMall-AI/fe-smartmall-ai)
- [Backend oficial](https://github.com/SmartMall-AI/be-smartmall-ai)
- [Documentação oficial](https://github.com/SmartMall-AI/docs-smartmall-ai)
- [Repositório índice oficial](https://github.com/SmartMall-AI/Hackarun-SmartMall)

A cópia consolidada não compartilha o histórico Git dos repositórios separados e não substitui esses repositórios. Para contribuir com a aplicação, abra alterações no repositório oficial responsável.
