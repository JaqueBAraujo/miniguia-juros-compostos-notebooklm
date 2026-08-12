# 📚 Miniguia de Juros Compostos com NotebookLM

Projeto desenvolvido como parte de um desafio da **DIO**, com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de **aprendizagem ativa**, utilizando o **NotebookLM** para organizar fontes, formular perguntas, testar diferentes estratégias de prompts e consolidar conhecimento.

O tema escolhido para o caderno foi:

> **Juros Compostos e o Impacto do Tempo nos Investimentos**

---

## 🎯 1. Contexto e Objetivos

A educação financeira é fundamental para a tomada de decisões conscientes relacionadas a investimentos, financiamentos, empréstimos, poupança e planejamento financeiro.

Dentro desse contexto, os **juros compostos** representam um dos conceitos mais importantes da matemática financeira, pois estão presentes tanto no crescimento de investimentos quanto na evolução de dívidas.

O objetivo deste projeto foi utilizar o NotebookLM para estudar o assunto a partir de fontes previamente selecionadas, avaliando também como diferentes formas de elaborar perguntas e prompts influenciam as respostas produzidas pela IA.

### Objetivo geral

Compreender o funcionamento dos juros compostos e analisar como capital, taxa de juros e tempo influenciam o crescimento de um investimento.

### Objetivos específicos

* Compreender o conceito de juros;
* Diferenciar juros simples de juros compostos;
* Entender o conceito de "juros sobre juros";
* Identificar capital, taxa, período e montante;
* Compreender a fórmula dos juros compostos;
* Analisar a influência do tempo sobre um investimento;
* Entender a influência da taxa de juros;
* Relacionar juros compostos com investimentos e dívidas;
* Experimentar diferentes estratégias de prompts;
* Avaliar criticamente respostas geradas por IA utilizando as fontes originais.

---

# 📖 2. Curadoria de Fontes

Para construção do caderno temático, foram selecionadas fontes abertas de instituições públicas e educacionais.

Foram utilizados materiais do **Banco Central do Brasil**, **Comissão de Valores Mobiliários (CVM)** e **eduCAPES**.

### Fonte 1 — Banco Central do Brasil

**Cidadania Financeira**

Conteúdo institucional relacionado à educação financeira e ao desenvolvimento da capacidade dos cidadãos de tomar decisões financeiras conscientes.

**Utilização no estudo:** contextualização da importância da educação financeira.

Link:

https://www.bcb.gov.br/cidadaniafinanceira

---

### Fonte 2 — Banco Central do Brasil

**Série Cidadania Financeira — Competências em Educação Financeira**

Material utilizado para analisar o conhecimento financeiro da população e identificar dificuldades relacionadas à matemática financeira e aos juros.

**Utilização no estudo:** fundamentação da importância do aprendizado sobre juros e juros compostos.

---

### Fonte 3 — eduCAPES

**Noções de Matemática Financeira com foco em Educação Financeira**

Material educacional utilizado para estudar conceitos matemáticos relacionados a porcentagem, juros simples e juros compostos.

**Utilização no estudo:** fundamentação matemática e exemplos didáticos.

Link:

https://educapes.capes.gov.br/handle/capes/205203

---

### Fonte 4 — Comissão de Valores Mobiliários (CVM)

**Portal do Investidor**

Material educacional utilizado para relacionar conceitos financeiros com investimentos e decisões financeiras.

**Utilização no estudo:** contextualização dos conceitos dentro do universo dos investimentos.

Link:

https://www.gov.br/investidor/

---

# 🤖 3. Utilização do NotebookLM

Após a seleção das fontes, foi criado um caderno temático no NotebookLM.

As quatro fontes foram adicionadas ao mesmo caderno para que as respostas da IA pudessem ser construídas utilizando o material selecionado.

Antes dos experimentos principais, foi realizada uma pergunta de validação:

> Quais são os principais assuntos abordados nas fontes deste caderno? Para cada assunto, indique qual fonte o apresenta.

O objetivo foi verificar se o NotebookLM havia processado corretamente os documentos e conseguia relacionar informações provenientes das diferentes fontes.

---

# 🧠 4. Engenharia de Prompts

Uma das propostas do projeto foi analisar como a construção do prompt influencia a resposta produzida pela IA.

Para isso, foram utilizados prompts com diferentes níveis de detalhamento.

---

## Experimento 1 — Prompt simples

### Prompt

> Explique juros compostos.

### Resposta obtida

O NotebookLM definiu juros compostos como um mecanismo no qual os juros incidem não somente sobre o capital inicial, mas também sobre os juros acumulados anteriormente.

A resposta utilizou a expressão **"juros sobre juros"** e apresentou um exemplo envolvendo um capital de R$ 100,00 rendendo 2% ao ano.

Também relacionou o assunto à educação financeira e apresentou dados provenientes das fontes do Banco Central.

### Resultado observado

Mesmo sendo extremamente curto, o prompt conseguiu gerar uma resposta relevante.

Entretanto, o usuário não determinou:

* o nível de conhecimento esperado;
* a estrutura da resposta;
* quais conceitos deveriam ser abordados;
* o nível de profundidade;
* o formato dos exemplos;
* quais fontes deveriam receber maior atenção.

Isso deixou diversas decisões sob responsabilidade da própria IA.

---

## Experimento 2 — Prompt contextualizado

### Prompt

> Com base exclusivamente nas fontes deste caderno, explique o conceito de juros compostos para uma pessoa que está começando a estudar educação financeira. Diferencie juros simples de juros compostos e apresente um exemplo prático. Utilize as fontes do caderno para fundamentar a resposta.

### Objetivo do experimento

O segundo prompt adiciona quatro elementos que não estavam presentes no primeiro:

1. delimitação das fontes;
2. definição do público-alvo;
3. solicitação de comparação;
4. solicitação de exemplo prático.

### Resposta obtida

> **INSERIR AQUI A RESPOSTA/RESUMO REAL OBTIDO NO NOTEBOOKLM.**

### Resultado observado

> **REGISTRAR AQUI AS DIFERENÇAS ENCONTRADAS EM RELAÇÃO AO EXPERIMENTO 1.**

---

## Experimento 3 — Prompt estruturado

### Prompt

> Atue como um professor de educação financeira. Utilizando exclusivamente as fontes deste caderno, ensine juros compostos para um aluno iniciante.
>
> Organize a resposta nas seguintes etapas:
>
> 1. definição de juros;
> 2. definição de juros compostos;
> 3. diferença entre juros simples e compostos;
> 4. explicação da fórmula matemática;
> 5. exemplo numérico;
> 6. influência da taxa de juros;
> 7. influência do tempo;
> 8. aplicação em investimentos;
> 9. aplicação em dívidas.
>
> Ao final, apresente três perguntas para verificar se compreendi o assunto.
>
> Indique as fontes utilizadas para sustentar as explicações e não utilize informações externas às fontes deste caderno.

### Objetivo do experimento

Neste terceiro teste, o prompt define:

* papel da IA;
* público-alvo;
* fontes permitidas;
* sequência da explicação;
* conceitos obrigatórios;
* utilização de exemplos;
* aplicação prática;
* mecanismo de avaliação da aprendizagem.

### Resposta obtida

> **INSERIR AQUI A RESPOSTA/RESUMO REAL OBTIDO NO NOTEBOOKLM.**

### Resultado observado

> **REGISTRAR AQUI AS DIFERENÇAS ENCONTRADAS EM RELAÇÃO AOS EXPERIMENTOS ANTERIORES.**

---

# 🔎 5. Cicatrizes e Troubleshooting

Uma parte importante do experimento foi perceber que utilizar uma IA baseada em fontes não elimina a necessidade de verificar as informações apresentadas.

Durante o primeiro experimento, por exemplo, o NotebookLM apresentou uma informação estatística sobre o domínio de juros simples e compostos pela população.

Isso demonstrou a necessidade de consultar a referência indicada pela própria ferramenta para verificar:

1. qual era exatamente o indicador utilizado;
2. qual população havia sido pesquisada;
3. se o percentual correspondia especificamente aos juros compostos ou a uma combinação de questões;
4. se a interpretação apresentada pela IA correspondia ao texto original.

Essa experiência reforçou um dos principais aprendizados do projeto:

> **Uma resposta acompanhada de referência ainda precisa ser interpretada e validada.**

Outro aprendizado foi perceber que prompts genéricos podem produzir boas respostas, mas oferecem pouco controle sobre o conteúdo apresentado.

A inclusão de contexto, público-alvo, estrutura esperada e restrições torna a interação com a IA mais previsível e adequada ao objetivo de aprendizagem.

---

# 📘 6. Miniguia de Estudo

## 6.1 O que são juros?

Juros representam uma remuneração ou um custo associado à utilização do dinheiro durante determinado período.

Em um investimento, podem representar a remuneração recebida pelo capital aplicado.

Em uma dívida, podem representar o custo associado ao dinheiro utilizado.

---

## 6.2 Juros simples

No regime de juros simples, os juros são calculados utilizando o capital inicial como referência.

Uma representação matemática é:

```text
J = C × i × n
```

Onde:

* `J` = juros;
* `C` = capital inicial;
* `i` = taxa de juros;
* `n` = quantidade de períodos.

---

## 6.3 Juros compostos

Nos juros compostos, os juros de cada período são incorporados ao saldo acumulado.

Consequentemente, o saldo resultante passa a ser utilizado como base para o cálculo do período seguinte.

Por esse motivo, o mecanismo é frequentemente chamado de:

> **juros sobre juros**

A fórmula do montante é:

```text
M = C × (1 + i)ⁿ
```

Onde:

* `M` = montante;
* `C` = capital inicial;
* `i` = taxa de juros;
* `n` = quantidade de períodos.

---

## 6.4 Exemplo

Considere hipoteticamente:

```text
Capital inicial = R$ 10.000,00
Taxa = 10% ao ano
Período = 10 anos
```

Aplicando a fórmula:

```text
M = 10.000 × (1 + 0,10)¹⁰
```

Resultado aproximado:

```text
M = R$ 25.937,42
```

O exemplo demonstra a importância da capitalização ao longo do tempo.

> O cálculo possui finalidade exclusivamente educacional e desconsidera impostos, inflação, taxas e outras variáveis existentes em investimentos reais.

---

## 6.5 A importância do tempo

O tempo exerce grande influência sobre os juros compostos.

Cada novo período permite que os juros acumulados anteriormente façam parte da base de cálculo dos juros seguintes.

Por isso, períodos maiores aumentam o efeito da capitalização composta.

---

## 6.6 A importância da taxa

A taxa determina o percentual de crescimento do capital em cada período.

Em horizontes longos, diferenças nas taxas podem produzir diferenças relevantes no montante acumulado.

É importante observar também se a unidade da taxa corresponde à unidade utilizada no período.

Por exemplo, uma taxa anual deve ser analisada em conjunto com períodos expressos adequadamente em anos ou convertida de forma apropriada.

---

## 6.7 Investimentos e dívidas

Os juros compostos não devem ser entendidos apenas como um mecanismo relacionado a investimentos.

O mesmo princípio de capitalização pode estar presente em diferentes operações financeiras.

Para quem investe, a capitalização pode contribuir para o crescimento do patrimônio ao longo do tempo.

Em operações de crédito e endividamento, juros e outros encargos podem aumentar significativamente o valor devido.

Por isso, compreender taxas, prazos e condições é uma habilidade importante para a educação financeira.

---

# 📖 7. Glossário

| Conceito            | Definição                                                                           |
| ------------------- | ----------------------------------------------------------------------------------- |
| **Aporte**          | Valor acrescentado a um investimento.                                               |
| **Capital**         | Valor inicial considerado em uma operação financeira.                               |
| **Capitalização**   | Processo de incorporação dos juros ao capital.                                      |
| **Juros**           | Remuneração ou custo associado ao dinheiro durante determinado período.             |
| **Juros compostos** | Regime no qual os juros acumulados passam a integrar a base dos cálculos seguintes. |
| **Juros simples**   | Regime no qual os juros são calculados sobre o capital inicial.                     |
| **Montante**        | Capital acrescido dos juros acumulados.                                             |
| **Período**         | Intervalo de tempo considerado na operação.                                         |
| **Principal**       | Outra denominação utilizada para o capital inicial.                                 |
| **Rentabilidade**   | Retorno obtido em determinado investimento durante um período.                      |
| **Taxa de juros**   | Percentual aplicado durante determinado período.                                    |
| **Valor futuro**    | Valor resultante após determinado período de capitalização.                         |

---

# ♻️ 8. Prompts Reutilizáveis

Os experimentos permitiram construir alguns prompts que podem ser reutilizados para estudar outros assuntos.

### Prompt para aprender um novo conceito

```text
Atue como professor de [ÁREA].

Utilizando exclusivamente as fontes deste caderno, explique [TEMA]
para uma pessoa que está começando a estudar o assunto.

Apresente:
1. definição;
2. conceitos fundamentais;
3. exemplo prático;
4. aplicações;
5. erros comuns.

Indique as fontes utilizadas.
```

### Prompt para revisão

```text
Utilizando exclusivamente as fontes deste caderno, crie uma revisão
sobre [TEMA].

Liste os 10 conceitos mais importantes e explique cada um utilizando
linguagem objetiva.

Ao final, faça 5 perguntas para testar meu conhecimento.
```

### Prompt para comparação

```text
Com base exclusivamente nas fontes deste caderno, compare
[CONCEITO A] e [CONCEITO B].

Apresente:
- definição;
- semelhanças;
- diferenças;
- aplicações;
- exemplos.

Fundamente a comparação utilizando as fontes.
```

### Prompt para identificar lacunas

```text
Analise as fontes deste caderno e identifique quais conhecimentos
importantes relacionados a [TEMA] não estão suficientemente explicados.

Não utilize conhecimento externo para preencher as lacunas.

Informe quais assuntos exigiriam fontes adicionais.
```

### Prompt para validação

```text
Analise a seguinte afirmação:

"[AFIRMAÇÃO]"

Utilizando exclusivamente as fontes deste caderno, classifique-a como:

- correta;
- parcialmente correta;
- incorreta;
- não verificável com as fontes disponíveis.

Explique a classificação e indique as referências utilizadas.
```

---

# 💡 9. Principais Aprendizados

O desenvolvimento deste projeto mostrou que utilizar inteligência artificial para estudar vai além de simplesmente fazer perguntas e receber respostas.

Alguns dos principais aprendizados foram:

* A qualidade das fontes influencia diretamente a qualidade do estudo;
* Prompts mais detalhados permitem maior controle sobre a resposta;
* Definir o público-alvo melhora a adequação da linguagem;
* Estabelecer uma estrutura ajuda a produzir respostas mais organizadas;
* Restringir a resposta às fontes facilita a verificação das informações;
* Citações devem ser verificadas e não apenas aceitas;
* A IA pode ser utilizada para criar perguntas e exercícios, não somente respostas;
* Identificar lacunas no conhecimento é tão importante quanto produzir resumos.

---

# 🚀 10. Conclusão

O NotebookLM demonstrou ser uma ferramenta útil para transformar um conjunto de fontes em um ambiente interativo de aprendizagem.

No estudo sobre juros compostos, foi possível utilizar a IA para relacionar conceitos, produzir explicações, comparar informações e explorar diferentes estratégias de formulação de prompts.

A experiência também demonstrou que o resultado depende não somente da capacidade da inteligência artificial, mas principalmente da **qualidade das fontes, das perguntas formuladas e da análise crítica realizada pelo usuário**.

Assim, a principal conclusão deste projeto é que a IA apresenta maior valor educacional quando utilizada não como substituta do processo de aprendizagem, mas como uma ferramenta para **questionar, organizar, comparar, revisar e validar conhecimento**.

---

## 🛠️ Tecnologias e recursos utilizados

* NotebookLM
* Inteligência Artificial Generativa
* GitHub
* Markdown
* Banco Central do Brasil
* CVM / Portal do Investidor
* eduCAPES

---

## 👤 Autor

**Jaqueline Araújo**

Projeto desenvolvido para o desafio de aprendizagem ativa com NotebookLM da **DIO**.
