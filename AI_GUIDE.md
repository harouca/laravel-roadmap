# Guia de uso de Inteligência Artificial

Este documento define como a Inteligência Artificial deve ser utilizada no
Laravel Roadmap. Ele orienta leitores, autores e revisores durante o aprendizado
e a construção progressiva da aplicação.

## Objetivo

Ensinar a utilizar IA como apoio ao desenvolvimento profissional sem transferir
para a ferramenta a responsabilidade de compreender, decidir e validar.

A IA pode ajudar a explorar alternativas, reduzir trabalho repetitivo, revisar
uma solução e tornar perguntas mais precisas. A decisão final, entretanto, deve
ser sustentada pelo conhecimento do desenvolvedor, pelas necessidades do projeto
e por evidências verificáveis.

## Filosofia

A IA é uma ferramenta. Ela não substitui entendimento, experiência, documentação
oficial, testes ou revisão humana.

O princípio central deste projeto é:

> **Nunca aceite uma resposta da IA sem compreendê-la.**

Uma resposta plausível ainda pode conter premissas erradas, código inseguro,
recursos inexistentes, dependências desnecessárias ou decisões inadequadas ao
contexto. Usar IA profissionalmente significa manter autoria e responsabilidade
sobre o resultado.

A IA amplia a produtividade. O conhecimento continua pertencendo ao
desenvolvedor.

## Princípios

### Compreender antes de aceitar

Não aprove uma sugestão que você não consiga explicar. Identifique o problema,
as premissas da resposta e o papel de cada parte da solução.

### Revisar antes de utilizar

Leia a resposta como leria uma contribuição externa. Procure inconsistências,
complexidade desnecessária, impactos em outras partes do sistema e desacordo com
as convenções do projeto.

### Validar antes de publicar

Confirme APIs e comportamentos em fontes oficiais. Execute testes, análise
estática e verificações proporcionais ao risco. Uma resposta da IA não é
evidência de que a solução funciona.

### Nunca confiar cegamente

Trate segurança, autenticação, autorização, dados pessoais, migrations,
dependências e operações destrutivas com atenção adicional. Quando não houver
meios de validar uma afirmação, registre a incerteza em vez de apresentá-la como
fato.

### Utilizar IA para ampliar capacidade técnica

Use a ferramenta para comparar alternativas, localizar pontos que precisam de
investigação, formular casos de teste, melhorar explicações e revelar lacunas no
próprio raciocínio. O ganho esperado é aprender e decidir melhor, não apenas
produzir mais texto ou código.

## O que a IA costuma fazer bem

A IA costuma agregar valor quando a atividade possui contexto delimitado e o
resultado pode ser revisado. Ela pode ajudar a:

- explicar conceitos por perspectivas diferentes;
- gerar exemplos iniciais para discussão;
- estruturar documentação;
- realizar uma primeira revisão de código;
- sugerir alternativas e critérios de comparação;
- apoiar a criação de casos de teste;
- resumir informações fornecidas;
- localizar possíveis inconsistências.

Essas capacidades aceleram exploração e revisão, mas não garantem correção. O
resultado continua sujeito ao contexto do projeto, às fontes confiáveis e à
avaliação do desenvolvedor.

## Limitações comuns da IA

A IA pode assumir um contexto que não foi fornecido, misturar versões de
frameworks, inventar APIs e produzir código plausível, porém incorreto. Também
pode propor uma arquitetura incompatível com as restrições reais, ocultar
incertezas ou responder com confiança maior do que as evidências permitem.

Fluência não equivale a precisão. Essas limitações tornam indispensável a
validação humana, especialmente quando a resposta influencia dados, segurança,
dependências, arquitetura ou produção.

## Quando NÃO utilizar IA

A IA não deve ser usada como substituta para:

- leitura da documentação oficial;
- entendimento das regras de negócio;
- revisão de Pull Requests;
- decisões críticas de segurança;
- aprovação de código para produção;
- responsabilidade técnica.

Também não deve receber informações que a equipe não esteja autorizada a
compartilhar. Quando a tarefa exige conhecimento institucional, decisão formal
ou responsabilização, a ferramenta pode no máximo apoiar a análise; ela não pode
ocupar o papel de quem responde pelo resultado.

## Níveis de utilização da IA

Os níveis indicam o tipo de responsabilidade envolvida. Eles não representam uma
competição nem autorizam maior autonomia sem revisão.

### Nível 1 — Assistência

A IA ajuda a esclarecer termos, organizar dúvidas, resumir informações já
fornecidas ou sugerir caminhos de estudo.

Neste nível, o leitor deve comparar a explicação com o material do capítulo e
identificar o que ainda não compreendeu. A resposta serve como apoio à leitura,
não como fonte única.

### Nível 2 — Produtividade

A IA auxilia em tarefas delimitadas e verificáveis, como esboçar documentação,
propor casos de teste, apontar repetições ou ajudar a organizar uma alteração.

Antes de utilizar o resultado, o desenvolvedor deve conferir escopo, convenções,
dependências e efeitos colaterais. Ganhar tempo não justifica introduzir código
que a equipe não consiga manter.

### Nível 3 — Revisão

A IA atua como uma segunda leitura de código, documentação, testes ou decisões.
Ela pode procurar riscos, inconsistências e casos não considerados.

As observações devem ser tratadas como hipóteses. O desenvolvedor confirma cada
achado no código, nos testes ou em uma fonte confiável e também procura problemas
que a IA deixou de apontar.

### Nível 4 — Arquitetura

A IA ajuda a comparar alternativas arquiteturais, explicitar trade-offs e
formular perguntas sobre manutenção, segurança, desempenho e evolução.

Decisões nesse nível exigem contexto amplo. A recomendação deve considerar o
problema real, as restrições do projeto e o custo de cada alternativa. Nenhuma
arquitetura deve ser adotada apenas porque foi sugerida pela ferramenta ou é
comum em projetos maiores.

### Nível 5 — Parceria

A IA participa de um ciclo contínuo de investigação, implementação, crítica e
refinamento. O desenvolvedor fornece contexto, divide o trabalho em etapas,
avalia evidências e direciona as próximas ações.

Parceria não significa delegação irrestrita. O desenvolvedor continua responsável
por definir objetivos, proteger dados, aprovar mudanças e garantir que o resultado
possa ser compreendido, testado e mantido.

## Confiança Progressiva

Quanto maior o impacto de uma decisão, maior deve ser o nível de validação. A
confiança não aumenta porque a resposta parece convincente; ela aumenta conforme
evidências independentes confirmam que a proposta é adequada.

Uma correção de ortografia pode exigir apenas leitura. Uma alteração de
documentação pede conferência do contexto e das referências. Uma refatoração
exige revisão do diff e testes que demonstrem a preservação do comportamento.

Migrations, autenticação, autorização e operações destrutivas exigem revisão
mais rigorosa, ambiente controlado, testes adequados e plano para falhas ou
reversão. Nesses casos, uma resposta da IA é somente uma hipótese inicial.

O esforço de revisão deve ser proporcional tanto à probabilidade de erro quanto
ao dano que esse erro pode causar.

## Ciclo de trabalho recomendado

Ao utilizar IA durante uma atividade:

1. defina o problema e o resultado esperado;
2. forneça apenas o contexto necessário, sem segredos ou dados pessoais;
3. registre o prompt relevante para a análise didática;
4. leia a resposta inteira e resuma a proposta com suas próprias palavras;
5. identifique premissas, riscos e informações que precisam de confirmação;
6. compare a proposta com documentação oficial e convenções do projeto;
7. teste ou verifique a solução de forma proporcional ao impacto;
8. revise a solução e registre por que a versão final foi aceita;
9. descarte sugestões que não possam ser compreendidas ou validadas.

## Evidências de validação

Dependendo da atividade, uma validação pode incluir:

- referência à documentação oficial;
- teste automatizado ou verificação manual reproduzível;
- saída de uma ferramenta de análise;
- comparação entre alternativas e seus trade-offs;
- revisão do diff e dos arquivos afetados;
- explicação do resultado esperado e do resultado observado.

Copiar a mesma resposta para outra ferramenta de IA não constitui validação
independente.

## Anti-padrões

Este projeto considera inadequado:

- copiar código sem compreender seu funcionamento;
- utilizar IA para esconder falta de conhecimento;
- justificar uma decisão apenas porque “a IA sugeriu”;
- aumentar a complexidade sem uma necessidade demonstrável;
- substituir testes por confiança na resposta;
- ignorar documentação oficial relevante.

Esses comportamentos ocultam incertezas, dificultam manutenção e impedem que a
atividade produza aprendizado real. Quando faltar conhecimento, a resposta
profissional é identificar a lacuna, estudá-la e buscar revisão apropriada.

## IA Transparente

Sempre que a IA participar da construção de um capítulo ou de uma solução, o
leitor deve conseguir responder:

- Por que a IA foi utilizada?
- Qual problema ela ajudou a resolver?
- O que foi aceito?
- O que foi rejeitado?
- Por que determinadas sugestões foram descartadas?
- Qual foi a decisão final do desenvolvedor?

O objetivo é tornar o raciocínio técnico visível e revisável. A IA nunca deve
aparecer como uma caixa-preta que entrega uma decisão sem contexto, critérios ou
autoria humana.

## Privacidade e segurança

Não envie para uma ferramenta de IA:

- credenciais, tokens ou conteúdo de arquivos `.env`;
- dados pessoais ou clínicos reais;
- código proprietário sem autorização;
- informações internas que não possam ser compartilhadas;
- dumps de banco de dados, logs ou configurações sem revisão e anonimização.

Os exemplos do sistema ambulatorial devem usar dados fictícios. Antes de colar
qualquer conteúdo em um serviço externo, confirme as regras de privacidade e a
autorização aplicável.

## Relação com os capítulos

Todo capítulo técnico deve conter uma seção `IA em Ação`, conforme o
`STYLE_GUIDE.md`. A seção registra o objetivo do uso da ferramenta, a proposta
recebida e, principalmente, a revisão feita pelo desenvolvedor.

O foco não é formar uma coleção de prompts. O foco é tornar visível o processo
de compreender, questionar, validar e melhorar uma solução assistida por IA.

## Conclusão

O objetivo do Laravel Roadmap não é ensinar pessoas a depender da Inteligência
Artificial. É formar profissionais capazes de liderar um processo de
desenvolvimento no qual a IA é apenas uma das ferramentas disponíveis.

O conhecimento, a responsabilidade e as decisões permanecem pertencendo ao
desenvolvedor.
