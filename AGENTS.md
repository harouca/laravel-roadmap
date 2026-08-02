# AGENTS.md

## Objetivo do projeto

Este repositório combina:

- roadmap de aprendizado;
- livro técnico sobre Laravel;
- laboratórios e exercícios;
- exemplos isolados;
- projeto Laravel progressivo.

## Idioma

Todo conteúdo didático deve ser escrito em português brasileiro.

## Público-alvo

Desenvolvedor com conhecimento básico de Laravel e PHP, ainda em processo de aprendizado de orientação a objetos e arquitetura de aplicações.

## Tecnologias de referência

- Laravel 13;
- versão do PHP compatível com o Laravel 13;
- MySQL;
- Docker para desenvolvimento;
- Apache ou Nginx em produção.

## Organização

- `docs/`: capítulos do livro;
- `examples/`: exemplos isolados;
- `labs/`: exercícios orientados para prática;
- `project/`: aplicação Laravel progressiva;
- `assets/`: imagens e diagramas;
- `versions/`: mudanças exclusivas de cada versão do Laravel.

## Regras editoriais

Cada capítulo deve conter, quando aplicável:

1. objetivos;
2. pré-requisitos;
3. conceitos;
4. funcionamento interno;
5. exemplo simples;
6. exemplo aplicado;
7. erros comuns;
8. boas práticas;
9. resumo;
10. exercícios;
11. checklist.

Não criar capítulos vazios antecipadamente.

Aplicar as regras de `STYLE_GUIDE.md` a todo conteúdo novo ou alterado. Em especial:

- usar “Controller”, nunca “controlador”;
- apresentar comandos em blocos de código;
- usar Mermaid quando um diagrama ajudar a compreensão;
- terminar capítulos com resumo e exercícios;
- explicar o porquê, não apenas o como.

Para cada recurso, explicar o que é, por que existe, quando usar e quando
evitar. A linguagem deve ser clara para quem possui apenas conhecimentos básicos
de PHP e Laravel.

Conceitos gerais devem permanecer independentes da versão do framework. Não
atribuir um comportamento ao Laravel 13 sem confirmação na documentação oficial.

Ao iniciar o suporte a uma nova versão principal, criar `versions/laravel-N.md`. Não misturar nesse arquivo conceitos gerais do framework.

## Restrições

- Preservar conteúdo útil e evitar arquivos duplicados.
- Não criar capítulos vazios ou arquivos apenas para antecipar assuntos futuros.
- Usar `.gitkeep` somente quando um diretório vazio precisar ser versionado.
- Não instalar ou recriar a aplicação Laravel sem solicitação explícita.
- Não incluir segredos, arquivos `.env` ou credenciais no repositório.
- Não substituir conteúdo válido sem necessidade e registrar mudanças estruturais
  relevantes no `CHANGELOG.md`.

## Projeto de referência

Os exemplos principais devem usar um sistema de gestão ambulatorial, com entidades como:

- Paciente;
- Atendimento;
- Prontuário;
- Receita;
- Médico;
- Enfermeiro;
- Usuário.

## Git

Usar commits claros, como:

- `docs: cria estrutura inicial do roadmap`
- `docs: adiciona capítulo sobre Artisan`
- `examples: adiciona exemplos de rotas`
- `labs: adiciona prática sobre Controllers`
- `project: implementa cadastro de pacientes`

Não executar commits ou pushes sem autorização explícita.
