# Introdução ao Laravel

## Objetivo do capítulo

Apresentar o Laravel, explicar onde ele se encaixa no desenvolvimento web com PHP e preparar o vocabulário usado nos próximos capítulos.

## O que é Laravel?

Laravel é um framework para desenvolvimento de aplicações web em PHP. Um framework fornece uma estrutura, convenções e ferramentas reutilizáveis para resolver tarefas comuns, como receber requisições HTTP, acessar bancos de dados, validar dados, autenticar usuários e executar testes.

Em vez de definir toda a organização de uma aplicação do zero, a equipe parte de uma base conhecida. Isso tende a tornar o código mais previsível e facilita a colaboração.

## A arquitetura em alto nível

Uma aplicação web recebe uma requisição, decide como tratá-la e devolve uma resposta. No Laravel, esse fluxo costuma envolver:

1. uma **rota**, que relaciona uma URL e um método HTTP a uma ação;
2. um **Controller**, que coordena a ação quando necessário;
3. uma camada de dados, frequentemente representada por **models**;
4. uma **view** ou outra forma de resposta, como JSON.

Esses elementos serão estudados individualmente e aplicados no projeto progressivo.

## Conhecimentos recomendados

Para aproveitar melhor o roadmap, é útil conhecer:

- sintaxe básica de PHP;
- orientação a objetos;
- HTML e noções de CSS;
- fundamentos de HTTP;
- uso básico do terminal;
- conceitos iniciais de banco de dados e SQL;
- Git para controle de versão.

Não é necessário dominar todos esses tópicos. Quando um conceito for essencial, o material indicará o contexto necessário.

## Organização deste estudo

Os capítulos em `docs/` formam a referência principal, `examples/` mostra conceitos isolados e `labs/` orienta a prática. Uma aplicação completa crescerá dentro de `project/`, enquanto `versions/` registrará apenas diferenças entre versões do Laravel. Assim, será possível entender, observar, praticar e integrar cada conceito.

## Próximo passo

Antes de criar a aplicação, conheça a [estrutura típica de um projeto Laravel](02-estrutura-do-laravel.md).

## Resumo

Laravel oferece estrutura, convenções e ferramentas para desenvolver aplicações web em PHP. Neste repositório, a teoria, os exemplos isolados, a prática orientada e a aplicação progressiva possuem espaços distintos para favorecer um aprendizado consistente.

## Exercícios

1. Descreva com suas palavras o papel de uma rota, de um Controller, de um model e de uma view.
2. Esboce o fluxo de uma requisição para consultar um Paciente no sistema ambulatorial.
3. Explique por que separar teoria, exemplos, laboratórios e projeto pode ajudar no aprendizado.
