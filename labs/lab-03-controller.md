# Laboratório 03 — Controller

## Objetivo

Transferir a resposta da rota de pacientes para um Controller e compreender por que essa separação ajuda a aplicação a crescer.

## Pré-requisitos

- aplicação Laravel 13 funcional em `project/`;
- conclusão do [Laboratório 02](lab-02-routes.md).

## Cenário do ambulatório

A área de pacientes terá novas regras e fontes de dados. Manter toda a lógica diretamente no arquivo de rotas dificultaria a leitura e a evolução do sistema. Um Controller dará um local claro para coordenar essa requisição.

## Atividades

1. Entre no diretório da aplicação e consulte a ajuda do gerador de Controllers:

   ```bash
   cd project
   php artisan help make:controller
   ```

2. Crie `PatientController` com o Artisan:

   ```bash
   php artisan make:controller PatientController
   ```

3. Adicione ao Controller um método `index` que retorne o texto `Lista de pacientes`.
4. Atualize a rota `GET /pacientes` para chamar o método `index`.
5. Inspecione o registro da rota:

   ```bash
   php artisan route:list
   ```

6. Acesse novamente `/pacientes` e confirme que a resposta foi preservada.
7. Explique por que mover a ação para um Controller melhora a organização, mesmo que o exemplo ainda seja pequeno.

## Critérios de conclusão

- `PatientController` foi criado no local convencional da aplicação.
- A rota referencia o método `index` do Controller.
- A resposta esperada continua funcionando.
- Você consegue justificar a separação entre rota e Controller.
