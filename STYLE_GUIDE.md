# Guia de estilo

Este guia define o padrão editorial do Laravel Roadmap. Ele deve ser aplicado aos capítulos, exemplos, laboratórios e documentos sobre versões.

## Linguagem

- Escreva todo conteúdo didático em português brasileiro.
- Use **Controller**, nunca “controlador”, ao tratar do componente do Laravel.
- Preserve em inglês os nomes oficiais de recursos, classes, métodos, arquivos e comandos.
- Explique siglas e termos técnicos na primeira ocorrência quando eles ainda não tiverem sido apresentados.
- Explique o porquê de uma decisão, não apenas como executá-la.
- Ao apresentar um recurso, explique o que é, por que existe, quando usar e
  quando evitar.
- Escreva conceitos gerais de forma independente da versão. Registre diferenças
  confirmadas do Laravel 13 em `versions/laravel-13.md`.

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

Cada capítulo deve seguir a progressão definida em `AGENTS.md`. Use, quando aplicável, esta estrutura:

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

Termine sempre com um resumo dos conceitos essenciais e exercícios que permitam
verificar e aplicar o aprendizado. O checklist, quando necessário, deve fazer
parte do encerramento e não introduzir conceitos novos.

## IA em Ação

Todo capítulo técnico deve conter uma seção com o título exato `## IA em Ação`.
A seção deve ensinar revisão técnica de uma resposta assistida por IA, e não
apenas apresentar um prompt para ser copiado.

A seção deve conter sempre, nesta ordem:

1. **Objetivo do uso da IA:** qual problema delimitado será investigado e por que
   a ferramenta é adequada para apoiar essa atividade;
2. **Prompt utilizado:** o texto enviado, com contexto suficiente para ser
   compreendido e sem segredos ou dados pessoais;
3. **Resposta resumida da IA:** síntese fiel da proposta, sem reproduzir conteúdo
   extenso desnecessariamente;
4. **Análise crítica:** avaliação das premissas, escolhas, trade-offs e aderência
   ao que o capítulo ensinou;
5. **Possíveis problemas:** erros, riscos, omissões, alucinações, questões de
   segurança ou complexidade desnecessária;
6. **Melhorias sugeridas:** correções e refinamentos necessários, acompanhados de
   justificativa;
7. **Versão final recomendada:** solução compreendida e validada pelo autor,
   indicando o que mudou em relação à resposta original.

Sempre que possível, registre como a versão final foi validada, por exemplo com
documentação oficial, testes, análise estática ou verificação manual
reproduzível. Consultar outra IA não substitui evidência independente.

A seção não deve sugerir que a resposta da ferramenta é uma autoridade. Seu
propósito é demonstrar como um desenvolvedor experiente compreende, revisa,
valida e melhora uma proposta. Aplique também os princípios do `AI_GUIDE.md`.

## Notas, alertas e boas práticas

Use citações Markdown com um rótulo em negrito para destacar informação que não
deve ficar escondida no texto:

```markdown
> **Nota:** informação complementar útil para compreender o contexto.

> **Atenção:** risco de erro, perda de dados ou comportamento inesperado.

> **Boa prática:** recomendação aplicável, acompanhada de sua justificativa.
```

Não use alertas como decoração nem para repetir a frase anterior. Explique o
impacto concreto e, em instruções potencialmente destrutivas, indique como
reduzir o risco.

## Domínio dos exemplos

- Use o sistema de gestão ambulatorial como domínio principal.
- Prefira exemplos envolvendo Paciente, Atendimento, Prontuário, Receita, Médico, Enfermeiro ou Usuário.
- Use outro domínio somente quando ele tornar o conceito claramente mais fácil de entender, explicando a escolha.

## Responsabilidade de cada diretório

- `docs/` **explica** um assunto de maneira progressiva e serve como referência.
- `examples/` **mostra** um conceito isolado com o mínimo de contexto necessário.
- `labs/` **faz o estudante praticar**, com objetivo, tarefas e critérios de conclusão.
- `project/` **integra** o aprendizado em uma aplicação Laravel progressiva.
- `ai/` **registra** materiais complementares sobre uso crítico e profissional
  de IA, sem substituir a análise presente nos capítulos.
- `versions/` registra **somente mudanças específicas de cada versão** do Laravel.

Um mesmo tema pode aparecer em mais de um diretório, desde que cumpra funções diferentes e tenha referências cruzadas úteis.
