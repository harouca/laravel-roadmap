# Guia de estilo

Este guia define o padrão editorial do Laravel Roadmap. Ele deve ser aplicado aos capítulos, exemplos, laboratórios e documentos sobre versões.

## Linguagem

- Escreva todo conteúdo didático em português brasileiro.
- Use **Controller**, nunca “controlador”, ao tratar do componente do Laravel.
- Preserve em inglês os nomes oficiais de recursos, classes, métodos, arquivos e comandos.
- Explique siglas e termos técnicos na primeira ocorrência quando eles ainda não tiverem sido apresentados.
- Explique o porquê de uma decisão, não apenas como executá-la.

## Comandos e código

- Escreva comandos em blocos de código com a linguagem `bash`.
- Identifique a linguagem dos demais blocos sempre que possível, como `php`, `sql` ou `json`.
- Mostre apenas o código necessário para o conceito atual.
- Informe o diretório em que um comando deve ser executado quando isso não estiver claro pelo contexto.
- Não apresente comandos destrutivos sem explicar seus efeitos e cuidados.

## Diagramas

- Use diagramas Mermaid quando relações, fluxos, sequências ou estruturas ficarem mais claras visualmente.
- Não use diagramas apenas como decoração; texto curto continua preferível para ideias simples.
- Inclua uma explicação textual que permita compreender o ponto principal mesmo sem renderizar o diagrama.

## Estrutura dos capítulos

Cada capítulo deve seguir a progressão definida em `AGENTS.md` e terminar, nesta ordem, com:

1. um resumo dos conceitos essenciais;
2. exercícios que permitam verificar e aplicar o aprendizado.

Quando fizer sentido, inclua pré-requisitos, funcionamento interno, erros comuns, boas práticas e checklist.

## Domínio dos exemplos

- Use o sistema de gestão ambulatorial como domínio principal.
- Prefira exemplos envolvendo Paciente, Atendimento, Prontuário, Receita, Médico, Enfermeiro ou Usuário.
- Use outro domínio somente quando ele tornar o conceito claramente mais fácil de entender, explicando a escolha.

## Responsabilidade de cada diretório

- `docs/` **explica** um assunto de maneira progressiva e serve como referência.
- `examples/` **mostra** um conceito isolado com o mínimo de contexto necessário.
- `labs/` **faz o estudante praticar**, com objetivo, tarefas e critérios de conclusão.
- `project/` **integra** o aprendizado em uma aplicação Laravel progressiva.
- `versions/` registra **somente mudanças específicas de cada versão** do Laravel.

Um mesmo tema pode aparecer em mais de um diretório, desde que cumpra funções diferentes e tenha referências cruzadas úteis.
