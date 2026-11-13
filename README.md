# 🚀 SmartMall AI

Plataforma inteligente para gestão de ocorrências e infraestrutura de shopping centers.

## 📌 Sobre o Projeto
O **SmartMall AI** é uma solução proposta para o Hackathon com o objetivo de centralizar a comunicação de problemas operacionais em shopping centers. A plataforma utiliza Inteligência Artificial Generativa para classificar, priorizar e sugerir encaminhamentos para as ocorrências, além de organizar as equipes de manutenção e acompanhar a resolução dos chamados.

## 📄 Primeira Entrega: Planejamento Técnico Inicial
Toda a documentação de planejamento exigida pelo edital (estrutura de telas, arquitetura, linguagens, tecnologias e a prática sorteada) está disponível na pasta `docs` deste repositório.

👉 **[Clique aqui para ler o documento completo de Planejamento Técnico](docs/planejamento_tecnico_inicial.pdf)**
*(Nota: Se estiver visualizando o formato Word, acesse a pasta `docs` no repositório).*

## 🛠️ Stack Tecnológica Proposta
- **Backend:** Python (FastAPI ou Flask)
- **Frontend:** HTML, Jinja2 (ou React, dependendo da versão final do MVP)
- **Banco de Dados:** PostgreSQL (com SQLAlchemy)
- **Inteligência Artificial:** API de LLM (Modelo Generativo)
- **Padrão de Arquitetura:** Monólito modular com uso do padrão *Transactional Outbox* para resiliência.

## 🎯 Prática Sorteada
**Validação com Usuários:** O projeto prevê ciclos de testes com perfis representativos da operação de um shopping (gestores, técnicos e lojistas) para validar a usabilidade da interface e a utilidade das sugestões geradas pela IA.