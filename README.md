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

Uma das propostas deste projeto foi observar como a construção de um prompt influencia a qualidade, a organização e a profundidade das respostas produzidas pela IA.

Para isso, foram realizados três experimentos sobre o mesmo assunto, aumentando progressivamente o nível de detalhamento das instruções.

A estratégia utilizada foi:

**Prompt simples → Prompt contextualizado → Prompt estruturado**

---

## Experimento 1 — Prompt simples

### Prompt utilizado

> Explique juros compostos.

### Resposta obtida

Mesmo com uma instrução curta, o NotebookLM apresentou uma definição adequada de juros compostos, explicando que eles incidem não apenas sobre o valor inicial, mas também sobre os juros acumulados nos períodos anteriores.

A ferramenta utilizou a expressão **"juros sobre juros"** e apresentou um exemplo no qual R$ 100,00 são aplicados a uma taxa de 2% ao ano.

Também relacionou o conceito à educação financeira e apresentou informações provenientes das fontes do Banco Central.

### Resultado observado

O primeiro experimento mostrou que um prompt simples pode produzir uma resposta relevante quando o NotebookLM possui fontes adequadas.

Entretanto, como nenhuma estrutura foi determinada, várias decisões ficaram sob responsabilidade da própria IA.

Não foram especificados:

* público-alvo;
* nível de profundidade;
* estrutura da resposta;
* conceitos obrigatórios;
* formato do exemplo;
* aplicação prática;
* forma de avaliação do aprendizado.

Isso tornou a resposta útil, porém menos controlável.

---

## Experimento 2 — Prompt contextualizado

### Prompt utilizado

> Com base exclusivamente nas fontes deste caderno, explique o conceito de juros compostos para uma pessoa que está começando a estudar educação financeira. Diferencie juros simples de juros compostos e apresente um exemplo prático. Utilize as fontes do caderno para fundamentar a resposta.

### Resposta obtida

O NotebookLM passou a organizar a explicação de maneira mais didática.

Primeiro definiu juros compostos como **"juros sobre juros"**. Em seguida, criou uma seção específica comparando juros simples e compostos.

A ferramenta explicou que:

* nos juros simples, o rendimento é calculado sobre o valor inicial;
* nos juros compostos, o cálculo considera o capital inicial e os juros acumulados anteriormente.

Também desenvolveu um exemplo progressivo utilizando R$ 100,00 aplicados a 2% ao ano.

No primeiro ano, o montante passa para R$ 102,00. A resposta explicou que, após cinco anos, o resultado dos juros compostos seria superior aos R$ 110,00 que seriam obtidos pela lógica dos juros simples.

A resposta também relacionou os juros compostos ao endividamento e ao cartão de crédito.

### Resultado observado

Em comparação ao primeiro experimento, a resposta ficou mais organizada e direcionada ao objetivo de aprendizagem.

A inclusão de instruções específicas trouxe melhorias importantes:

* **"para uma pessoa que está começando"** adequou a linguagem ao público-alvo;
* **"diferencie juros simples de juros compostos"** obrigou a IA a realizar uma comparação;
* **"apresente um exemplo prático"** fez com que a explicação fosse acompanhada de uma aplicação;
* **"com base exclusivamente nas fontes"** delimitou o universo de informações permitido.

O experimento mostrou que fornecer contexto ao prompt aumenta o controle sobre a resposta.

---

## Experimento 3 — Prompt estruturado

### Prompt utilizado

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

### Resposta obtida

O terceiro experimento apresentou a resposta mais estruturada dos três testes.

O NotebookLM assumiu explicitamente uma abordagem pedagógica e dividiu a explicação nas nove etapas solicitadas.

Foram abordados:

1. conceito de juros;
2. conceito de juros compostos;
3. diferença entre juros simples e compostos;
4. lógica matemática da capitalização;
5. exemplo numérico;
6. influência da taxa;
7. influência do tempo;
8. utilização em investimentos;
9. consequências em dívidas.

A ferramenta novamente utilizou o exemplo de R$ 100,00 a uma taxa de 2% ao ano e relacionou taxas elevadas a situações como cartão de crédito rotativo e cheque especial.

Ao final, conforme solicitado, foram apresentadas três perguntas para verificar a compreensão do conteúdo.

A resposta informou como fontes utilizadas:

* *Série Cidadania Financeira n. 5*;
* *Cidadania Financeira*;
* *Portal eduCAPES*.

### Resultado observado

O terceiro experimento apresentou maior controle sobre o formato da resposta.

A instrução **"Atue como um professor de educação financeira"** estabeleceu um papel para a IA, enquanto **"para um aluno iniciante"** definiu o nível da explicação.

A estrutura numerada reduziu a liberdade da IA para decidir quais assuntos abordar e em qual ordem apresentá-los.

Outro ganho importante foi a inclusão de perguntas de verificação. Dessa forma, a IA deixou de atuar apenas como ferramenta para produzir respostas e passou também a apoiar uma estratégia de **aprendizagem ativa**.

---

## Comparação dos experimentos

| Característica            |  Experimento 1  | Experimento 2 | Experimento 3 |
| ------------------------- | :-------------: | :-----------: | :-----------: |
| Define público-alvo       |        ❌        |       ✅       |       ✅       |
| Restringe às fontes       |        ❌        |       ✅       |       ✅       |
| Solicita comparação       |        ❌        |       ✅       |       ✅       |
| Exige exemplo             |        ❌        |       ✅       |       ✅       |
| Define papel da IA        |        ❌        |       ❌       |       ✅       |
| Define estrutura          |        ❌        |    Parcial    |       ✅       |
| Aborda investimentos      | Espontaneamente |  Parcialmente |       ✅       |
| Aborda dívidas            | Espontaneamente |       ✅       |       ✅       |
| Avalia aprendizado        |        ❌        |       ❌       |       ✅       |
| Controle sobre a resposta |      Baixo      |     Médio     |      Alto     |

### Evolução observada

```text
PROMPT 1
"Explique juros compostos."
        ↓
Resposta relevante, porém com grande liberdade para a IA

PROMPT 2
Contexto + público + comparação + exemplo + fontes
        ↓
Resposta mais direcionada e didática

PROMPT 3
Papel + contexto + público + fontes + estrutura + avaliação
        ↓
Resposta organizada como uma experiência de aprendizagem
```

O experimento mostrou que um bom prompt não precisa apenas perguntar **"o que quero saber?"**, mas também pode determinar:

* **quem** deve responder;
* **para quem** a resposta será produzida;
* **quais fontes** podem ser utilizadas;
* **o que** precisa ser abordado;
* **como** a resposta deve ser estruturada;
* **como verificar** se houve aprendizagem.

---

# 🔎 5. Cicatrizes e Troubleshooting

Além das respostas obtidas, alguns comportamentos do NotebookLM foram importantes para compreender as limitações e os cuidados necessários no uso da IA.

## Cicatriz 1 — Uma referência não elimina a necessidade de validação

Nos primeiros experimentos, o NotebookLM apresentou a afirmação de que apenas **18% da população demonstrava domínio completo** do conteúdo relacionado aos juros simples e compostos.

Isso chamou atenção durante a análise das respostas.

A experiência mostrou que uma informação não deve ser considerada automaticamente correta apenas porque uma IA apresentou uma referência.

É necessário consultar o trecho original e verificar:

* qual pergunta foi realizada na pesquisa;
* o que exatamente o percentual representa;
* qual população foi analisada;
* se a interpretação da IA corresponde ao conteúdo original.

**Aprendizado:** referências ajudam na verificação, mas não substituem a análise crítica.

---

## Cicatriz 2 — A IA respeitou a limitação das fontes mesmo quando isso reduziu a resposta

No terceiro experimento foi solicitada explicitamente uma:

> "explicação da fórmula matemática"

Entretanto, o NotebookLM respondeu:

> "Embora as fontes mencionem a existência de fórmulas em e-books e calculadoras, elas explicam a lógica através da acumulação."

Em vez de simplesmente inventar ou complementar a resposta com conhecimento externo, a ferramenta reconheceu uma limitação no material disponível e explicou somente a lógica encontrada nas fontes.

Esse comportamento revelou algo importante sobre sistemas baseados em recuperação de fontes:

> **Um prompt mais detalhado não consegue compensar completamente uma lacuna existente no material fornecido à IA.**

Se determinado conhecimento não está adequadamente representado nas fontes, pode ser necessário melhorar a **curadoria**, e não apenas melhorar o prompt.

---

## Cicatriz 3 — Nem todas as fontes são necessariamente utilizadas

O caderno possuía quatro fontes selecionadas, mas no terceiro experimento o NotebookLM informou utilizar:

* Série Cidadania Financeira n. 5;
* Cidadania Financeira;
* Portal eduCAPES.

Isso demonstra que adicionar uma fonte ao caderno não significa que ela será necessariamente relevante para todas as perguntas.

A IA recupera os conteúdos que considera relacionados à consulta realizada.

**Aprendizado:** quantidade de fontes não é tão importante quanto relevância e qualidade.

---

## Cicatriz 4 — Prompt detalhado não significa automaticamente resposta perfeita

O terceiro prompt foi significativamente mais elaborado que os anteriores.

Mesmo assim, a solicitação de uma fórmula matemática não pôde ser atendida da maneira esperada.

Isso demonstrou que existem pelo menos três elementos envolvidos na qualidade da resposta:

```text
QUALIDADE DA RESPOSTA
        ↓
Boas fontes
        +
Bom prompt
        +
Validação crítica
```

Melhorar somente um desses elementos não garante um resultado ideal.

---

# 🎯 Conclusão dos Experimentos

Os três testes demonstraram uma evolução clara na utilização da IA.

No primeiro experimento, a IA foi utilizada basicamente como um mecanismo de **pergunta e resposta**.

No segundo, passou a funcionar como uma ferramenta de **explicação orientada**.

No terceiro, a estrutura do prompt transformou a interação em uma pequena **experiência de aprendizagem**, contendo explicação, comparação, aplicações e perguntas de verificação.

A principal conclusão dessa etapa foi que **engenharia de prompts não consiste apenas em escrever comandos maiores**.

O objetivo é fornecer contexto suficiente para orientar a IA sem deixar de avaliar criticamente suas respostas.

Além disso, o experimento mostrou que a qualidade final depende da combinação entre:

**curadoria de fontes + elaboração de prompts + pensamento crítico.**
