---
tipo: projeto
status: ativo
projeto: Sistema-Maestro
area: desenvolvimento-pessoal
sensivel: false
atualizado: 2026-10-05
---
# Sistema Maestro

## Resumo
Agente principal que conhece o Kaká, gerencia este vault e delega tarefas a subagentes. Copiloto pessoal tecnológico.

## Metas
- Rodar em servidor ("sempre online").
- Integração com WhatsApp para enviar mensagens ao Kaká.

## Contexto
- Sistema de desenvolvimento com Claude Code: skills, subagentes, hooks e workflows, para projetos da Plena e da Lottiar.
- 13 peças, em ordem de implementação: commit, hook de formatação, clarifica, testar, escrever-claude-md, deploy, explorador, revisor, debugger, design, dev-frontend, dev-backend, planejar.
- 3 conjuntos de skills:
  - desenvolvimento
  - campanha/Lottiar: prospecta, fagulha, molde, regua
  - negociação/Plena: contratos-plena, propostas-plena
- A skill de commit usa Conventional Commits e mostra a mensagem para aprovação antes de commitar.
- Preferência: revisar cada fase antes da próxima, sem encadeamento automático.

## Decisões em aberto
- Antes: dev-backend e dev-frontend em paralelo sobre contrato de API, **sem orquestrador**. Agora: agente Dev como "admin" que invoca especialistas. [PREENCHER: qual modelo vale]

## Próximo passo
[PREENCHER]

Fonte: informado pelo Kaká (conversas com o Claude, ago–out/2026).