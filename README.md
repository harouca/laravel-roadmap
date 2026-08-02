# Laravel Roadmap

O **Laravel Roadmap** é um framework aberto de aprendizagem em português
brasileiro. Ele usa o Laravel 13 como versão técnica de referência para ensinar
desenvolvimento de aplicações, Engenharia de Software e uso profissional de
Inteligência Artificial.

O projeto combina:

1. um roadmap progressivo, do básico ao avançado;
2. documentação técnica e um livro de referência;
3. laboratórios, exercícios e exemplos isolados;
4. uma aplicação Laravel construída progressivamente;
5. práticas de Engenharia de Software, arquitetura e fluxo profissional com Git;
6. uma metodologia para desenvolvimento assistido por IA.

A IA é uma camada transversal do roadmap, não um assunto isolado. Ela deve
ajudar a investigar, implementar, revisar e comparar soluções, sem transferir à
ferramenta a responsabilidade técnica. A filosofia central é:

> **Nunca aceite uma resposta da IA sem compreendê-la.**

A IA amplia a produtividade. O conhecimento, as decisões e a responsabilidade
continuam pertencendo ao desenvolvedor.

O conteúdo está em desenvolvimento. Neste estágio, o repositório contém a
fundação editorial, capítulos introdutórios e laboratórios planejados. A
aplicação Laravel ainda não foi instalada em `project/`.

## Público-alvo

O material é destinado a pessoas com conhecimentos básicos de PHP e Laravel que
desejam avançar em orientação a objetos, arquitetura e desenvolvimento de
aplicações. Também atende quem deseja incorporar IA ao fluxo de trabalho sem
abrir mão de entendimento, revisão crítica e validação. Os conceitos são
apresentados progressivamente, sem pressupor domínio avançado do framework.

## Tecnologias de referência

- Laravel 13;
- uma versão do PHP compatível com o Laravel 13;
- MySQL;
- Docker para o ambiente de desenvolvimento;
- Apache ou Nginx para produção.

Conceitos gerais são documentados sem vínculo desnecessário com uma versão.
Comportamentos específicos da versão de referência pertencem ao documento
[Laravel 13](versions/laravel-13.md) e devem ser confirmados na documentação
oficial antes de serem registrados.

## Como usar este repositório

- Leia o [VISION.md](VISION.md) para conhecer a missão e os compromissos do
  projeto.
- Leia o [AI_GUIDE.md](AI_GUIDE.md) antes de usar IA nas atividades do roadmap.
- Consulte o [PEDAGOGY.md](PEDAGOGY.md) para conhecer a metodologia de ensino e
  avaliação.
- Use o [GLOSSARY.md](GLOSSARY.md), quando houver verbetes publicados, como
  apoio à consulta de termos.
- Use `templates/` para iniciar novos conteúdos e consulte `decisions/` para
  compreender escolhas importantes do projeto.
- Consulte o [ROADMAP.md](ROADMAP.md) para acompanhar a ordem sugerida de estudos.
- Consulte o [MASTER_PLAN.md](MASTER_PLAN.md) para conhecer a arquitetura do
  livro e a evolução planejada da aplicação.
- Respeite as dependências indicadas em cada fase antes de avançar.
- Leia os capítulos em `docs/` na sequência numérica.
- Use `examples/` para exemplos pequenos e independentes dos capítulos.
- Consulte `ai/` para materiais complementares sobre prompts, revisões, estudos
  de caso, padrões e checklists.
- Resolva os exercícios orientados em `labs/` para praticar cada etapa.
- Acompanhe em `project/` a aplicação que será desenvolvida ao longo do roadmap.
- Consulte `versions/` para mudanças específicas da versão de referência.
- Consulte o [CHANGELOG.md](CHANGELOG.md) para conhecer a evolução do conteúdo.
- Consulte o [CONTRIBUTING.md](CONTRIBUTING.md) antes de propor alterações.

## Estrutura

```text
.
├── docs/           # Capítulos do material de estudo
├── examples/       # Exemplos práticos e isolados
├── labs/           # Atividades práticas orientadas
├── assets/         # Imagens e outros recursos dos documentos
├── ai/             # Materiais sobre uso crítico e profissional de IA
├── templates/      # Modelos para produção consistente de conteúdo
├── decisions/      # Contexto e justificativas de decisões importantes
├── versions/       # Mudanças específicas de cada versão do Laravel
├── project/        # Aplicação Laravel construída progressivamente
├── AI_GUIDE.md     # Princípios permanentes para uso de IA
├── PEDAGOGY.md     # Metodologia de ensino e avaliação
├── GLOSSARY.md     # Estrutura do glossário de termos
├── VISION.md       # Missão, visão e compromissos do projeto
├── MASTER_PLAN.md  # Arquitetura editorial e operacional
├── ROADMAP.md      # Ordem sugerida dos estudos
├── CONTRIBUTING.md # Convenções para contribuições
├── STYLE_GUIDE.md  # Padrão editorial do conteúdo
└── AGENTS.md       # Contexto permanente para agentes de IA
```

## Capítulos disponíveis

1. [Introdução](docs/01-introducao.md)
2. [Estrutura do Laravel](docs/02-estrutura-do-laravel.md)
3. [PHP Artisan](docs/03-php-artisan.md)

## Laboratórios disponíveis

1. [Artisan](labs/lab-01-artisan.md)
2. [Rotas](labs/lab-02-routes.md)
3. [Controller](labs/lab-03-controller.md)

## Contribuição

Antes de contribuir, leia o [CONTRIBUTING.md](CONTRIBUTING.md). Ele define como
escrever capítulos, criar exemplos, organizar exercícios, nomear arquivos e
registrar commits, evitando inconsistências conforme o projeto cresce.

Consulte também o [STYLE_GUIDE.md](STYLE_GUIDE.md) para o padrão editorial e o
[AGENTS.md](AGENTS.md) para as regras gerais do repositório. Novos conteúdos
devem respeitar a progressão pedagógica, usar português brasileiro e evitar
antecipar conceitos que ainda não foram apresentados.

## Licença

Distribuído sob a licença MIT. Consulte [LICENSE](LICENSE).
