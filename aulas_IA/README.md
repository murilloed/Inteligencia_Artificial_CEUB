# Inteligencia Artificial

**Miniaula - Docente de Tecnologia da Informacao | CEUB**  
**Professor:** Prof. Dr. Murillo Carvalho  
**Tema:** Inteligencia Artificial  
**Duracao prevista da exposicao:** 15 minutos  
**Formato:** aula expositiva-dialogada com exemplo pratico e exercicio avaliativo

## 1. Apresentacao da aula

Esta aula apresenta uma visao introdutoria e aplicada sobre Inteligencia Artificial, com foco em agentes conversacionais, Processamento de Linguagem Natural, Aprendizado de Maquina, Aprendizagem Profunda, programacao para IA, automacao e agentes inteligentes.

A proposta e compreender a IA nao como "magica" ou como um simples chatbot, mas como um conjunto de tecnicas, sistemas, dados, modelos e decisoes de engenharia que permitem criar aplicacoes capazes de interpretar informacoes, reconhecer padroes, gerar respostas e executar acoes.

O exemplo principal da aula sera um **agente conversacional academico**, isto e, um sistema que pode receber perguntas de estudantes, interpretar a linguagem, consultar informacoes institucionais e responder ou encaminhar uma demanda.

## 2. Objetivos de aprendizagem

Ao final da aula, voce devera ser capaz de:

1. Diferenciar Inteligencia Artificial, Aprendizado de Maquina, Aprendizagem Profunda e Processamento de Linguagem Natural.
2. Explicar como agentes conversacionais transformam linguagem natural em respostas ou acoes.
3. Reconhecer o papel da automacao e dos agentes inteligentes em sistemas reais.
4. Identificar cuidados tecnicos e eticos no uso de sistemas de IA.

## 3. Pergunta inicial para reflexao

Antes de definir os conceitos, pense na seguinte pergunta:

> Quando um chatbot responde a um aluno, ele esta entendendo, calculando probabilidade ou seguindo regras?

A resposta mais adequada e: **depende da arquitetura do sistema**.

Alguns chatbots funcionam com regras fixas, como menus e respostas previamente cadastradas. Outros usam modelos de Aprendizado de Maquina para classificar perguntas. Sistemas mais recentes podem usar modelos de linguagem, bases de conhecimento, ferramentas externas e fluxos de automacao.

Por isso, um agente conversacional moderno pode combinar:

- regras de negocio;
- modelos estatisticos;
- aprendizagem profunda;
- Processamento de Linguagem Natural;
- integracao com bancos de dados;
- chamadas a APIs;
- supervisao humana;
- automacao de tarefas.

## 4. Ideia central da aula

Inteligencia Artificial nao e apenas "um robo que conversa".

IA e um campo da computacao dedicado a construir sistemas capazes de executar tarefas que, em algum grau, associamos a inteligencia humana, como:

- perceber dados;
- reconhecer padroes;
- classificar informacoes;
- tomar decisoes;
- recomendar opcoes;
- dialogar com pessoas;
- planejar acoes;
- agir em um ambiente.

Hoje, os agentes conversacionais tornam essa ideia mais visivel porque combinam varias areas:

- **PLN**, para lidar com linguagem humana;
- **Aprendizado de Maquina**, para reconhecer padroes;
- **Aprendizagem Profunda**, para representar relacoes complexas;
- **programacao**, para integrar dados, regras e sistemas;
- **automacao**, para transformar uma resposta em uma acao concreta.

## 5. Mapa conceitual da Inteligencia Artificial

Uma forma simples de organizar os conceitos e pensar na seguinte relacao:

```text
Inteligencia Artificial
├── Sistemas de IA
├── Aprendizado de Maquina
│   └── Aprendizagem Profunda
├── Processamento de Linguagem Natural
│   └── Agentes Conversacionais
└── Automacao e Agentes Inteligentes
```

### 5.1 Inteligencia Artificial

Inteligencia Artificial e a area ampla que busca criar sistemas capazes de realizar tarefas que exigem algum tipo de raciocinio, percepcao, adaptacao ou tomada de decisao.

Exemplos:

- assistentes virtuais;
- sistemas de recomendacao;
- reconhecimento facial;
- traducao automatica;
- diagnostico auxiliado por computador;
- filtros de spam;
- chatbots;
- veiculos autonomos;
- ferramentas de geracao de texto e imagem.

### 5.2 Sistemas de Inteligencia Artificial

Um sistema de IA nao e apenas um modelo. Ele normalmente envolve varios componentes trabalhando juntos.

Um sistema real pode conter:

- dados de entrada;
- modelo de IA;
- regras de negocio;
- banco de dados;
- interface com usuario;
- mecanismos de seguranca;
- logs de monitoramento;
- avaliacao de desempenho;
- integracao com outros sistemas.

Em outras palavras: **um modelo pode ser o coracao da solucao, mas o sistema inteiro e o corpo que faz a IA funcionar no mundo real**.

### 5.3 Aprendizado de Maquina

Aprendizado de Maquina, ou Machine Learning, e uma subarea da IA em que o sistema aprende padroes a partir de dados.

Em vez de programar manualmente todas as regras, fornecemos exemplos para que o algoritmo encontre relacoes.

Exemplo:

Uma instituicao pode ter varias perguntas historicas feitas por estudantes:

- "Como faco minha matricula?"
- "Quando comeca o semestre?"
- "Perdi a prova. Posso pedir segunda chamada?"
- "Tenho boleto em aberto. Com quem falo?"

Se essas perguntas estiverem rotuladas por categoria, como `matricula`, `calendario`, `segunda_chamada` e `financeiro`, um modelo pode aprender a classificar novas perguntas.

### 5.4 Aprendizagem Profunda

Aprendizagem Profunda, ou Deep Learning, e uma familia de tecnicas de Aprendizado de Maquina baseada em redes neurais com varias camadas.

Ela e muito usada quando os dados sao complexos, como:

- textos;
- imagens;
- audio;
- videos;
- fala;
- grandes volumes de dados nao estruturados.

Modelos de linguagem modernos, usados em agentes conversacionais avancados, geralmente utilizam arquiteturas de aprendizagem profunda.

### 5.5 Processamento de Linguagem Natural

Processamento de Linguagem Natural, ou PLN, e a area da IA que trabalha com linguagem humana.

O PLN permite que sistemas computacionais possam:

- receber textos;
- identificar palavras importantes;
- reconhecer intencoes;
- extrair entidades;
- classificar mensagens;
- gerar respostas;
- resumir documentos;
- traduzir textos;
- buscar informacoes em bases textuais.

Em um agente conversacional, o PLN ajuda o sistema a lidar com perguntas escritas de forma natural, como:

> Quais documentos preciso para matricula?

O sistema precisa perceber que a intencao principal e provavelmente `matricula` e que o estudante deseja uma lista de documentos.

### 5.6 Agentes conversacionais

Agentes conversacionais sao sistemas que interagem com pessoas por meio de linguagem natural, geralmente em formato de conversa.

Eles podem aparecer como:

- chatbots em sites;
- assistentes virtuais;
- atendentes automatizados;
- bots em aplicativos de mensagem;
- copilotos em ferramentas de trabalho;
- interfaces conversacionais em sistemas educacionais.

Um agente conversacional pode apenas responder perguntas simples ou pode executar acoes, como abrir chamados, consultar dados ou encaminhar demandas.

### 5.7 Automacao e agentes inteligentes

Automacao e o uso de tecnologia para executar processos com pouca ou nenhuma intervencao humana.

Um agente inteligente vai alem de responder: ele pode perceber um contexto, escolher uma acao e agir para atingir um objetivo.

Exemplo:

Um estudante pergunta:

> Preciso pedir segunda chamada. Como faco?

Um agente mais simples apenas responde com instrucoes.  
Um agente mais completo pode:

- identificar a intencao;
- consultar as regras da instituicao;
- verificar prazo;
- enviar link do formulario;
- registrar o atendimento;
- encaminhar o caso para analise humana se houver excecao.

## 6. Sintese do mapa conceitual

Uma frase ajuda a organizar os conceitos:

> IA e o campo; Aprendizado de Maquina e uma estrategia; Aprendizagem Profunda e uma familia de modelos; PLN e uma area de aplicacao; agente conversacional e uma interface; automacao e o uso da IA para executar processos.

Essa frase e importante porque evita confusoes comuns.

Por exemplo:

- Todo chatbot e IA? Nem sempre. Alguns sao apenas sistemas de regras.
- Todo sistema de IA usa deep learning? Nao.
- Todo modelo de IA e um agente? Nao.
- PLN e a mesma coisa que IA? Nao. PLN e uma area dentro do campo de IA.
- Automacao e IA sao sinonimos? Nao. Automacao pode usar IA, mas tambem pode ser baseada em regras simples.

## 7. Como funciona um agente conversacional

Vamos considerar um exemplo de atendimento academico automatizado.

Entrada do usuario:

> Quais documentos preciso para matricula?

Para responder bem, o sistema precisa realizar uma sequencia de etapas.

### 7.1 Pipeline simplificado

```text
Entrada do usuario
      ↓
Processamento de Linguagem Natural
      ↓
Modelo de IA
      ↓
Base de conhecimento ou ferramenta
      ↓
Resposta ao usuario
      ↓
Acao automatizada ou encaminhamento
```

### 7.2 Etapa 1: entrada em linguagem natural

O estudante escreve uma pergunta como falaria com uma pessoa.

Exemplos:

- "Quais documentos preciso para matricula?"
- "Quando comeca o semestre?"
- "Como peco segunda chamada?"
- "Meu boleto nao apareceu. O que faco?"

Essas perguntas podem ter erros, abreviacoes, variacoes de escrita e diferentes formas de dizer a mesma coisa.

### 7.3 Etapa 2: Processamento de Linguagem Natural

Nessa etapa, o sistema transforma a linguagem humana em uma representacao que possa ser processada.

O sistema pode realizar:

- tokenizacao: separacao do texto em unidades menores;
- normalizacao: tratamento de maiusculas, acentos, pontuacao e variacoes;
- identificacao de intencao: descobrir o que o usuario quer;
- extracao de entidades: encontrar informacoes especificas, como curso, data, documento ou setor;
- analise semantica: aproximar perguntas parecidas pelo significado.

No exemplo:

> Quais documentos preciso para matricula?

A intencao pode ser classificada como `matricula`.  
A entidade relevante pode ser `documentos`.

### 7.4 Etapa 3: modelo de IA

O modelo de IA pode atuar de varias formas:

- classificar a pergunta;
- recuperar informacoes relevantes;
- gerar uma resposta;
- estimar a confianca da resposta;
- decidir se deve responder ou encaminhar para um humano.

Em sistemas simples, pode haver um classificador de intencoes.  
Em sistemas mais avancados, pode haver um modelo de linguagem conectado a uma base de conhecimento.

### 7.5 Etapa 4: base de conhecimento ou ferramenta

Um agente confiavel nao deve responder apenas "de memoria".

Ele pode consultar:

- regulamentos academicos;
- calendario institucional;
- documentos oficiais;
- perguntas frequentes;
- sistemas internos;
- banco de dados;
- APIs;
- historico de atendimentos.

Essa etapa e essencial para reduzir respostas incorretas.

### 7.6 Etapa 5: resposta em linguagem clara

Depois de interpretar a pergunta e consultar as informacoes, o sistema produz uma resposta compreensivel para o usuario.

Uma boa resposta deve ser:

- clara;
- objetiva;
- correta;
- contextualizada;
- baseada em fonte confiavel;
- limitada ao escopo do agente.

### 7.7 Etapa 6: acao automatizada

Em alguns casos, responder nao basta.

O sistema pode executar uma acao, como:

- abrir protocolo;
- enviar link;
- registrar atendimento;
- consultar status;
- encaminhar para um setor;
- avisar que o caso exige atendimento humano.

Por isso, um agente conversacional moderno pode combinar conversa e automacao.

## 8. Exemplo completo

Pergunta:

> Quais documentos preciso para matricula?

Possivel funcionamento:

1. O estudante envia a pergunta.
2. O sistema identifica a intencao `matricula`.
3. O sistema identifica que o estudante quer `documentos`.
4. O agente consulta a base de conhecimento atualizada.
5. O agente gera uma resposta com a lista de documentos.
6. O agente pode oferecer um link para o procedimento oficial.

Possivel resposta:

> Para realizar a matricula, consulte a lista oficial de documentos exigidos para o seu curso e periodo de ingresso. Posso enviar o link da pagina de matricula ou abrir um atendimento caso voce tenha uma situacao especifica.

## 9. Mensagem importante

Um bom agente conversacional nao e apenas um gerador de texto.

Ele precisa de:

- contexto;
- limites;
- base confiavel;
- integracao com sistemas;
- regras de negocio;
- criterios de confiabilidade;
- avaliacao constante;
- possibilidade de encaminhamento humano.

## 10. Programacao para IA

A programacao continua essencial em sistemas de IA.

Mesmo quando usamos modelos prontos, alguem precisa:

- organizar os dados;
- definir regras de negocio;
- integrar APIs;
- construir a interface;
- tratar erros;
- criar mecanismos de seguranca;
- monitorar o funcionamento;
- registrar logs;
- testar respostas;
- atualizar bases de conhecimento.

Portanto, IA nao substitui engenharia de software. Ela aumenta a importancia de boas praticas de engenharia.

### 10.1 Pseudocodigo do exemplo

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

### 10.2 Interpretando o pseudocodigo

A linha:

```python
pergunta = receber_texto_usuario()
```

representa a entrada do estudante.

A linha:

```python
intencao = classificar_intencao(pergunta)
```

representa o uso de PLN ou Aprendizado de Maquina para descobrir o objetivo da pergunta.

O bloco:

```python
if intencao == "matricula":
```

mostra uma regra de negocio. Se a pergunta for sobre matricula, o sistema consulta uma base especifica.

O bloco:

```python
elif intencao == "financeiro":
```

mostra que nem toda pergunta deve ser respondida diretamente pelo agente. Algumas devem ser encaminhadas.

O bloco:

```python
else:
    resposta = pedir_esclarecimento()
```

mostra uma boa pratica: quando o sistema nao entende, ele nao deve inventar. Ele deve pedir mais informacoes.

## 11. Formas de aprendizado em IA

### 11.1 Aprendizado supervisionado

No aprendizado supervisionado, o modelo aprende com exemplos rotulados.

Exemplo:

| Pergunta do estudante | Rotulo esperado |
| --- | --- |
| "Como faco minha matricula?" | matricula |
| "Quando comeca o semestre?" | calendario |
| "Como peço segunda chamada?" | segunda_chamada |
| "Meu boleto nao apareceu" | financeiro |

Depois de treinar com muitos exemplos, o modelo tenta classificar novas perguntas.

### 11.2 Aprendizado nao supervisionado

No aprendizado nao supervisionado, o modelo busca padroes sem receber rotulos prontos.

Exemplo:

Um conjunto grande de perguntas de alunos pode ser agrupado automaticamente por similaridade. Depois, a equipe analisa os grupos e percebe temas recorrentes, como matricula, provas, estagio, financeiro e suporte tecnico.

### 11.3 Aprendizado por reforco

No aprendizado por reforco, um agente aprende por interacao com um ambiente, recebendo recompensas ou penalidades.

Exemplo simplificado:

Um agente de atendimento pode ser ajustado para priorizar respostas que resolvem a demanda do aluno, reduzem retrabalho e evitam encaminhamentos desnecessarios.

Em sistemas reais, esse tipo de abordagem exige muito cuidado, pois recompensas mal definidas podem gerar comportamentos inadequados.

### 11.4 Aprendizagem profunda

Na aprendizagem profunda, redes neurais aprendem representacoes complexas dos dados.

No caso de textos, essas representacoes ajudam o sistema a perceber relacoes de significado.

Por exemplo, as frases abaixo sao diferentes, mas podem ter intencao semelhante:

- "Quais documentos preciso para matricula?"
- "O que tenho que entregar para me matricular?"
- "Que documentos a faculdade pede na matricula?"

Um bom modelo deve perceber que todas tratam do mesmo tema.

## 12. Riscos e limites da IA

Sistemas de IA podem ser muito uteis, mas tambem apresentam riscos.

### 12.1 Alucinacao

Alucinacao ocorre quando o modelo produz uma resposta plausivel, mas incorreta.

Exemplo:

O agente informa um prazo de matricula que nao existe ou cita uma regra desatualizada.

Como reduzir:

- consultar base oficial;
- mostrar fonte;
- limitar respostas fora do escopo;
- usar revisao humana em temas sensiveis;
- testar com casos reais.

### 12.2 Vies

Vies ocorre quando os dados ou o modelo reproduzem distorcoes, desigualdades ou padroes injustos.

Exemplo:

Um sistema treinado com dados historicos pode tratar grupos de usuarios de forma diferente sem justificativa adequada.

Como reduzir:

- avaliar dados de treinamento;
- testar resultados por diferentes perfis;
- criar criterios transparentes;
- revisar decisoes automatizadas.

### 12.3 Privacidade

Perguntas e bases consultadas podem conter dados sensiveis.

Exemplos:

- dados financeiros;
- documentos pessoais;
- informacoes academicas;
- historico de atendimento;
- informacoes de saude ou vulnerabilidade.

Como reduzir:

- evitar expor dados pessoais;
- controlar acesso;
- registrar apenas o necessario;
- seguir politicas de protecao de dados;
- prever encaminhamento humano para casos sensiveis.

### 12.4 Explicabilidade

Nem sempre e facil explicar por que um modelo tomou determinada decisao.

Isso e especialmente importante quando a IA afeta direitos, acesso a servicos ou decisoes institucionais.

Como reduzir:

- manter regras claras;
- registrar criterios;
- usar modelos interpretaveis quando necessario;
- explicar limites do sistema;
- permitir revisao humana.

### 12.5 Avaliacao

Sistemas de IA precisam ser avaliados com metricas e casos reais.

Possiveis metricas:

- acuracia na classificacao de intencoes;
- taxa de respostas corretas;
- satisfacao dos usuarios;
- tempo medio de resposta;
- taxa de resolucao;
- taxa de encaminhamento correto;
- numero de erros criticos;
- taxa de respostas com baixa confianca.

## 13. Boas praticas para sistemas de IA

Para construir ou avaliar um agente conversacional, algumas boas praticas sao essenciais:

1. Definir claramente o objetivo do agente.
2. Limitar o escopo de atendimento.
3. Usar fontes confiaveis e atualizadas.
4. Registrar interacoes importantes.
5. Prever fallback humano.
6. Medir a qualidade das respostas.
7. Atualizar a base de conhecimento.
8. Testar com perguntas reais.
9. Tratar dados sensiveis com cuidado.
10. Informar ao usuario quando ele esta interagindo com um sistema automatizado.

## 14. Pergunta de fechamento

Considere a seguinte situacao:

> Um chatbot consulta documentos, responde em linguagem natural e abre chamados automaticamente.

Quais componentes de IA aparecem nesse sistema?

Resposta esperada:

- Processamento de Linguagem Natural;
- modelo de IA ou classificador;
- base de conhecimento;
- regras de negocio;
- integracao com sistemas;
- geracao de resposta;
- automacao;
- agente inteligente;
- supervisao ou encaminhamento humano.

## 15. Fechamento conceitual

A Inteligencia Artificial contemporanea deve ser entendida como um ecossistema.

Nesse ecossistema:

- modelos aprendem com dados;
- programas organizam fluxos;
- agentes interagem com pessoas e ferramentas;
- bases de conhecimento oferecem informacao confiavel;
- automacoes transformam respostas em acoes;
- metricas ajudam a avaliar qualidade;
- principios eticos orientam limites e responsabilidades.

Portanto, estudar IA exige tanto compreensao tecnica quanto pensamento critico.

## 16. Glossario rapido

**IA:** campo da computacao dedicado a sistemas capazes de executar tarefas associadas a inteligencia.  
**Modelo:** componente treinado ou configurado para realizar uma tarefa, como classificar, prever ou gerar texto.  
**Aprendizado de Maquina:** abordagem em que sistemas aprendem padroes a partir de dados.  
**Aprendizagem Profunda:** tipo de Aprendizado de Maquina baseado em redes neurais profundas.  
**PLN:** area que processa e gera linguagem humana.  
**Agente conversacional:** sistema que interage com usuarios por conversa.  
**Automacao:** execucao de processos com pouca ou nenhuma intervencao humana.  
**Fallback humano:** encaminhamento para uma pessoa quando o sistema nao consegue ou nao deve resolver sozinho.  
**Alucinacao:** resposta plausivel, mas incorreta, gerada por um modelo.  
**Vies:** distorcao ou injustica reproduzida por dados, modelos ou decisoes automatizadas.

## 17. O que voce deve levar desta aula

1. IA e um campo amplo, nao apenas chatbots.
2. Agentes conversacionais integram linguagem, modelos, dados, regras e automacao.
3. PLN permite tratar perguntas em linguagem humana.
4. Aprendizado de Maquina permite reconhecer padroes em dados.
5. Aprendizagem Profunda permite lidar com representacoes complexas.
6. Programacao continua essencial para transformar IA em sistema real.
7. Um agente confiavel precisa de limites, fontes, metricas e fallback humano.
8. Usar IA tambem exige responsabilidade tecnica, etica e institucional.


