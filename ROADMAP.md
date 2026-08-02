# Roadmap de estudos

Este roadmap organiza o aprendizado do básico ao avançado. Um item marcado
indica que há conteúdo correspondente no repositório; não significa que a
aplicação progressiva já implementa o assunto. Os laboratórios existentes que
dependem da futura aplicação permanecem disponíveis, mas ainda não podem ser
executados.

> Novos capítulos devem ser criados somente quando seu conteúdo for desenvolvido.
> Os itens abaixo planejam a trilha sem antecipar arquivos vazios.

## Fase 1 — Fundamentos do framework

**Dependências:** conhecimentos básicos de PHP, HTTP, terminal e Git.

- [x] Entender a proposta do Laravel e os pré-requisitos de estudo.
- [x] Conhecer a estrutura típica de uma aplicação Laravel.
- [x] Compreender o papel do PHP Artisan.
- [ ] Revisar os fundamentos de orientação a objetos necessários para a trilha.

## Fase 2 — Ambiente e primeira aplicação

**Dependência:** Fase 1.

- [ ] Preparar PHP, Composer, MySQL e Docker para desenvolvimento.
- [ ] Criar a aplicação Laravel 13 em `project/`.
- [ ] Documentar a configuração por variáveis de ambiente.
- [ ] Executar a aplicação localmente.
- [ ] Executar e validar o [laboratório de Artisan](labs/lab-01-artisan.md).

## Fase 3 — Fluxo HTTP e interface

**Dependência:** aplicação funcional da Fase 2.

- [ ] Compreender requisições, respostas e ciclo de vida HTTP.
- [ ] Criar e nomear rotas.
- [ ] Organizar ações em Controllers.
- [ ] Criar views com Blade e layouts reutilizáveis.
- [ ] Trabalhar com formulários, validação e mensagens de erro.
- [ ] Executar os laboratórios de
  [rotas](labs/lab-02-routes.md) e
  [Controller](labs/lab-03-controller.md).

## Fase 4 — Persistência de dados

**Dependências:** fluxo HTTP e formulários da Fase 3; MySQL configurado.

- [ ] Compreender configuração e conexões de banco de dados.
- [ ] Criar e reverter migrations.
- [ ] Modelar Paciente, Atendimento e demais entidades com Eloquent.
- [ ] Implementar relacionamentos, factories e seeders.
- [ ] Construir o primeiro fluxo CRUD da aplicação ambulatorial.

## Fase 5 — Organização e regras da aplicação

**Dependência:** persistência de dados da Fase 4.

- [ ] Separar validação, autorização e regras de negócio.
- [ ] Compreender injeção de dependências e o service container.
- [ ] Aplicar eventos, listeners, filas e tarefas agendadas quando necessários.
- [ ] Avaliar padrões de arquitetura sem criar abstrações prematuras.

## Fase 6 — Segurança e qualidade

**Dependência:** fluxo funcional construído nas fases anteriores.

- [ ] Implementar autenticação e autorização.
- [ ] Tratar dados sensíveis, sessões e proteção contra vulnerabilidades comuns.
- [ ] Escrever testes de unidade e de funcionalidade.
- [ ] Usar ferramentas de análise estática e padronização de código.
- [ ] Medir e melhorar a confiabilidade dos fluxos principais.

## Fase 7 — Integrações e recursos avançados

**Dependências:** organização, segurança e testes das Fases 5 e 6.

- [ ] Projetar APIs e autenticação de clientes.
- [ ] Integrar serviços externos com tratamento de falhas.
- [ ] Trabalhar com cache, filas e processamento assíncrono.
- [ ] Observar logs, desempenho e comportamento da aplicação.

## Fase 8 — Produção e evolução

**Dependência:** aplicação testada e observável.

- [ ] Preparar configuração segura para produção.
- [ ] Publicar com Apache ou Nginx.
- [ ] Planejar migrations, filas, cache e tarefas agendadas no deploy.
- [ ] Definir estratégia de backup, monitoramento e recuperação.
- [ ] Atualizar versões do framework com apoio dos registros em `versions/`.
