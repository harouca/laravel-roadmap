# Glossário

Este documento define a estrutura do futuro glossário do Laravel Roadmap. Nesta
etapa, ele não contém verbetes.

## Objetivo

O glossário deverá oferecer definições curtas e consistentes para termos usados
ao longo do projeto, ajudando o leitor a recuperar conceitos sem duplicar as
explicações completas dos capítulos.

Ele funcionará como índice de consulta e ponto de conexão entre capítulos,
exemplos, laboratórios e referências relacionadas. Não deverá substituir a
progressão pedagógica nem introduzir conteúdo técnico ainda não desenvolvido.

## Organização alfabética

Os verbetes serão organizados pelo termo principal em ordem alfabética.

Se o volume de conteúdo justificar a divisão por letras, os índices alfabéticos
somente deverão ser criados quando possuírem verbetes reais. Não criar seções
vazias antecipadamente.

Termos conhecidos por mais de um nome deverão possuir um verbete principal. As
formas alternativas poderão apontar para ele por meio de referências cruzadas.

## Convenções de escrita

- Escrever as definições em português brasileiro.
- Preservar nomes técnicos oficiais em inglês quando essa for a forma utilizada
  pela tecnologia.
- Usar **Controller**, nunca “controlador”, para o componente do Laravel.
- Apresentar a forma por extenso antes de uma sigla quando necessário.
- Preferir definições diretas, precisas e adequadas ao público-alvo.
- Explicar apenas o contexto mínimo necessário para identificar o conceito.
- Evitar opiniões, analogias extensas e exemplos que pertençam a um capítulo.
- Não atribuir um comportamento ao Laravel 13 sem confirmação oficial.
- Diferenciar termos gerais de particularidades de uma versão.

## Formato de cada verbete

Cada verbete deverá seguir este modelo, incluindo apenas os campos aplicáveis:

```markdown
### Termo

**Categoria:** categoria conceitual do termo.

Definição curta e independente.

**Também conhecido como:** nomes alternativos ou siglas.

**Consulte:** links para os capítulos que explicam o conceito.

**Relacionado a:** links para outros verbetes relacionados.

**Referências:** fontes primárias ou documentação oficial pertinente.

**Observação de versão:** diferença confirmada e link para o arquivo em
`versions/`.
```

Campos sem conteúdo deverão ser omitidos, não deixados vazios. A definição deve
continuar compreensível mesmo quando os campos complementares não forem usados.

## Links cruzados para capítulos

O campo `Consulte` deverá apontar para o capítulo que desenvolve o conceito. Um
verbete poderá apontar para mais de um capítulo quando cada um tratar uma
responsabilidade diferente.

Somente criar links para arquivos existentes. Quando o capítulo ainda estiver
planejado, aguardar sua publicação em vez de registrar um destino futuro.

Capítulos poderão apontar para verbetes quando a definição curta ajudar a
consulta, mas a primeira explicação necessária ao aprendizado deverá permanecer
no próprio capítulo.

## Referências relacionadas

O glossário poderá relacionar:

- documentação oficial;
- especificações e padrões técnicos;
- capítulos do livro;
- exemplos e laboratórios existentes;
- outros verbetes;
- registros específicos de versão.

Dar preferência a fontes primárias. Referências deverão apoiar diretamente a
definição ou a observação à qual estão associadas.

## Observações sobre termos específicos de versões

Conceitos gerais deverão possuir definições independentes da versão do Laravel.
Quando o significado, a disponibilidade ou o comportamento de um termo depender
de uma versão, o verbete deverá incluir uma observação curta e apontar para
`versions/laravel-N.md`.

Detalhes de compatibilidade, mudanças, remoções e recursos exclusivos deverão
permanecer no arquivo da versão correspondente. O glossário apenas sinalizará a
diferença e oferecerá o link, evitando duplicação.

Nenhuma observação específica do Laravel 13 deverá ser adicionada sem confirmação
na documentação oficial.
