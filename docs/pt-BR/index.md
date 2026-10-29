# Catálogo de documentação: payment-reconciliation-lab

[Introdução do projeto](../../README.pt-BR.md) | [Outro idioma](../en/index.md)

Percurso: propósito/setup → arquitetura/contratos → segurança/falhas → testes/evidência → operações. Na biblioteca: catálogo/dossiê → entrevista por projeto → fundamentos → falhas. Marcos/refactors/handoff históricos descrevem datas originais; revisão/checklist explica escopo atual.

## architecture

Componentes, fluxos e fronteiras implementadas.

- [Arquitetura e domínio](../pt-br/architecture/overview.md)
- [Escopo e estado da implementação](../pt-br/architecture/roadmap.md)

## adr

Decisões e consequências; IDs/histórico preservados.

- [Decisões de Arquitetura e Trade-offs](../pt-br/adr/architecture-decisions.md)

## guides

Setup, pré-requisitos e procedimentos de leitura.

- [Instalação e execução](../pt-br/guides/setup.md)
- [Ferramentas e versões](../pt-br/guides/toolchain.md)

## testing

Estratégia, inventários e evidências datadas.

- [Testes](../pt-br/testing/strategy.md)
- [Verificação da reestruturação — 2026-10-05](../../../engineering-library/docs/pt-br/projects/engineering-library/docs/pt-br/testing/documentation.md)

## docker

Imagens, serviços, mounts e configuração local.

- [Desenvolvimento Docker e recuperação](../pt-br/docker/development.md)
- [Ambiente Docker de desenvolvimento](../pt-br/docker/runtime.md)

## database

Modelos, constraints, migrações e consistência.

- [Schema de catálogo e transição de domínio](../pt-br/database/catalog-and-transition.md)

## api

Contratos expostos e comportamento de clientes.

- [API e UI de catálogo implementadas](../pt-br/api/catalog-contract.md)

## operations

Diagnóstico, recuperação, checklists e registros históricos.

- [payment-reconciliation-lab: Checklist de conclusão do repositório](../pt-br/operations/completion-checklist.md)
- [Startup, implantação e fronteiras dos testes](../pt-br/operations/deployment-and-evidence.md)
- [Relatório da reestruturação Aurora Bakery](../pt-br/operations/historical-refactor-report.md)

## security

Autenticação, autorização, dados e recursos.

- [Segurança da API de leitura e futuras fronteiras de pagamento](../pt-br/security/read-api-boundaries.md)

Aplicabilidade e omissões estão justificadas no [checklist](../pt-br/operations/completion-checklist.md). Não há categorias vazias.

## Roteiro prático de implementação e entrevista

[Acompanhe uma requisição, examine falhas e pratique respostas](../pt-br/guides/implementation-study.md).

- [Verificação da reestruturação — 2026-10-05](testing/verification.md)
