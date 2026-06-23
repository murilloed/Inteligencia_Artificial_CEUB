# Miniaula - Inteligencia Artificial

Processo seletivo docente TI CEUB  
Tema escolhido: Inteligencia Artificial  
Duracao da miniaula: 15 minutos  
Formato: aula expositiva-dialogada com exemplo pratico e exercicio avaliativo

## 1. Intencao da aula

Ao final da miniaula, o estudante devera ser capaz de:

1. Diferenciar Inteligencia Artificial, Aprendizado de Maquina, Aprendizagem Profunda e Processamento de Linguagem Natural.
2. Explicar como agentes conversacionais transformam linguagem natural em respostas ou acoes.
3. Reconhecer o papel da automacao e dos agentes inteligentes em sistemas reais.
4. Identificar cuidados tecnicos e eticos no uso de IA.

## 2. Ideia central

Inteligencia Artificial nao e apenas "um robo que conversa". Ela e um campo da computacao dedicado a construir sistemas capazes de perceber dados, reconhecer padroes, tomar decisoes e agir em algum ambiente. Hoje, agentes conversacionais tornam essa ideia visivel porque combinam PLN, aprendizado de maquina, aprendizagem profunda, programacao e automacao.

Frase-guia para a banca:

"Nesta miniaula, eu vou usar agentes conversacionais como porta de entrada para organizar os principais conceitos de IA: dos sistemas inteligentes ao aprendizado profundo, chegando a automacao com agentes."

## 3. Roteiro cronometrado de 15 minutos

### Minuto 0-1 - Abertura e problema motivador

Pergunta para a turma:

"Quando um chatbot responde a um aluno, ele esta entendendo, calculando probabilidade ou seguindo regras?"

Objetivo da abertura:

Mostrar que IA envolve diferentes abordagens: regras, modelos estatisticos, aprendizagem profunda e agentes que executam tarefas.

Fala sugerida:

"A resposta curta e: depende da arquitetura. Alguns sistemas sao baseados em regras; outros usam modelos treinados em dados; e os sistemas mais recentes combinam linguagem natural, modelos de aprendizado profundo, ferramentas externas e fluxos de automacao."

### Minuto 1-4 - Mapa conceitual da IA

Organizar no quadro:

IA
-> Sistemas de IA
-> Aprendizado de Maquina
-> Aprendizagem Profunda
-> Processamento de Linguagem Natural
-> Agentes Conversacionais
-> Automacao e Agentes Inteligentes

Explicacoes rapidas:

- Inteligencia Artificial: area ampla que cria sistemas capazes de executar tarefas associadas a inteligencia, como classificar, recomendar, dialogar, planejar e decidir.
- Sistemas de IA: aplicacoes completas que usam dados, modelos, regras, interfaces e mecanismos de decisao.
- Aprendizado de Maquina: subarea em que o sistema aprende padroes a partir de dados, em vez de receber todas as regras explicitamente.
- Aprendizagem Profunda: tipo de aprendizado de maquina baseado em redes neurais com varias camadas, muito usado em imagens, fala e linguagem.
- PLN: area que permite processar, interpretar e gerar linguagem humana.
- Agentes inteligentes: sistemas que observam um contexto, decidem uma acao e atuam para atingir um objetivo.

Analogia didatica:

"IA e o campo; aprendizado de maquina e uma estrategia; aprendizagem profunda e uma familia de modelos; PLN e uma area de aplicacao; agente conversacional e uma interface; automacao e o uso da IA para executar processos."

### Minuto 4-8 - Como funciona um agente conversacional

Exemplo: atendimento academico automatizado.

Entrada do usuario:

"Quais documentos preciso para matricula?"

Pipeline simplificado:

1. Entrada em linguagem natural.
2. Processamento de Linguagem Natural: tokenizacao, representacao semantica e identificacao de intencao.
3. Modelo de IA: recupera informacao, classifica a pergunta ou gera resposta.
4. Base de conhecimento ou ferramenta: consulta regras, documentos ou sistemas internos.
5. Resposta: linguagem clara para o usuario.
6. Acao automatizada: abrir protocolo, enviar link, registrar atendimento ou encaminhar a um humano.

Mensagem importante:

"Um bom agente conversacional nao e apenas um gerador de texto. Ele precisa de contexto, limites, integracao com sistemas e criterios de confiabilidade."

### Minuto 8-11 - Programacao para IA e aprendizado

Mostrar um pseudocodigo simples:

```python
pergunta = receber_texto_usuario()
intencao = classificar_intencao(pergunta)

if intencao == "matricula":
    dados = buscar_base_conhecimento("matricula")
    resposta = gerar_resposta(pergunta, dados)
elif intencao == "financeiro":
    resposta = encaminhar_para_setor("financeiro")
else:
    resposta = pedir_esclarecimento()

enviar_resposta(resposta)
```

Ponto didatico:

A programacao continua essencial. A IA nao substitui arquitetura de software, engenharia de dados, testes, seguranca, governanca e integracao.

Conectar com aprendizado:

- No aprendizado supervisionado, treinamos com exemplos rotulados, como perguntas e categorias.
- No aprendizado nao supervisionado, buscamos grupos ou padroes sem rotulos.
- No aprendizado por reforco, o agente aprende por recompensa em um ambiente.
- Na aprendizagem profunda, redes neurais aprendem representacoes complexas, como relacoes de significado em textos.

### Minuto 11-13 - Riscos, limites e boas praticas

Pontos para destacar:

- Alucinacao: o modelo pode produzir resposta plausivel, mas incorreta.
- Vies: dados de treinamento podem reproduzir desigualdades.
- Privacidade: prompts e bases consultadas podem conter dados sensiveis.
- Explicabilidade: nem sempre e facil justificar uma decisao automatizada.
- Avaliacao: sistemas de IA precisam ser testados com metricas e casos reais.

Boas praticas:

- Definir objetivo do agente.
- Limitar escopo.
- Usar fontes confiaveis.
- Registrar interacoes importantes.
- Prever fallback humano.
- Medir qualidade das respostas.

### Minuto 13-15 - Fechamento e verificacao rapida

Pergunta final:

"Se eu digo que um chatbot consulta documentos, responde em linguagem natural e abre chamados automaticamente, quais componentes de IA aparecem nesse sistema?"

Resposta esperada:

PLN, modelo de linguagem ou classificador, base de conhecimento, programacao de integracao, automacao e agente inteligente.

Fechamento:

"A Inteligencia Artificial contemporanea deve ser entendida como um ecossistema: modelos aprendem com dados, programas organizam fluxos, agentes interagem com pessoas e ferramentas, e a automacao transforma respostas em acoes."

## 4. Sugestao de slides

### Slide 1 - Inteligencia Artificial em sistemas reais

Subtitulo: de modelos que aprendem a agentes que conversam e agem

Conteudo:

- IA como campo amplo
- Agentes conversacionais como exemplo integrador
- Objetivo: entender conceitos e arquitetura

### Slide 2 - Mapa da IA

Conteudo visual:

IA -> ML -> Deep Learning

IA -> PLN -> Agentes Conversacionais

IA -> Agentes Inteligentes -> Automacao

Mensagem:

"Os conceitos se sobrepoem, mas nao sao sinonimos."

### Slide 3 - Anatomia de um agente conversacional

Fluxo:

Usuario -> PLN -> Modelo -> Base/Ferramenta -> Resposta -> Acao

Exemplo:

Pergunta sobre matricula -> consulta norma academica -> responde -> abre protocolo.

### Slide 4 - Programacao para IA

Conteudo:

- Dados
- Modelo
- Regras de negocio
- APIs
- Testes
- Monitoramento

Mensagem:

"Sem engenharia de software, IA vira demonstracao; com engenharia, vira sistema."

### Slide 5 - Limites e responsabilidades

Conteudo:

- Alucinacao
- Vies
- Privacidade
- Explicabilidade
- Fallback humano

Fechamento:

"IA boa nao e so inteligente; e verificavel, util e responsavel."

## 5. Exercicio avaliativo para entregar a banca

### Enunciado

Considere o seguinte cenario:

Uma instituicao de ensino deseja criar um agente conversacional para apoiar estudantes. O agente deve responder perguntas sobre matricula, calendario academico e segunda chamada de provas. Quando a pergunta envolver situacao financeira, o agente deve encaminhar o aluno ao setor responsavel. Quando a pergunta envolver documentos oficiais, o agente deve consultar uma base de conhecimento atualizada antes de responder.

Responda:

1. Identifique pelo menos quatro componentes de IA ou de software presentes nesse sistema.
2. Explique a diferenca entre Processamento de Linguagem Natural e Aprendizado de Maquina no contexto do agente.
3. Indique uma situacao em que a automacao deve ser limitada por intervencao humana.
4. Proponha uma metrica para avaliar se o agente esta funcionando bem.

### Gabarito esperado

1. Componentes possiveis:
   - Interface conversacional.
   - Modulo de PLN para interpretar a pergunta.
   - Classificador de intencao.
   - Modelo de linguagem ou mecanismo de geracao de resposta.
   - Base de conhecimento.
   - Integracao com sistemas internos.
   - Regras de negocio.
   - Mecanismo de encaminhamento humano.
   - Logs e monitoramento.

2. Diferenca:
   - PLN e a area voltada ao tratamento da linguagem humana, como interpretar perguntas, extrair intencoes e gerar respostas.
   - Aprendizado de Maquina e a abordagem pela qual modelos aprendem padroes a partir de dados, por exemplo, associar perguntas a categorias como "matricula", "calendario" ou "financeiro".

3. Exemplo de intervencao humana:
   - Casos financeiros, pedidos com dados sensiveis, excecoes academicas, conflito entre informacoes ou respostas com baixa confianca.

4. Metricas possiveis:
   - Acuracia na classificacao de intencoes.
   - Taxa de respostas corretas.
   - Taxa de resolucao sem encaminhamento.
   - Satisfacao do usuario.
   - Tempo medio de resposta.
   - Taxa de escalonamento adequado para atendimento humano.

## 6. Versao curta para fala final

"Nesta aula, vimos que IA e um campo amplo e que agentes conversacionais sao uma boa forma de integrar seus principais conceitos. Um agente desse tipo usa PLN para lidar com linguagem, aprendizado de maquina para reconhecer padroes, aprendizagem profunda em modelos mais sofisticados, programacao para integrar dados e regras, e automacao para transformar respostas em acoes. O desafio docente e tecnico e mostrar que IA nao e magia: e arquitetura, dados, modelos, avaliacao e responsabilidade."

## 7. Dicas de apresentacao para a banca

- Comece com uma pergunta, nao com definicao.
- Use o quadro para desenhar o mapa conceitual.
- Evite tentar explicar toda a historia da IA em 15 minutos.
- Mostre que voce domina tanto conceito quanto aplicacao.
- Termine com o exercicio avaliativo e o gabarito, pois isso evidencia planejamento pedagogico.
- Mantenha a aula em ritmo de graduacao: conceitual, aplicada e verificavel.


