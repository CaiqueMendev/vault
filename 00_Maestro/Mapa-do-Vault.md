---
tipo: sistema
status: ativo
projeto:
area:
sensivel: false
atualizado: 2026-10-05
---
# Mapa do Vault

## Onde cada coisa vive
| Informação | Local |
|---|---|
| Quem é o Kaká | 00_Maestro/Perfil.md |
| Regras e permissões | 00_Maestro/Regras.md |
| Ferramentas | 00_Maestro/Ferramentas.md |
| Definição dos agentes | 00_Maestro/Agentes/ |
| Entrada rápida, ideias, propostas do Maestro | 01_Inbox/ |
| Projetos ativos e pausados | 02_Projetos/<Projeto>/ |
| Áreas contínuas | 03_Areas/<Area>.md |
| Conceitos | 04_Conhecimento/Conceitos/ |
| Referências (links, docs, artigos) | 04_Conhecimento/Referencias/ |
| Pessoas | 04_Conhecimento/Pessoas/ |
| Diário do Kaká (só ele escreve) | 05_Diario/ |
| Resumo diário do Maestro | 07_Logs/Diario-Maestro/ |
| Projetos concluídos | 06_Arquivo/ |
| Registros de delegação | 07_Logs/Delegacoes/ |
| Templates | _Templates/ |

## Como navegar
Perfil → Área → `_indice.md` do projeto → notas do projeto.
Cada `_indice.md` linka sua área. Cada nota de projeto linka seu `_indice.md`.

## Nomes de arquivo
- Projeto: pasta `Nome-Do-Projeto/` com `_indice.md`
- Diário: `AAAA-MM-DD.md`
- Delegação: `AAAA-MM-DD_HHMM_slug.md`
- Proposta do Maestro: `PROPOSTA_AAAA-MM-DD_slug.md`
- Pessoa: `Nome-Sobrenome.md`
- Resumo diário do Maestro: `07_Logs/Diario-Maestro/AAAA-MM-DD.md`

## Frontmatter
| Campo | Valores |
|---|---|
| tipo | projeto, area, conceito, pessoa, diario, log, sistema |
| status | ativo, pausado, concluido |
| projeto | nome do projeto (vazio se não se aplica) |
| area | plena-tecnologia, plena-lottiar, lottiar, desenvolvimento-pessoal |
| sensivel | true / false (true = nunca vai para subagentes) |
| atualizado | AAAA-MM-DD |

## Ciclo de vida
- Projeto concluído: `status: concluido` e pasta movida para 06_Arquivo/ (com aprovação).
- Itens da Inbox: processar e mover para o destino certo (com aprovação), ou arquivar.