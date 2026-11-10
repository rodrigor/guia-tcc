# Critérios de revisão do TCC no formato relatório técnico

Este arquivo reúne os critérios usados na revisão dos TCCs no formato Artigo
Tecnológico ou Relatório Técnico orientados por Rodrigo Rebouças de Almeida
(DCX/UFPB). Ele é a fonte única dos critérios: a skill de revisão do orientador e a
skill de apoio ao estudante usam o mesmo conteúdo, e o checklist do guia em PDF o
resume.

As instruções estão escritas para quem revisa o texto. Quando um trecho manda
"apontar ao aluno" ou "orientar o aluno", leia como o que deve ser verificado e
explicado.

## Contexto do trabalho avaliado

É um **relatório técnico** (formato "Artigo Tecnológico / Relatório Técnico" da
resolução de TCC), sem exigência de formalismo científico rigoroso, mas **com
exigência de coerência metodológica e de resultados**. O texto deve descrever
claramente o que foi feito e os resultados obtidos.

### Elementos obrigatórios pela resolução de TCC

O formato relatório técnico deve conter, segundo a resolução, os seguintes
elementos. Use esta lista como referência ao avaliar a completude do trabalho. A
ausência de qualquer um é, em regra, apontamento **OBRIGATÓRIO**:

1. **Introdução** com descrição clara do **problema** e do **contexto** que
   motivaram o desenvolvimento, uso ou avaliação da solução.
2. **Descrição do processo** sob o qual a solução foi desenvolvida, com
   **identificação dos envolvidos** (clientes, usuários, outros desenvolvedores
   etc.). *(Este é o cerne da metodologia; ver critério 6.)*
3. **Breve descrição das tecnologias** utilizadas durante todo o processo de
   desenvolvimento.
4. **Apresentação da solução**: descrição do que foi desenvolvido, diagramas e
   outros artefatos, **métricas relevantes** que demonstrem a dimensão do
   resultado, e anexos (fotos, impressões de tela, artefatos) que demonstrem a
   solução.
5. **Repositório público** com o código-fonte e demais artefatos (GitHub, Google
   Drive, Dropbox etc.), **exceto** sob contrato de sigilo. Verifique se há um
   link para o repositório e se ele está acessível/mencionado; se ausente, aponte
   (a menos que o trabalho declare sigilo).

**Parágrafo único, avaliação da solução:** se a solução passou por alguma
avaliação, é obrigatório **descrever o processo de avaliação e os resultados**. A
avaliação *científica* não é obrigatória, mas, havendo qualquer forma de avaliação
(testes com usuários, medição de desempenho, comparação antes/depois, validação
com a equipe), o processo e os resultados precisam constar. Ver critério 7.

Ao longo dos critérios abaixo, sempre que um deles corresponder a um elemento
obrigatório da resolução, trate a ausência como prioridade OBRIGATÓRIA.

## Leitura macro

Os critérios olham o texto por partes. A leitura macro olha o trabalho inteiro e
encontra o que só aparece quando as seções são comparadas entre si. Faça-a depois de
ler o texto completo e antes de avaliar os critérios, anotando para cada item o que
encontrou e onde:

1. **Mapa das seções.** Para cada seção, uma linha com o que ela afirma ou entrega e
   o que deixa preparado para a seguinte. Compare o mapa com o parágrafo em que o
   aluno apresenta a organização do texto: seção anunciada que não existe, seção que
   existe e não foi anunciada, ordem diferente.
2. **Linha do argumento.** Verifique se problema, objetivos, método, resultados e
   conclusão formam uma sequência em que cada parte usa o que a anterior preparou:
   conceito usado antes de ser definido, resultado que depende de uma etapa não
   descrita, conclusão que não decorre dos resultados.
3. **Resumo, Introdução e Conclusão.** Compare as três: devem prometer e afirmar a
   mesma coisa, com os mesmos números e o mesmo grau de cautela. Aponte o resultado
   que está no Resumo e não nos resultados, e a afirmação mais forte na Conclusão do
   que na discussão dos resultados.
4. **Números repetidos.** Liste os números que aparecem em mais de um lugar (Resumo,
   resultados, tabelas, discussão, conclusão) e confira se têm o mesmo valor. Quando
   houver tabelas com totais ou desdobramentos (por grupo, por modelo, por etapa),
   some e confira se fecham entre si e com o texto.
5. **Termos centrais.** Liste os termos que sustentam o trabalho e verifique se cada
   um mantém o mesmo nome e o mesmo sentido do começo ao fim (e se nomes iguais não
   designam coisas diferentes em estudos ou etapas distintas).
6. **Proporção.** Veja se o tamanho de cada seção corresponde ao seu papel: por
   exemplo, fundamentação longa e resultados curtos, ou metodologia de um parágrafo
   para um desenvolvimento de dez páginas.
7. **Percurso de cada objetivo.** Para cada objetivo e cada pergunta de pesquisa
   declarados na Introdução, anote: onde ele é desenvolvido no texto, qual etapa do
   método gera os dados que o atendem, qual resultado (seção, tabela, figura) o
   atende e onde o texto dá a resposta explícita. Anote também o objetivo que some
   antes da Conclusão ou reaparece com outro nome. Essas anotações viram a matriz de
   rastreabilidade do documento final.
8. **Proveniência dos resultados.** Liste cada resultado apresentado (número, tabela,
   figura, afirmação sobre o que foi observado) e indique a etapa do método que
   coletou ou produziu aquele dado. Resultado sem etapa de origem é o problema mais
   grave desta lista: resultado de entrevista sem entrevista no método, métrica sem
   medição descrita, opinião de usuários sem consulta a usuários, comparação
   antes/depois sem medida do "antes".
9. **Justificativa das escolhas.** Liste as escolhas do método (etapas, ferramentas,
   participantes, amostra, número de repetições, critérios de avaliação, exclusão de
   dados) e marque as que o texto não justifica, isto é, em que não está claro por
   que aquilo foi feito daquele jeito.

Os achados entram no documento como apontamentos comuns: encadeamento, proporção e
objetivo que some ao longo do texto no critério 2; resultado sem etapa de origem e
escolha sem justificativa no critério 6; números, Resumo e Conclusão desalinhados com
os resultados, objetivo sem resultado ou sem resposta no critério 7 e na matriz;
contradições e termos com sentidos diferentes nos critérios 3 e 9. Cite sempre os dois
lugares que não batem.

## Critérios de avaliação

### 1. Língua portuguesa e gramática
- Ortografia, acentuação, pontuação, concordância verbal e nominal, regência.
- Uso adequado e consistente de tempos verbais ao longo do texto.
- Clareza: identifique frases ambíguas, longas demais ou confusas e oriente a
  reescrita, indicando o que torna a frase confusa e como simplificá-la.
- **Escrita padronizada.** Aponte os padrões abaixo como problema de redação, sempre
  com antes e depois feitos com o texto do aluno. Eles vêm dos guias de sinais de
  escrita gerada da Wikipédia ("Signs of AI writing" e a adaptação "Sinais de texto
  gerado por inteligência artificial") e valem para qualquer texto, escrito por pessoa
  ou por ferramenta:
  - importância declarada sem o fato que a sustenta ("ergue-se como referência",
    "um marco para a área", "consolida-se como", "deixa um legado");
  - comentário em gerúndio no fim da frase ("…, destacando sua importância",
    "…, contribuindo para o desenvolvimento");
  - verbo rebuscado no lugar de "é" ou "tem" ("serve como", "atua como",
    "configura-se como", "conta com");
  - atribuição vaga ("especialistas apontam", "estudos mostram", "a literatura
    indica" sem citar quem);
  - contraste montado ("não apenas X, mas também Y"; "não é X, é Y") e enumeração de
    três itens só pela cadência;
  - fórmulas e conectores de enchimento ("vale ressaltar", "é importante destacar",
    "nesse sentido", "em suma") e vocabulário inflado ("robusto", "crucial",
    "potencializar", "jornada");
  - parágrafo que termina resumindo o que acabou de dizer, e conclusão genérica de
    "desafios e perspectivas" sem desafio concreto;
  - títulos com maiúscula em todas as palavras ("Impacto da Tecnologia na Gestão"; em
    português, só a primeira palavra e nomes próprios), excesso de negrito e listas em
    que todo item começa com rótulo em negrito;
  - sintaxe do inglês: vírgula antes do "e" final da enumeração ("A, B, e C") e
    decalques como "endereçar um problema" ou "eventualmente" no sentido de "por fim";
  - resíduo de conversa ("Claro!", "Espero que isso ajude") e campo por preencher
    ("[CITAR]", "[inserir]").
- **O que não apontar como problema de estilo.** Gramática correta, vocabulário formal
  ou acadêmico, conectivos isolados ("além disso"), tom neutro, variedade regional do
  português e travessão usado corretamente não são defeitos. Os guias da Wikipédia
  listam esses traços como indícios que não funcionam. Corrija só o que estiver errado.
- **Nunca trate esses padrões como prova de autoria.** Não diga nem insinue no
  feedback que o texto foi gerado por IA: nenhum sinal isolado prova autoria e
  detectores automáticos erram com frequência. O apontamento é sobre a redação e tem
  correção própria.

### 2. Encadeamento lógico e coerência textual
- Verifique se há progressão lógica entre parágrafos e seções (cada seção deve
  preparar a próxima).
- Aponte saltos de raciocínio, informações sem contexto prévio e repetições
  desnecessárias, indicando onde inserir o contexto faltante ou o que remover.
- Verifique se termos técnicos são definidos antes de serem usados; se não,
  indique onde a definição deve entrar.
- **Objetivos acompanhados ao longo do texto.** Cada objetivo ou pergunta de pesquisa
  anunciado na Introdução deve ser retomado onde é desenvolvido e chegar à Conclusão
  com o mesmo nome. Aponte o objetivo que desaparece depois da Introdução, o que
  reaparece com outra formulação sem aviso e a seção de desenvolvimento que não diz a
  qual objetivo serve.

### 3. Terminologia e siglas
- Consistência terminológica: o mesmo conceito deve ter sempre o mesmo nome (ex.:
  não alternar entre "sistema", "aplicação", "plataforma" e "software" para a
  mesma coisa). Ao apontar, sugira qual termo padronizar.
- Siglas devem ser expandidas por extenso na primeira ocorrência **apenas quando
  não forem amplamente conhecidas na área do trabalho**. Como se trata de um TCC
  de computação, siglas de uso corrente na área (ex.: API, REST, HTTP, HTML,
  YAML, IDE, CLI, CI/CD, SSL/TLS, npm, SQL) **não precisam** ser escritas por
  extenso; não as aponte. Cobre expansão apenas de siglas específicas do projeto,
  do domínio de negócio ou pouco usuais, que um leitor da área não reconheceria de
  imediato (ex.: o nome de um sistema interno, de um método proprietário ou de um
  termo de nicho). Na dúvida sobre se a sigla é "amplamente conhecida", não aponte.

### 4. Resumo/Abstract (se existir no formato do trabalho)
- Deve ser autossuficiente: o leitor entende o trabalho sem ler o restante.
- Deve conter, de forma sintética: objetivo, método/o que foi feito e resultado
  obtido. Se algum desses três faltar, indique qual e o que acrescentar.

### 5. Introdução
- Deve resumir o trabalho como um todo e apresentar claramente os objetivos
  (geral e específicos, se houver).
- Se os objetivos estiverem ausentes, vagos ou incompatíveis com o que foi de
  fato desenvolvido, aponte e oriente como reformulá-los para refletir o trabalho
  realizado.
- **Contexto institucional (AYTY):** o AYTY é o laboratório de Engenharia de
  Software Aplicada da Universidade Federal da Paraíba (Departamento de Ciências
  Exatas, https://ayty.org), e é comum que estes TCCs sejam desenvolvidos no
  contexto de um projeto do AYTY. Se o trabalho mencionar o AYTY sem apresentá-lo,
  ou usar descrições genéricas ("uma empresa privada na área de…") que deixam
  ambíguo se o AYTY é o laboratório de origem, o cliente ou o local do projeto,
  aponte a ambiguidade e oriente o aluno a explicar, na Introdução, que o TCC foi
  desenvolvido no contexto de um projeto do AYTY (laboratório da UFPB) e como o
  laboratório, a empresa/cliente e o projeto se relacionam. Não afirme essa
  relação por conta própria caso o texto não deixe claro; oriente o aluno a
  torná-la explícita.

### 6. Coerência metodológica (atenção especial)
A metodologia é um dos pontos mais negligenciados nos trabalhos. Dedique atenção
especial a este critério.
- A metodologia descrita deve ser compatível com o que foi executado e relatado.
- Verifique se o texto descreve **O QUE** foi feito, **COMO** foi feito e **COM
  QUAIS** ferramentas/tecnologias. Indique qual desses elementos falta e onde
  incluí-lo.
- **Identificação dos envolvidos (exigência da resolução):** a descrição do
  processo deve identificar quem participou: clientes, usuários, equipe,
  orientador, outros desenvolvedores, o papel do aluno. Se o trabalho não deixa
  claro quem fez o quê e para quem, aponte e oriente a incluir essa identificação.
- Aponte etapas mencionadas na metodologia que não aparecem no desenvolvimento (o
  aluno deve relatá-las ou removê-las da metodologia) e atividades relatadas no
  desenvolvimento que não foram previstas na metodologia (o aluno deve incluí-las
  na metodologia).
- **Proveniência dos resultados.** Todo resultado apresentado precisa de uma etapa da
  metodologia que coletou ou produziu aquele dado, dizendo como, com quem (ou sobre
  o quê) e com que instrumento. Resultado sem etapa de origem é **OBRIGATÓRIA**: não
  pode haver resultado de entrevista sem entrevista descrita na metodologia, dado de
  uso sem coleta desse dado, avaliação de usuários sem a sessão com usuários,
  métrica de desempenho sem a medição. Oriente o aluno a descrever a coleta na
  metodologia (o que foi coletado, de quem, como e quando na sequência das etapas)
  ou a retirar o resultado.
- **Justificativa das ações.** O texto deve deixar claro por que cada coisa está
  sendo feita: cada etapa, ferramenta, participante ou amostra, número de
  repetições, critério de avaliação e exclusão de dados precisa de um motivo
  declarado. Liste as escolhas sem justificativa. A falta é **RECOMENDADA** em
  geral e **OBRIGATÓRIA** quando a escolha muda a leitura do resultado (amostra,
  critério de avaliação, dados excluídos, comparação escolhida). O exemplo de
  antes e depois mostra a forma ("fizemos X para Y"), com o motivo deixado para o
  aluno preencher, porque só ele sabe por que escolheu.
- **SE A METODOLOGIA ESTIVER AUSENTE OU COM PROBLEMAS GRAVES:** além de apontar o
  problema, **oriente o aluno sobre como construir a metodologia**:
  - (a) Explique brevemente o que uma seção de metodologia de relatório técnico
    deve conter: as etapas do trabalho em ordem, como cada etapa foi conduzida e
    as ferramentas/tecnologias/materiais usados em cada uma.
  - (b) Com base no que foi **relatado no restante do trabalho** (desenvolvimento,
    resultados, figuras), proponha um **esboço de estrutura** para a metodologia
    daquele trabalho específico: liste as etapas que o aluno aparentemente
    executou e que devem ser descritas (ex.: "Pelo que você relata nas seções 4 e
    5, sua metodologia deve descrever ao menos: levantamento de requisitos,
    escolha das tecnologias X e Y, desenvolvimento do módulo Z, testes W…").
  - (c) Deixe claro que o esboço é uma sugestão de estrutura baseada no que está
    no documento, e que cabe ao aluno confirmar, completar e redigir com o que de
    fato aconteceu.
  - Ao orientar sobre as etapas, peça que o aluno deixe clara a **ordem/sequência**
    em que foram executadas (o que veio antes e depois, e as dependências entre
    etapas), **não datas nem período de calendário**. A metodologia descreve o
    percurso na ordem lógica em que aconteceu; cronograma com datas não é
    necessário. Peça também as **versões das ferramentas/tecnologias** usadas,
    quando relevante, porque isso importa para reprodutibilidade.

### 7. Apresentação da solução, resultados e conclusão
- **Apresentação da solução (exigência da resolução):** o trabalho deve descrever
  o que foi desenvolvido e demonstrar sua dimensão com **métricas relevantes** e
  **artefatos** (diagramas, impressões de tela, fotos). Se o trabalho descreve a
  solução mas não apresenta nenhuma métrica ou artefato que dê a dimensão do
  resultado, aponte e oriente o aluno a incluir dados concretos (ex.: nº de
  cenários automatizados, tempo de execução antes/depois, cobertura, volume
  processado, o que fizer sentido para o projeto).
- A seção de resultados/conclusão deve **apresentar resultados concretos**: o que
  aconteceu, o que foi obtido, o que funcionou ou não.
- Aponte conclusões genéricas ("o trabalho foi importante para o aprendizado")
  sem apresentação efetiva de resultados, e oriente a substituí-las pelos
  resultados concretos obtidos.
- **Avaliação da solução (parágrafo único da resolução):** se a solução passou por
  qualquer forma de avaliação (testes com usuários, medição de desempenho,
  comparação antes/depois, validação com a equipe), é **obrigatório descrever o
  processo de avaliação e seus resultados**. Se o texto menciona que houve
  avaliação mas não descreve como foi feita ou o que ela mostrou, aponte como
  OBRIGATÓRIO. A avaliação *científica* formal não é exigida (não cobre rigor
  estatístico), mas a descrição do processo e do resultado da avaliação
  realizada, sim.
- **Rastreabilidade objetivo → método → resultado → resposta:** faça a verificação
  cruzada explícita, a partir do percurso anotado na leitura macro. Para **cada**
  objetivo e **cada** pergunta de pesquisa declarados na introdução, verifique:
  - onde ele é desenvolvido no texto;
  - qual etapa do método gera os dados que o atendem;
  - qual resultado o atende (seção, tabela, figura);
  - onde o texto dá a **resposta explícita**. Ter dados sobre o assunto não basta: a
    pergunta precisa ser respondida com uma frase que diga a resposta, na discussão
    ou na conclusão.
  Objetivo ou pergunta sem resultado, ou sem resposta explícita, é **OBRIGATÓRIA**:
  oriente o aluno a apresentar o resultado e a resposta, ou a ajustar o objetivo.
  Resultado sem objetivo é **RECOMENDADA**: oriente a conectá-lo a um objetivo ou a
  retirá-lo. Objetivo atendido por um resultado cuja etapa de origem não está na
  metodologia entra também no critério 6 (proveniência). Esta verificação vira a
  **matriz de rastreabilidade** no documento final.
- Limitações e trabalhos futuros **não** são obrigatórios. Porém, se a seção
  existir, avalie: as limitações devem ser reais e específicas do trabalho (não
  genéricas) e os trabalhos futuros devem decorrer do que foi desenvolvido. Se
  estiverem genéricos, oriente como torná-los específicos.

### 8. Figuras, tabelas e gráficos
Requer inspeção **visual** das páginas, não só do texto extraído.
- Todo elemento visual (figura, tabela, gráfico, quadro) deve ter título e
  identificação numerada (ex.: "Figura 1 – …", "Tabela 2 – …"). Liste os
  elementos sem identificação.
- Todo elemento visual deve ser referenciado no texto, e a referência deve
  **descrever** o conteúdo (o que mostra e por que é relevante), não apenas
  citá-lo ("como mostra a Figura 3" sem descrição é insuficiente). Aponte cada
  elemento não referenciado ou apenas citado sem descrição, e oriente o que a
  descrição deve conter.
- Gráficos devem ter legendas e identificação dos eixos. Liste gráficos sem
  legenda ou sem rótulo de eixos.
- **Prints de código com fundo preto NÃO são aceitos: imagens devem ter fundo
  azul.** Liste cada ocorrência que precisa ser trocada.
- **Trechos de código NÃO devem aparecer como imagem:** devem estar como texto em
  bloco de código formatado (fonte monoespaçada). Liste toda ocorrência de código
  em imagem e oriente a substituição pelo texto formatado.

### 9. Inconsistências de conteúdo e trechos desconectados do trabalho
Sem fazer acusações sobre a origem do texto, aponte ao aluno os trechos com
problemas de consistência que ele deve corrigir ou justificar:
- Mudanças abruptas de estilo, tom ou nível de escrita entre trechos: oriente a
  uniformizar a redação.
- Afirmações que fogem do escopo ou do plano do trabalho: oriente a remover ou a
  conectar explicitamente ao projeto.
- Descrição de funcionalidades, tecnologias ou etapas que não aparecem em nenhum
  outro lugar do documento: oriente a documentá-las no desenvolvimento ou
  removê-las.
- Informações genéricas sobre o tema que não se conectam ao projeto específico:
  oriente a substituí-las por conteúdo relacionado ao trabalho realizado.
- Contradições entre o que um trecho afirma e o que o restante do trabalho relata:
  aponte os dois trechos conflitantes e oriente a harmonizá-los.
- Afirmações mais fortes em um trecho do que em outro (a Discussão diz "parte da
  diferença", a Conclusão diz "porque"): aponte e oriente a usar a mesma cautela.

Os padrões de escrita listados no critério 1 entram lá, como redação. Aqui, trate só
da consistência do conteúdo, e nunca como indício de autoria.

### 10. Normas (ABNT)
- Não é exigido rigor total com ABNT, mas notifique erros graves: ausência de
  referências bibliográficas, citações sem fonte, referências citadas no texto
  mas ausentes da lista (e vice-versa), numeração de seções inconsistente e
  elementos obrigatórios ausentes (capa, sumário, referências). Para cada erro,
  indique a correção esperada.
- **Confira as referências, não só o formato.** Quando houver acesso à rede, abra
  uma amostra dos DOIs e links (todos, se forem poucos) e verifique se resolvem e se
  levam ao trabalho citado, com autor, ano e veículo iguais aos da lista. DOI que
  leva a outro artigo, referência que não existe e link quebrado são apontamentos
  OBRIGATÓRIOS. Aponte também marcador de citação pendente ("[CITAR]"), link com
  parâmetro de rastreio (`utm_source=`) e citação direta de livro sem página. Diga no
  feedback quais referências foram conferidas e quais não puderam ser.

### 11. Elementos obrigatórios da resolução de TCC
Verifique a presença dos elementos exigidos pela resolução (ver
"Elementos obrigatórios pela resolução de TCC" no contexto acima). Os critérios
5, 6 e 7 já cobrem introdução/problema, descrição do processo/envolvidos e
apresentação/avaliação; aqui, confira os dois restantes:
- **Descrição das tecnologias:** o trabalho deve trazer ao menos uma breve
  descrição das tecnologias utilizadas no processo de desenvolvimento. Se estiver
  ausente, aponte e oriente onde incluí-la.
- **Repositório público:** deve haver link para um repositório público (GitHub,
  Google Drive, Dropbox etc.) com código-fonte e artefatos, **salvo contrato de
  sigilo**. Se não houver menção a repositório, aponte como OBRIGATÓRIO e oriente
  o aluno a incluir o link (ou a declarar explicitamente o sigilo, se for o caso).

## Prioridade dos apontamentos

Classifique cada apontamento em um destes três níveis:
- **OBRIGATÓRIA**: precisa ser corrigida para aprovação.
- **RECOMENDADA**: melhora bastante o trabalho, sem ser condição para a aprovação.
- **SUGESTÃO**: aprimoramento opcional.

## Textos explicativos de referência

Base para as aberturas explicativas dos critérios e da matriz. Adapte cada texto ao
trabalho: troque a frase genérica pelo caso concreto do aluno (qual objetivo, qual
resultado, qual seção) e corte o que não se aplica. Escreva na segunda pessoa e siga
o padrão de redação do próprio feedback.

**Objetivos e perguntas de pesquisa (critérios 2 e 7, matriz).** Os objetivos e as
perguntas de pesquisa anunciados na Introdução são um compromisso com o leitor: eles
dizem o que o trabalho vai entregar, e a banca avalia o texto por esse compromisso.
Por isso, cada objetivo e cada pergunta precisam ser tratados ao longo do texto: o
método diz como os dados para atendê-los foram obtidos, os resultados mostram esses
dados, e a discussão ou a conclusão dá a resposta de forma explícita, com uma frase
que o leitor consiga localizar. Ter dados sobre o assunto não basta se o texto não
disser qual é a resposta. Quando um objetivo some depois da Introdução, o leitor
conclui que ele não foi cumprido. Nesse caso, há dois caminhos: desenvolver e
responder o objetivo, ou retirá-lo e ajustar a Introdução ao que o trabalho de fato
fez.

**Proveniência dos resultados (critério 6).** Todo resultado precisa ter uma origem
descrita na metodologia. Se você apresenta o que os usuários disseram, a metodologia
precisa descrever a entrevista ou o questionário: com quem, quantas pessoas, com que
roteiro e em que momento do trabalho. Se apresenta um tempo de execução, precisa
descrever como e em que condições ele foi medido. Um resultado sem essa origem não
pode ser conferido nem repetido, e a banca não tem como saber se ele vale. A correção
é descrever a etapa de coleta na metodologia, ou retirar o resultado.

**Justificativa das ações (critério 6).** O leitor precisa entender por que cada
coisa foi feita daquele jeito: por que essa ferramenta, esses participantes, esse
número de repetições, esse critério de avaliação. Uma escolha sem motivo declarado
parece arbitrária, e quando ela afeta o resultado (a amostra, o critério de
avaliação, os dados excluídos), o leitor passa a duvidar do resultado também. Não é
preciso um parágrafo para cada escolha: em geral, uma oração com "para" ou "porque"
resolve.

**Metodologia em geral (critério 6).** A metodologia de um relatório técnico descreve
o percurso do trabalho na ordem em que aconteceu: quais etapas, como cada uma foi
conduzida, com quais ferramentas e quem participou. Ela é o que permite ao leitor
confiar nos resultados, porque mostra de onde eles vieram. Tudo o que aparece nos
resultados precisa ter passado pela metodologia, e tudo o que está na metodologia
precisa aparecer no desenvolvimento ou nos resultados.

**Resultados e conclusão (critério 7).** A conclusão de um relatório técnico diz o
que foi obtido, com os números e os fatos que os resultados mostraram. Frases sobre
aprendizado ou importância do tema não substituem resultado. A conclusão também não
pode afirmar mais do que os resultados sustentam: se a discussão apresenta um efeito
com ressalvas, a conclusão mantém as mesmas ressalvas.

**Figuras, tabelas e código (critério 8).** Toda figura e tabela precisa ser
apresentada no texto antes de aparecer, com uma frase que diga o que ela mostra. Código
é texto: em imagem, ele não pode ser copiado, pesquisado nem lido por leitores de
tela, e perde nitidez na impressão. Por isso, trechos de código vão em bloco de texto
com fonte monoespaçada, e imagens de código com fundo preto não são aceitas.

**Consistência entre seções (critério 9).** O texto é lido como um todo, e uma
contradição entre duas seções faz o leitor duvidar das duas. O mesmo número precisa
ter o mesmo valor em todas as partes, e a mesma afirmação precisa ter a mesma cautela
no Resumo, nos resultados e na conclusão.

**Terminologia (critério 3).** Em texto técnico, cada conceito tem um nome, e esse
nome não muda. Quando o mesmo conceito aparece com dois nomes, o leitor entende que
são duas coisas; quando o mesmo nome designa duas coisas, ele não sabe de qual se
fala.

**Redação (critério 1).** Frases longas, com várias informações encadeadas, obrigam
o leitor a reler. Um texto técnico fica mais claro com uma informação principal por
frase e com afirmações apoiadas em fatos, sem fórmulas de ênfase nem declarações de
importância que o texto não demonstra.

**Referências e normas (critério 10).** Toda afirmação que não é sua precisa de uma
fonte que o leitor consiga encontrar e conferir. Uma referência com DOI errado ou
que não existe compromete a confiança no texto inteiro.

**Elementos obrigatórios da resolução (critério 11).** A resolução de TCC define o
que um relatório técnico precisa conter, e a banca confere esses elementos. O
repositório público, por exemplo, permite que o código e os dados sejam examinados,
o que dá ao leitor uma forma de verificar o que o texto descreve.
