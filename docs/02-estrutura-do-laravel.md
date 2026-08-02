# Estrutura do Laravel

## Objetivo do capítulo

Reconhecer os principais diretórios e arquivos de uma aplicação Laravel. A pasta `project/` ainda está vazia nesta etapa; a estrutura descrita aqui será criada quando o framework for instalado.

## Visão geral

Uma instalação padrão do Laravel separa responsabilidades em diretórios conhecidos:

```text
app/          Código principal da aplicação
bootstrap/    Inicialização do framework e arquivos de cache
config/       Arquivos de configuração
database/     Migrations, factories e seeders
public/       Ponto de entrada público e arquivos acessíveis pelo navegador
resources/    Views e recursos-fonte do frontend
routes/       Definição das rotas
storage/      Logs, cache e arquivos gerados pela aplicação
tests/        Testes automatizados
vendor/       Dependências PHP instaladas pelo Composer
```

Alguns detalhes podem variar entre versões do framework. Ao instalar o Laravel, a própria estrutura gerada será a referência para a versão usada neste repositório.

## Diretórios principais

### `app/`

Concentra grande parte do código da aplicação. Controllers, models e outras classes de domínio costumam ficar aqui, organizados em subdiretórios.

### `routes/`

Contém os pontos de entrada da aplicação. Rotas web e de console são separadas por finalidade. Dependendo da versão e das opções instaladas, outros arquivos de rota podem existir.

### `resources/`

Armazena templates Blade e arquivos-fonte relacionados à interface. Esses recursos podem precisar de um processo de compilação antes de serem publicados.

### `database/`

Reúne arquivos que descrevem e preparam os dados da aplicação:

- **migrations** versionam alterações na estrutura do banco;
- **factories** produzem dados de teste;
- **seeders** inserem dados iniciais ou demonstrativos.

### `public/`

É o diretório que deve ser exposto pelo servidor web. Seu `index.php` recebe as requisições destinadas à aplicação.

### `storage/`

Guarda arquivos produzidos durante a execução, como logs, sessões, cache e views compiladas. A aplicação precisa de permissão de escrita nos locais apropriados.

## Arquivos importantes

- `.env`: configurações locais e informações sensíveis; não deve ser versionado.
- `.env.example`: modelo versionado das variáveis necessárias.
- `artisan`: entrada da ferramenta de linha de comando do Laravel.
- `composer.json`: dependências PHP e metadados do projeto.
- `package.json`: dependências e scripts do ecossistema JavaScript, quando utilizados.

## Uma distinção importante

Neste repositório, `docs/`, `examples/` e `assets/` pertencem ao material educacional. A instalação real do framework ficará dentro de `project/`. Portanto, a raiz do repositório não será a raiz da aplicação Laravel.

## Próximo passo

Conheça o [PHP Artisan](03-php-artisan.md), a interface de linha de comando usada para interagir com uma aplicação Laravel.

## Resumo

A estrutura padrão separa código, rotas, configurações, dados, recursos, arquivos públicos, armazenamento e testes. Conhecer a responsabilidade de cada diretório reduz decisões arbitrárias e torna mais fácil localizar o que precisa ser alterado.

## Exercícios

1. Em qual diretório você procuraria uma rota da área de pacientes? Justifique.
2. Explique a diferença entre `resources/`, `public/` e `storage/`.
3. Indique onde seriam encontrados uma migration de pacientes e o `PatientController`.
