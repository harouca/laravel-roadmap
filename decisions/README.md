# Registro de decisões

Este diretório registra por que decisões editoriais, pedagógicas, técnicas ou
arquiteturais importantes foram tomadas no Laravel Roadmap.

O registro preserva contexto, alternativas e consequências. Ele não substitui o
estado atual da documentação: quando uma decisão alterar uma regra, os documentos
afetados também deverão ser atualizados.

## Quando registrar uma decisão

Crie um registro quando a escolha:

- afetar a identidade ou a direção do projeto;
- modificar a arquitetura do livro ou do Projeto Integrador;
- estabelecer uma convenção com impacto amplo;
- envolver trade-offs que futuros colaboradores precisarão compreender;
- for difícil ou custosa de reverter.

Não registre preferências triviais nem crie arquivos para decisões que ainda não
foram discutidas.

## Convenção

- Use `NNNN-titulo-descritivo.md`.
- Numere os registros sequencialmente com quatro dígitos.
- Use o modelo em [`templates/decision-template.md`](../templates/decision-template.md).
- Preserve registros aceitos; se a direção mudar, marque o anterior como
  substituído e crie uma nova decisão.
- Atualize o `CHANGELOG.md` quando a decisão causar mudança relevante.

## Decisões registradas

1. [Visão e missão do projeto](0001-project-vision.md) — aceita.
