# Laboratório 02 — Rotas

## Objetivo

Praticar a criação e a inspeção de uma rota simples para a área de pacientes do sistema ambulatorial.

## Pré-requisitos

- aplicação Laravel 13 funcional em `project/`;
- conhecimento introdutório de requisições HTTP;
- conclusão do [Laboratório 01](lab-01-artisan.md).

## Cenário do ambulatório

O sistema precisa oferecer uma página inicial para a futura área de pacientes. Neste laboratório, a resposta será simples para manter o foco no funcionamento da rota.

## Atividades

1. Abra o arquivo de rotas web da aplicação.
2. Crie uma rota `GET` para `/pacientes` que retorne temporariamente o texto `Lista de pacientes`.
3. Liste as rotas registradas:

   ```bash
   cd project
   php artisan route:list
   ```

4. Confirme na saída o método HTTP, o caminho e a ação da nova rota.
5. Acesse `/pacientes` no ambiente local e verifique a resposta.
6. Explique por que `GET` é adequado para consultar uma lista e por que não deve alterar dados.

## Critérios de conclusão

- A rota responde no caminho esperado.
- `php artisan route:list` exibe a rota criada.
- A escolha do método HTTP foi justificada.
- A atividade não adicionou regras de negócio à definição da rota.
