# Visão do Laravel Roadmap

Este documento apresenta o propósito de longo prazo do Laravel Roadmap. O
[plano mestre](MASTER_PLAN.md) transforma essa direção em arquitetura editorial,
enquanto o [roadmap](ROADMAP.md) registra a sequência e o progresso do trabalho.

## 1. Nossa missão

Nossa missão é ajudar pessoas a aprender Laravel, Engenharia de Software e
práticas profissionais de desenvolvimento de forma progressiva, prática e
tecnicamente responsável.

Queremos aproximar a documentação de referência da experiência de construir uma
aplicação real. Para isso, reunimos explicações conceituais, exemplos isolados,
exercícios, laboratórios e uma aplicação que evolui junto com o aprendizado.

O objetivo não é ensinar a memorizar comandos nem a copiar respostas produzidas
por Inteligência Artificial. É desenvolver a capacidade de entender um problema,
avaliar alternativas, tomar decisões, validar resultados e manter o código que
resulta dessas decisões.

## 2. Nossa visão

Queremos que o Laravel Roadmap se torne uma referência aberta em português
brasileiro para quem precisa avançar dos primeiros contatos com Laravel até a
construção consciente de aplicações organizadas, testáveis e operáveis.

Queremos também oferecer uma metodologia clara para trabalhar com IA sem
substituir conhecimento por automação. A ferramenta pode ampliar a produtividade
e a capacidade de investigação; autoria, julgamento e responsabilidade continuam
com o desenvolvedor.

Essa referência deve continuar útil como percurso de aprendizagem e como fonte
de consulta. Seu valor dependerá menos da quantidade de páginas e mais da
clareza, da correção técnica, da progressão pedagógica e da capacidade de
acompanhar a evolução do ecossistema sem perder conceitos duradouros.

## Nossos valores

- **Entendimento:** saber explicar uma solução antes de aceitá-la.
- **Pensamento crítico:** questionar premissas, riscos e alternativas.
- **Responsabilidade:** assumir autoria pelas mudanças e por seus efeitos.
- **Evidência:** validar afirmações, código e decisões de forma reproduzível.
- **Clareza:** tornar conceitos complexos acessíveis sem distorcê-los.
- **Colaboração:** revisar contribuições com respeito e justificativas técnicas.
- **Evolução sustentável:** preferir conhecimento durável e manutenção possível.

## 3. Nosso público-alvo

O projeto é voltado principalmente a pessoas que:

- conhecem fundamentos de PHP e já tiveram contato básico com Laravel;
- ainda estão consolidando orientação a objetos e arquitetura de aplicações;
- conseguem seguir exemplos, mas desejam compreender as decisões por trás
  deles;
- precisam conectar framework, banco de dados, testes e operação em um percurso
  coerente;
- desejam usar IA como parceira de desenvolvimento sem depender dela para
  compreender o próprio código;
- valorizam material técnico em português brasileiro.

Também queremos apoiar instrutores, pessoas mentoras e equipes que precisem de
uma base organizada para estudos. O conteúdo não pressupõe experiência avançada,
mas trata o leitor como alguém capaz de compreender fundamentos quando eles são
explicados com contexto.

## 4. Os problemas que queremos resolver

Materiais sobre frameworks frequentemente apresentam recursos em isolamento,
sem mostrar suas dependências ou seus efeitos em uma aplicação que cresce. Isso
pode levar o estudante a reproduzir soluções sem saber quando elas são
apropriadas.

O Laravel Roadmap busca reduzir problemas como:

- trilhas que saltam de conceitos básicos para abstrações avançadas;
- exemplos que funcionam sozinhos, mas não ajudam a estruturar uma aplicação;
- comandos apresentados sem explicar seus efeitos;
- decisões arquiteturais copiadas sem um problema que as justifique;
- conteúdo geral misturado com particularidades de uma versão;
- exercícios sem objetivo ou critério de conclusão;
- documentação que envelhece sem indicar o que foi verificado;
- falta de continuidade entre aprender, praticar, integrar e operar;
- uso de IA baseado em cópia, sem revisão técnica ou validação;
- automação que aumenta a produção de código, mas reduz a compreensão do sistema.

Não pretendemos substituir a documentação oficial. Queremos preparar o leitor
para consultá-la melhor, interpretar suas escolhas e aplicar seus recursos com
responsabilidade.

## 5. Os princípios editoriais

Todo conteúdo deve seguir estes princípios:

- **clareza:** introduzir termos e dependências antes de utilizá-los;
- **progressão:** exigir apenas conhecimentos ensinados ou declarados como
  pré-requisitos;
- **contexto:** explicar o que é, por que existe, quando usar e quando evitar;
- **correção:** verificar afirmações técnicas e evitar certezas sem evidência;
- **durabilidade:** separar conceitos gerais de comportamentos específicos de
  versão;
- **prática significativa:** relacionar exemplos e exercícios aos objetivos do
  capítulo;
- **entendimento antes da automação:** usar ferramentas somente quando o leitor
  puder avaliar o resultado;
- **pensamento crítico:** tratar respostas de IA e outras fontes como propostas
  sujeitas a revisão;
- **consistência:** usar o sistema de gestão ambulatorial como domínio principal;
- **economia:** incluir apenas código, diagramas e abstrações que contribuam para
  a compreensão;
- **transparência:** distinguir conteúdo concluído, planejamento e ideias
  futuras;
- **acessibilidade técnica:** escrever em português brasileiro, preservando
  nomes oficiais de comandos, classes e recursos.

Esses princípios são aplicados pelas regras do `STYLE_GUIDE.md` e pelos critérios
de revisão do `CONTRIBUTING.md`.

O princípio que orienta o uso de IA em todo o projeto é:

> **Nunca aceite uma resposta da IA sem compreendê-la.**

## 6. O diferencial do Laravel Roadmap

O diferencial do projeto não está em cobrir todos os recursos do framework. Está
em relacionar diferentes formas de aprendizado dentro de uma única progressão.

Um conceito pode ser explicado no livro, observado em um exemplo mínimo,
praticado em um laboratório, analisado com apoio de IA e integrado à aplicação
ambulatorial. Cada formato tem uma responsabilidade clara, evitando tanto
repetição desnecessária quanto exemplos desconectados.

A aplicação progressiva funciona como registro das consequências das decisões.
Ela permite observar como rotas, Controllers, persistência, regras de negócio,
segurança, testes e operação passam a se relacionar. Ao mesmo tempo, a separação
entre conteúdo geral e arquivos em `versions/` ajuda a preservar o valor do
material quando a versão técnica de referência mudar.

A IA não forma uma etapa separada. Em cada capítulo técnico, ela torna visível o
processo de formular um objetivo, examinar uma resposta, encontrar possíveis
problemas, validar informações e recomendar uma versão final compreendida pelo
desenvolvedor.

## 7. Como mediremos o sucesso do projeto

O sucesso será medido por evidências de aprendizagem, qualidade e manutenção,
não apenas por volume de conteúdo ou popularidade. Entre os sinais relevantes
estão:

- capítulos que atendem aos critérios editoriais e técnicos definidos;
- leitores capazes de concluir exercícios e explicar suas decisões;
- laboratórios reproduzíveis, com resultados e critérios verificáveis;
- aplicação progressiva coerente com os assuntos já ensinados;
- exemplos executáveis e compatíveis com o ambiente documentado;
- ausência controlada de links quebrados, instruções obsoletas e contradições;
- issues e revisões que resultam em melhorias rastreáveis;
- contribuições de pessoas diferentes sem perda de consistência editorial;
- feedback de iniciantes indicando onde a progressão ainda possui lacunas;
- análises de IA que documentam revisão crítica, riscos e evidências de
  validação, em vez de apenas reproduzir respostas;
- versões publicadas com mudanças relevantes documentadas no changelog.

Estrelas, acessos e número de páginas podem indicar alcance, mas não substituem
esses sinais de utilidade e confiabilidade.

## 8. O compromisso com a qualidade

Preferimos publicar menos conteúdo a manter material extenso que não possa ser
revisado. Um capítulo não será considerado concluído apenas porque possui texto;
ele deve cumprir seus objetivos, respeitar dependências, oferecer prática
adequada e passar por revisão técnica, pedagógica e textual.

Afirmações específicas do Laravel 13 devem ser confirmadas em documentação
oficial. Código executável deve ser validado no ambiente previsto. Erros
encontrados depois da publicação devem ser tratados com transparência e
registrados quando afetarem o entendimento ou a estrutura do projeto.

Qualidade também significa reconhecer limites. Quando uma decisão estiver
pendente, ela deve aparecer como pendente. Quando houver mais de uma alternativa
válida, o texto deve apresentar os critérios da escolha em vez de declarar uma
preferência como regra universal.

O mesmo compromisso se aplica ao uso de IA. Nenhuma resposta será tratada como
autoridade por si só. Sugestões devem ser compreendidas, confrontadas com o
contexto e verificadas antes de integrar documentação, exemplos ou aplicação.

## 9. A filosofia de aprendizado

Aprender um framework é aprender a enxergar responsabilidades, fluxos e
consequências. A prática é indispensável, mas se torna mais valiosa quando o
estudante consegue explicar o que fez e por que fez.

Por isso, o percurso parte de modelos mentais simples e aumenta a complexidade
conforme surgem problemas reais. Primeiro compreendemos; depois observamos;
então praticamos; por fim, integramos e revisamos. Abstrações entram quando
resolvem uma dificuldade visível, não apenas porque são comuns em projetos
maiores.

Erros fazem parte desse processo. Os exercícios e laboratórios devem permitir
experimentação segura, incentivar o uso de documentação e ajudar o leitor a
diagnosticar problemas sem depender de respostas prontas.

A IA pode participar de todas essas etapas como assistência, ferramenta de
produtividade, revisora, apoio arquitetural ou parceira de investigação. Quanto
maior o impacto da decisão, maior deve ser a exigência de contexto, evidência e
revisão humana. O conhecimento continua pertencendo ao desenvolvedor.

## 10. Uma mensagem final aos futuros leitores

Este projeto foi pensado para ser percorrido com curiosidade e sem pressa. Você
não precisa dominar toda a arquitetura de uma aplicação antes de começar. Precisa
apenas compreender bem o passo atual, praticá-lo e saber quais perguntas levar
para o próximo.

Use o roadmap como orientação, não como medida de valor pessoal. Consulte a
documentação oficial, questione os exemplos e compare alternativas. Quando algo
não estiver claro, isso pode revelar uma oportunidade de melhorar tanto seu
entendimento quanto este material.

Se utilizar IA, peça ajuda, mas não entregue a ela o seu julgamento. Leia a
resposta, explique-a com suas palavras, teste suas hipóteses e mantenha apenas o
que puder defender tecnicamente.

O Laravel Roadmap será construído por leitores e colaboradores que valorizam
explicações honestas, código compreensível e evolução sustentável. Esperamos que
você encontre aqui uma base para desenvolver aplicações melhores — e confiança
para continuar aprendendo além delas.
