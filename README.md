# Laravel Roadmap

O **Laravel Roadmap** é um repositório educacional em português brasileiro que
usa o Laravel 13 como versão técnica de referência e combina cinco objetivos:

1. oferecer uma trilha progressiva de estudos;
2. servir como livro de consulta sobre Laravel;
3. oferecer laboratórios e exercícios orientados;
4. reunir exemplos práticos e isolados;
5. construir uma aplicação Laravel de forma incremental, capítulo por capítulo.

O conteúdo está em desenvolvimento. Neste estágio, o repositório contém a
fundação editorial, capítulos introdutórios e laboratórios planejados. A
aplicação Laravel ainda não foi instalada em `project/`.

## Público-alvo

O material é destinado a pessoas com conhecimentos básicos de PHP e Laravel que
desejam avançar em orientação a objetos, arquitetura e desenvolvimento de
aplicações. Os conceitos são apresentados progressivamente, sem pressupor
domínio avançado do framework.

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

- Consulte o [ROADMAP.md](ROADMAP.md) para acompanhar a ordem sugerida de estudos.
- Respeite as dependências indicadas em cada fase antes de avançar.
- Leia os capítulos em `docs/` na sequência numérica.
- Use `examples/` para exemplos pequenos e independentes dos capítulos.
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
├── versions/       # Mudanças específicas de cada versão do Laravel
├── project/        # Aplicação Laravel construída progressivamente
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
