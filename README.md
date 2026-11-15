# SmartMall AI — projeto consolidado

Este repositório reúne uma cópia consultável do trabalho publicado pela organização [SmartMall-AI](https://github.com/SmartMall-AI): documentação, aplicação web e API. Ele facilita a leitura conjunta e a apresentação; os repositórios da organização continuam sendo as fontes oficiais de desenvolvimento.

## Demonstração e materiais

- [Demonstração online](https://smartmall-ai-demo.vercel.app)
- [API interativa](https://smartmall-ai-demo-api-8mez.onrender.com/docs)
- [Formulário de validação com usuários](https://docs.google.com/forms/d/e/1FAIpQLSdP_wHxdIQcthQ3dqxtBPWOL9SlHGxBP92iavi1vdPOuyNAUw/viewform?usp=sharing&ouid=100468181742144616071)
- [Planilha de respostas da validação (acesso conforme permissões do Google)](https://docs.google.com/spreadsheets/d/11vCZ1sWJ0eIiD_oQW2EhgIHbg3YN8xo1q9WE409XX8c/edit?resourcekey=&gid=1361567321#gid=1361567321)
- [Vídeo de apresentação do projeto](https://youtube.com/shorts/nIa-9M6grfo?si=IiV3afbBTyGLgbxB)
- [Planejamento técnico inicial (PDF)](docs/planejamento_tecnico_inicial.pdf)
- [Documentação consolidada](documentacao/README.md)
- [Registro das fontes e revisões copiadas](ORIGENS.md)

A demonstração usa contas e dados fictícios compartilhados, e a IA aparece em modo simulado. Perfis não implementam autenticação nem autorização reais. A tela de rádio atual registra texto digitado localmente; não captura nem transcreve áudio. A transcrição de rádio continua sendo uma ideia futura.

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
