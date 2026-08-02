# Laboratório 01 — Artisan

## Objetivo

Praticar a descoberta de comandos do Artisan e aprender a consultar a ajuda integrada antes de alterar uma aplicação.

## Pré-requisitos

- aplicação Laravel 13 criada em `project/`;
- PHP disponível no ambiente de desenvolvimento;
- leitura do capítulo [PHP Artisan](../docs/03-php-artisan.md).

> Este laboratório deverá ser executado quando a aplicação Laravel existir em `project/`. A ausência atual do arquivo `project/artisan` é intencional.

## Cenário do ambulatório

A equipe do sistema ambulatorial precisa descobrir quais ferramentas o Laravel oferece para criar e inspecionar componentes da aplicação, sem executar comandos desconhecidos às cegas.

## Atividades

1. Entre no diretório da aplicação:

   ```bash
   cd project
   ```

2. Consulte a versão do framework:

   ```bash
   php artisan --version
   ```

3. Liste os comandos disponíveis:

   ```bash
   php artisan list
   ```

4. Localize os grupos relacionados a rotas e geração de arquivos.
5. Consulte a ajuda do comando que lista as rotas:

   ```bash
   php artisan help route:list
   ```

6. Anote duas opções apresentadas pela ajuda e explique por que seriam úteis no sistema ambulatorial.

## Critérios de conclusão

- Você identificou a versão instalada.
- Você sabe listar os comandos disponíveis sem consultar fontes externas.
- Você consegue abrir a ajuda de um comando antes de executá-lo.
- Você explicou a utilidade de pelo menos duas opções de `route:list`.
