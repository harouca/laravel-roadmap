# Metodologia pedagógica

Este documento define a metodologia de ensino do Laravel Roadmap. Ele orienta a
concepção, a produção, a revisão e a avaliação dos materiais educacionais do
projeto.

A metodologia deve ser lida em conjunto com a visão, o plano mestre, o roadmap,
o guia de estilo e o guia de uso de Inteligência Artificial. Em caso de dúvida,
a progressão e a compreensão do estudante têm prioridade sobre a quantidade de
conteúdo publicado.

## 1. Objetivo pedagógico

Formar profissionais capazes de compreender problemas, construir soluções,
avaliar consequências e justificar decisões no desenvolvimento de software.

Ao concluir a trilha, o estudante deve ter desenvolvido autonomia para:

- relacionar fundamentos a situações práticas;
- decompor problemas e reconhecer dependências;
- utilizar documentação e outras fontes de forma crítica;
- aplicar ferramentas sem perder compreensão sobre o resultado;
- revisar código, decisões e processos com base em evidências;
- comunicar escolhas técnicas com clareza;
- evoluir uma aplicação preservando qualidade e capacidade de manutenção.

O objetivo não é apenas transmitir informação. É desenvolver competência, isto
é, a capacidade de mobilizar conhecimento, prática e julgamento em contexto.

## 2. Filosofia de ensino

A metodologia adota aprendizagem progressiva, prática deliberada e reflexão
crítica. Conceitos são introduzidos antes de serem exigidos, aplicados em
contextos controlados e retomados quando novos problemas aumentam sua
complexidade.

O ensino deve respeitar estes princípios:

- **compreensão antes da execução:** saber o que será feito e por quê;
- **problema antes da abstração:** apresentar a necessidade antes da ferramenta;
- **prática com propósito:** toda atividade deve verificar um objetivo declarado;
- **complexidade gradual:** aumentar a dificuldade sem criar saltos conceituais;
- **erro como evidência:** usar dificuldades para localizar lacunas e orientar
  revisão;
- **autonomia progressiva:** reduzir orientação conforme o estudante demonstra
  domínio;
- **decisão justificada:** avaliar alternativas, riscos e consequências;
- **integração:** relacionar teoria, laboratório, projeto, IA e revisão.

O material não deve confundir facilidade de copiar uma solução com aprendizagem.

## 3. Perfil do estudante

O estudante esperado possui conhecimentos iniciais de programação e contato
básico com desenvolvimento web. Ele pode executar instruções simples, mas ainda
está consolidando modelos mentais, orientação a objetos, arquitetura, testes,
fluxo profissional e operação de aplicações.

A metodologia não pressupõe domínio avançado. Ao mesmo tempo, trata o estudante
como participante ativo, responsável por formular hipóteses, consultar fontes,
registrar dúvidas, testar resultados e explicar decisões.

Diferenças de experiência devem ser atendidas por pré-requisitos explícitos,
referências de apoio e atividades graduadas, não pela omissão dos fundamentos.

## 4. Ciclo de aprendizagem

Cada unidade de aprendizagem deve percorrer um ciclo verificável:

1. **Contextualizar:** apresentar o problema, o objetivo e os conhecimentos
   necessários.
2. **Compreender:** construir vocabulário e modelo mental.
3. **Observar:** analisar uma demonstração delimitada.
4. **Praticar:** realizar uma atividade com orientação proporcional à etapa.
5. **Integrar:** aplicar o conhecimento no Projeto Integrador quando houver base.
6. **Revisar:** avaliar resultado, decisões, riscos e evidências.
7. **Explicar:** comunicar o que foi aprendido e justificar a solução.
8. **Retomar:** identificar lacunas e planejar a próxima iteração.

O ciclo não termina quando uma tarefa produz uma saída. Ele termina quando o
estudante consegue interpretar o resultado e relacioná-lo ao objetivo inicial.

## 5. Pirâmide do conhecimento

A progressão do estudante é organizada em cinco níveis cumulativos:

1. **Fundamentos:** reconhecer termos, responsabilidades e relações essenciais.
2. **Compreensão:** explicar conceitos com as próprias palavras e antecipar
   efeitos básicos.
3. **Aplicação:** usar o conhecimento em uma tarefa delimitada.
4. **Análise:** comparar alternativas, diagnosticar problemas e avaliar riscos.
5. **Síntese e autonomia:** combinar conhecimentos, justificar decisões e evoluir
   soluções sem depender de instruções passo a passo.

Os níveis superiores não substituem os inferiores. Uma decisão arquitetural sem
fundamentos verificáveis representa um salto, não avanço. Exercícios, laboratórios
e checkpoints devem indicar qual nível estão avaliando.

## 6. Espiral de aprendizagem

Assuntos essenciais devem reaparecer em contextos progressivamente mais
complexos. A primeira apresentação estabelece um modelo simples; as retomadas
acrescentam restrições, integração, qualidade e operação.

Cada volta da espiral deve:

- recuperar explicitamente o conhecimento anterior;
- introduzir uma nova dificuldade relevante;
- mostrar por que a solução anterior já não é suficiente ou precisa evoluir;
- preservar o que continua válido;
- exigir maior autonomia e qualidade de justificativa;
- terminar com reflexão sobre o que mudou no modelo mental.

Repetição sem novo objetivo deve ser evitada. A espiral aprofunda conhecimento;
ela não duplica conteúdo.

## 7. Estrutura obrigatória dos capítulos

Todo capítulo deve conter, quando aplicável e na ordem pedagógica adequada:

1. objetivos de aprendizagem observáveis;
2. pré-requisitos;
3. problema e contexto;
4. conceitos e terminologia;
5. funcionamento interno na profundidade necessária;
6. demonstração simples;
7. aplicação contextualizada;
8. erros comuns e limites;
9. boas práticas e critérios de decisão;
10. seção `IA em Ação` para capítulos técnicos;
11. resumo;
12. exercícios;
13. checklist de conclusão, quando necessário.

Os títulos podem ser adaptados ao assunto, mas as funções pedagógicas não devem
desaparecer. Objetivos, resumo e exercícios precisam estar alinhados: o capítulo
deve ensinar e avaliar o mesmo conjunto de competências.

## 8. Integração entre teoria, projeto e IA

Os três elementos cumprem responsabilidades diferentes:

- a **teoria** constrói modelos mentais, vocabulário e critérios;
- o **projeto** revela como decisões se acumulam e afetam um sistema em evolução;
- a **IA** apoia investigação, produtividade e revisão, tornando explícito o
  raciocínio crítico do desenvolvedor.

A teoria deve preceder a integração. O projeto não deve receber uma solução que
o estudante ainda não tenha condições de compreender. A IA não deve produzir um
atalho que elimine a prática ou esconda uma dependência conceitual.

Uma integração é pedagogicamente válida quando o estudante consegue explicar o
problema, a decisão tomada, o papel da IA, as evidências de validação e o impacto
da mudança no projeto.

## 9. Critérios de qualidade

Uma unidade educacional deve ser avaliada por:

- correção técnica e atualização verificável;
- clareza para o perfil definido;
- coerência com a ordem pedagógica;
- pré-requisitos explícitos e disponíveis;
- alinhamento entre objetivo, explicação, prática e avaliação;
- exemplos e atividades com propósito identificável;
- distinção entre conceitos gerais e particularidades de versão;
- tratamento de riscos, limites e alternativas;
- acessibilidade da linguagem sem perda de precisão;
- links, referências e instruções verificáveis;
- integração responsável da IA;
- possibilidade de revisão e manutenção futura.

Quantidade de texto, número de recursos abordados e complexidade aparente não
são indicadores de qualidade por si só.

## 10. Critérios para concluir um capítulo

Um capítulo pode ser considerado concluído quando:

- atende aos critérios de qualidade desta metodologia;
- cumpre todos os objetivos de aprendizagem declarados;
- não depende de conteúdo ainda não ensinado ou não referenciado;
- apresenta profundidade compatível com seu lugar no roadmap;
- contém atividades capazes de verificar compreensão e aplicação;
- registra como exemplos e afirmações técnicas foram validados;
- apresenta `IA em Ação` com análise crítica, quando for técnico;
- permite que o estudante explique decisões, não apenas reproduza passos;
- passou por revisão técnica, pedagógica e editorial;
- não possui lacunas conhecidas que impeçam a aprendizagem pretendida.

Publicação e conclusão são estados diferentes. Um rascunho pode ser publicado
para colaboração sem ser marcado como concluído no roadmap.

## 11. Erros pedagógicos que devem ser evitados

O projeto deve evitar:

- introduzir ferramentas antes do problema que elas resolvem;
- exigir conceitos não ensinados ou não declarados como pré-requisitos;
- apresentar receitas sem explicar decisões e consequências;
- usar exemplos extensos para demonstrar uma ideia simples;
- aumentar complexidade para parecer tecnicamente avançado;
- confundir repetição mecânica com domínio;
- fornecer exercícios cuja resposta já está integralmente exposta;
- avaliar algo diferente do que foi ensinado;
- ocultar erros, incertezas ou alternativas legítimas;
- tratar IA, documentação ou autoridade como substitutas do raciocínio;
- marcar progresso sem evidência no repositório;
- acumular conteúdo sem capacidade de revisão e manutenção.

## 12. Papel do Projeto Integrador

O Projeto Integrador é a aplicação progressiva mantida em `project/`. Sua função
é tornar visíveis as relações entre conceitos e as consequências das decisões ao
longo do tempo.

Cada incremento deve:

- corresponder a conhecimentos já apresentados;
- resolver uma necessidade identificável do domínio ambulatorial;
- possuir escopo pequeno o suficiente para revisão;
- preservar rastreabilidade com capítulos e laboratórios;
- incluir validação proporcional ao risco;
- evitar abstrações que ainda não tenham justificativa pedagógica.

O Projeto Integrador não é um repositório de soluções prontas. Ele é evidência da
evolução do estudante e do próprio material.

## 13. Papel dos Laboratórios

Laboratórios transformam conhecimento em desempenho observável. Eles devem
propor uma situação, delimitar o resultado esperado e fornecer critérios de
conclusão sem retirar do estudante as decisões compatíveis com seu nível.

Um laboratório deve:

- declarar objetivo e pré-requisitos;
- indicar sua relação com o capítulo e com o projeto;
- organizar atividades em progressão;
- permitir experimentação segura;
- exigir registro de resultado e reflexão;
- conter critérios verificáveis;
- distinguir orientação, dica e solução.

Laboratórios não substituem explicação conceitual e não devem introduzir, sem
apoio, um assunto que o capítulo ainda não desenvolveu.

## 14. Papel da IA

A IA é uma ferramenta transversal de assistência, produtividade, revisão e
investigação. Seu papel é ampliar a capacidade técnica do estudante, não decidir
em seu lugar.

O uso pedagógico deve exigir que o estudante:

- declare por que utilizou a IA;
- compreenda e resuma a proposta recebida;
- identifique premissas, riscos e possíveis erros;
- compare a resposta com fontes e critérios do projeto;
- registre o que aceitou, alterou ou rejeitou;
- valide a decisão final com evidência adequada.

Quanto maior o impacto, maior deve ser o rigor da validação. O `AI_GUIDE.md`
define os princípios permanentes desse uso.

## 15. Papel da revisão

Revisão é uma etapa de aprendizagem, não apenas controle de qualidade. Ela ajuda
a confrontar intenção e resultado, revelar lacunas e tornar critérios técnicos
explícitos.

A revisão deve observar três dimensões:

- **técnica:** correção, segurança, efeitos e capacidade de manutenção;
- **pedagógica:** progressão, clareza, alinhamento e nível de autonomia exigido;
- **editorial:** linguagem, terminologia, estrutura e consistência documental.

Comentários devem explicar o problema e os critérios envolvidos. Aprovação sem
leitura e correção sem justificativa reduzem o valor formativo do processo.

## 16. Como medir a evolução do estudante

A evolução deve ser observada por evidências variadas:

- qualidade das explicações com palavras próprias;
- redução de dependência de instruções passo a passo;
- capacidade de decompor problemas;
- escolha e justificativa de alternativas;
- precisão ao diagnosticar erros;
- qualidade dos testes e das validações;
- revisão crítica de respostas da IA;
- transferência do conhecimento para um novo contexto;
- integração segura no Projeto Integrador;
- capacidade de reconhecer limites e solicitar revisão.

Velocidade isolada não mede aprendizagem. A avaliação deve considerar a
qualidade do raciocínio, a consistência do resultado e a autonomia demonstrada.

## 17. Checkpoints

Checkpoints são momentos formais de consolidação entre etapas relevantes. Eles
devem verificar se o estudante possui base para avançar e indicar recuperação
quando houver lacunas.

Um checkpoint pode combinar:

- autoavaliação orientada pelos objetivos;
- explicação oral ou escrita de conceitos e decisões;
- exercício de aplicação sem roteiro completo;
- revisão de uma solução com problemas intencionais;
- análise do estado do Projeto Integrador;
- avaliação do uso e da validação de IA;
- plano de revisão para competências ainda frágeis.

O resultado deve ser registrado como **pronto para avançar**, **pronto com
ressalvas** ou **revisão necessária**, acompanhado de evidências. Checkpoints não
devem funcionar como punição nem depender apenas de memorização.

## 18. Compromisso editorial

Autores e revisores assumem o compromisso de:

- preservar a progressão e o público-alvo;
- explicar decisões, limites e riscos com honestidade;
- verificar conteúdo técnico e explicitar incertezas;
- separar evidência, opinião e planejamento;
- manter teoria, prática, projeto e avaliação alinhados;
- utilizar IA com transparência e responsabilidade;
- corrigir erros de forma rastreável;
- evitar publicação motivada apenas por volume;
- ouvir dificuldades reais dos estudantes;
- revisar a metodologia quando as evidências mostrarem necessidade.

O Laravel Roadmap considera o estudante capaz de desenvolver autonomia quando
recebe contexto, prática, critérios e revisão adequados. Todo material deve
contribuir para essa autonomia.
