# Como contribuir

Obrigado por contribuir com o Laravel Roadmap. Este repositório é um material
didático progressivo; por isso, toda alteração deve considerar tanto a correção
técnica quanto a etapa de aprendizado do leitor.

## Antes de começar

Leia estes documentos:

- [README.md](README.md), para conhecer o objetivo e a estrutura do projeto;
- [ROADMAP.md](ROADMAP.md), para entender a sequência de estudos;
- [AGENTS.md](AGENTS.md), para consultar as regras do repositório;
- [STYLE_GUIDE.md](STYLE_GUIDE.md), para seguir o padrão editorial.

Antes de propor um conteúdo novo, verifique se ele pertence à etapa atual do
roadmap. Não crie capítulos vazios para assuntos futuros.

## Onde fazer cada contribuição

- `docs/`: capítulos progressivos e material de referência;
- `examples/`: exemplos pequenos e isolados;
- `labs/`: exercícios orientados, com objetivo e critérios de conclusão;
- `project/`: aplicação Laravel construída ao longo do aprendizado;
- `assets/`: imagens e diagramas usados pelo material;
- `versions/`: mudanças exclusivas de uma versão principal do Laravel.

Conceitos gerais do framework devem ficar nos capítulos correspondentes, não nos
arquivos de `versions/`.

## Como escrever capítulos

Escreva o conteúdo didático em português brasileiro e para pessoas que ainda
estão aprendendo orientação a objetos e arquitetura de aplicações. Explique o
motivo das decisões apresentadas, preserve os nomes oficiais da tecnologia e use
**Controller**, nunca “controlador”, ao se referir ao componente do Laravel.

Quando aplicável, um capítulo deve incluir:

1. objetivos;
2. pré-requisitos;
3. conceitos;
4. funcionamento interno;
5. exemplo simples;
6. exemplo aplicado;
7. erros comuns;
8. boas práticas;
9. resumo;
10. exercícios;
11. checklist.

Os exemplos principais devem utilizar o sistema de gestão ambulatorial e suas
entidades, como Paciente, Atendimento, Prontuário, Receita, Médico, Enfermeiro e
Usuário.

Cada capítulo deve desenvolver um assunto completo, respeitar os conhecimentos
apresentados anteriormente e terminar com as seções `Resumo` e `Exercícios`,
nessa ordem. Use exemplos simples para apresentar o conceito e exemplos do
sistema ambulatorial para demonstrar sua aplicação. Quando um fluxo ou uma
relação ficar mais claro visualmente, use Mermaid e também forneça uma explicação
textual.

Não copie para um capítulo uma explicação completa que já existe em outro.
Apresente apenas o contexto necessário e crie um link para o conteúdo de origem.

## Como criar exemplos

Um exemplo em `examples/` deve demonstrar um conceito isolado, conter apenas o
código necessário e poder ser compreendido sem depender de trechos ocultos. O
texto que acompanha o código deve explicar:

- qual conceito está sendo demonstrado;
- quais são os pré-requisitos;
- como executar ou observar o exemplo;
- qual resultado é esperado;
- como o exemplo se relaciona com o capítulo correspondente.

Prefira exemplos pequenos. Se forem necessários vários arquivos, agrupe-os em um
diretório próprio e inclua um `README.md` com as instruções. Não use
`examples/` para manter uma segunda aplicação completa; integrações progressivas
pertencem a `project/`.

Todo código deve ser compatível com as tecnologias de referência definidas em
`AGENTS.md`. Comandos devem aparecer em blocos `bash` e os demais blocos devem
identificar a linguagem sempre que possível.

## Convenção dos arquivos

Use nomes em letras minúsculas, sem espaços ou acentos, com palavras separadas
por hífen. Siga os padrões específicos de cada diretório:

- capítulos: `docs/NN-nome-do-capitulo.md`;
- laboratórios: `labs/lab-NN-nome-do-laboratorio.md`;
- versões: `versions/laravel-N.md`;
- exemplos de um arquivo: `examples/nome-do-conceito.ext`;
- exemplos com vários arquivos: `examples/nome-do-conceito/`;
- imagens e diagramas: `assets/nome-descritivo.ext`.

Em `NN`, use dois dígitos e preserve a ordem definida no roadmap. Em `N`, use o
número da versão principal do Laravel. Nomes exigidos por uma tecnologia, como
nomes de classes PHP e arquivos do Laravel, devem seguir a convenção oficial
dessa tecnologia.

Ao adicionar, remover ou renomear um capítulo, atualize os links e índices
afetados, especialmente `README.md` e `ROADMAP.md`.

## Organização dos exercícios

Os exercícios ao final de um capítulo verificam a compreensão do conteúdo
recém-apresentado. Organize-os em ordem crescente de dificuldade e combine,
quando possível:

1. uma questão de compreensão;
2. uma pequena alteração ou implementação;
3. uma aplicação no domínio ambulatorial.

Cada exercício deve informar claramente o que precisa ser produzido. Não exija
conceitos que ainda não tenham sido apresentados e evite instruções que revelem
toda a solução.

Atividades maiores e orientadas devem ficar em `labs/`. Cada laboratório deve
conter, nesta ordem quando aplicável:

1. objetivo;
2. pré-requisitos e link para o capítulo relacionado;
3. cenário do sistema ambulatorial;
4. atividades numeradas;
5. critérios de conclusão verificáveis.

Um laboratório deve poder ser concluído com o estado do projeto previsto para
aquela etapa do roadmap. Caso dependa de algo ainda não instalado, registre essa
condição explicitamente.

## Fluxo de contribuição

1. Parta de uma branch principal atualizada.
2. Crie uma branch curta e descritiva, como `docs/rotas` ou
   `labs/validacao-paciente`.
3. Faça mudanças pequenas e focadas em um único assunto.
4. Revise ortografia, links, comandos e exemplos de código.
5. Confirme que o conteúdo respeita a progressão do `ROADMAP.md`.
6. Atualize o `CHANGELOG.md` apenas quando a mudança for relevante para os
   leitores ou para a estrutura do projeto.
7. Abra um pull request explicando o objetivo e como a alteração foi validada.

Se houver código executável, rode os testes e as ferramentas de qualidade
disponíveis no diretório correspondente. Não inclua credenciais, arquivos de
ambiente locais, dependências geradas ou outros dados sensíveis.

## Critérios para concluir um capítulo

Um capítulo pode ser considerado concluído quando:

- possui objetivo claro e pré-requisitos quando necessários;
- explica o que é o conceito, por que existe, quando usar e quando evitar;
- respeita a ordem pedagógica e não depende de conteúdo ainda não apresentado;
- diferencia conceitos gerais de observações específicas do Laravel 13;
- confirma afirmações específicas de versão em documentação oficial;
- inclui exemplos tecnicamente coerentes e adequados ao nível do leitor;
- termina com resumo e exercícios que verificam os objetivos propostos;
- segue o `STYLE_GUIDE.md` e usa a terminologia definida pelo projeto;
- não contém links quebrados, comandos não explicados ou trechos incompletos;
- foi revisado quanto à clareza, correção técnica e ortografia.

Checklist não substitui revisão humana. Se um exemplo puder ser executado, a
revisão deve informar como ele foi testado e qual resultado foi obtido.

## Padrão de commits

Faça commits pequenos, relacionados a um único objetivo, e use mensagens no
formato `escopo: descrição`. Escreva a descrição em português, com letra inicial
minúscula e sem ponto final, seguindo formas como `adiciona`, `corrige`,
`atualiza`, `remove` ou `implementa`. Use como escopo o diretório ou a área
principal da mudança, como `docs`, `examples`, `labs`, `project`, `assets`,
`versions` ou `chore`.

Exemplos:

```text
docs: adiciona capítulo sobre Artisan
examples: adiciona exemplos de rotas
labs: adiciona prática sobre Controllers
project: implementa cadastro de pacientes
```

## Pull requests

O pull request deve informar:

- o problema ou objetivo da contribuição;
- os principais arquivos alterados;
- como a mudança foi revisada ou testada;
- imagens, quando houver alteração visual relevante.

Durante a revisão, confirme a correção técnica, a adequação ao público-alvo, a
progressão pedagógica e o cumprimento dos critérios de conclusão. Comentários de
revisão devem explicar o problema e, quando possível, sugerir uma direção para a
correção.

Antes de enviar, confira se o pull request não contém mudanças não relacionadas
ao seu objetivo.
