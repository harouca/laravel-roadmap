# PHP Artisan

## Objetivo do capítulo

Entender o papel do Artisan, reconhecer a forma dos comandos e aprender cuidados básicos antes de executá-los.

## O que é Artisan?

Artisan é a interface de linha de comando incluída no Laravel. O arquivo `artisan`, localizado na raiz da aplicação, inicializa o framework e disponibiliza comandos para desenvolvimento, manutenção e inspeção do sistema.

Como o Laravel ainda não foi instalado neste repositório, os comandos abaixo são apenas referências e ainda não devem ser executados em `project/`.

## Forma básica de uso

Dentro da raiz de uma aplicação Laravel, um comando segue este formato:

```bash
php artisan nome:do-comando
```

Para listar os comandos disponíveis:

```bash
php artisan list
```

Para consultar a ajuda de um comando específico:

```bash
php artisan help nome:do-comando
```

## Categorias comuns

O Artisan pode ser usado para:

- iniciar um servidor local de desenvolvimento;
- gerar classes como Controllers, models e migrations;
- executar migrations;
- limpar ou gerar caches;
- inspecionar rotas;
- executar tarefas agendadas e filas;
- abrir um ambiente interativo da aplicação.

Os comandos exatos e suas opções devem ser confirmados com `php artisan list` e `php artisan help`, pois podem variar conforme a versão do Laravel e os pacotes instalados.

## Comandos que alteram estado

Alguns comandos apenas exibem informações; outros criam arquivos, modificam o banco de dados, removem cache ou processam trabalhos. Antes de executar um comando:

1. leia sua ajuda;
2. confirme o ambiente atual;
3. entenda quais arquivos ou dados serão afetados;
4. mantenha um backup quando houver dados importantes.

## Artisan e este repositório

Quando a aplicação for criada, os comandos deverão ser executados dentro de `project/`:

```bash
cd project
php artisan list
```

Até lá, a ausência do arquivo `project/artisan` é intencional.

## Resumo

Neste ponto, você já conhece a proposta do framework, a estrutura típica de uma aplicação e sua principal ferramenta de terminal. A próxima etapa do roadmap será preparar o ambiente e criar a primeira aplicação em `project/`.

## Exercícios

1. Explique por que consultar `php artisan help` antes de usar um comando desconhecido é uma boa prática.
2. Liste três categorias de tarefas que o Artisan pode executar.
3. Quando a aplicação estiver instalada, conclua o [Laboratório 01 — Artisan](../labs/lab-01-artisan.md).
