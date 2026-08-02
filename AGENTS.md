# AGENTS.md

## Objetivo do projeto

Este repositório combina:

- roadmap de aprendizado;
- livro técnico sobre Laravel;
- laboratórios e exercícios;
- exemplos isolados;
- projeto Laravel progressivo;
- metodologia de desenvolvimento profissional assistido por Inteligência
  Artificial.

A IA é uma camada transversal do roadmap, não um capítulo isolado. O projeto
deve ensinar a compreender, revisar, validar e evoluir soluções assistidas por IA.
O princípio permanente é: **nunca aceite uma resposta da IA sem compreendê-la**.

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
- `ai/`: prompts, revisões, estudos de caso, padrões e checklists sobre IA;
- `templates/`: modelos para capítulos, laboratórios, exemplos, decisões e
  estudos de caso;
- `decisions/`: registros de decisões importantes e suas justificativas;
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
9. IA em Ação;
10. resumo;
11. exercícios;
12. checklist.

Não criar capítulos vazios antecipadamente.

Aplicar as regras de `STYLE_GUIDE.md` a todo conteúdo novo ou alterado. Em especial:

- usar “Controller”, nunca “controlador”;
- apresentar comandos em blocos de código;
- usar Mermaid quando um diagrama ajudar a compreensão;
- terminar capítulos com resumo e exercícios;
- explicar o porquê, não apenas o como.

Aplicar o `PEDAGOGY.md` ao planejar capítulos, exercícios, laboratórios,
checkpoints e incrementos do Projeto Integrador. Objetivos, prática e avaliação
devem permanecer alinhados.

Todo capítulo técnico deve incluir `## IA em Ação` conforme o
`STYLE_GUIDE.md`, contendo objetivo, prompt, resposta resumida, análise crítica,
possíveis problemas, melhorias sugeridas e versão final recomendada. O foco deve
ser a revisão técnica, não a cópia de prompts ou respostas.

Aplicar o `AI_GUIDE.md` a todo conteúdo que utilize IA. Nunca tratar uma resposta
da ferramenta como evidência suficiente; validar afirmações, código e decisões
com fontes e verificações adequadas.

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
- Não enviar dados pessoais, clínicos, proprietários ou sensíveis a ferramentas
  de IA.
- Não substituir conteúdo válido sem necessidade e registrar mudanças estruturais
  relevantes no `CHANGELOG.md`.
- Usar os arquivos em `templates/` ao criar novos conteúdos do tipo
  correspondente.
- Registrar em `decisions/` somente escolhas importantes, seguindo a convenção
  e o modelo definidos para esses registros.

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
