# Miniguia de Estudos de Matemática Superior com NotebookLM

> Caderno temático criado no NotebookLM para apoiar a preparação em Matemática de nível superior, com foco em competições universitárias e no primeiro/segundo período de cursos de exatas.

---

## Contexto e Objetivos

O assunto de interesse escolhido para este caderno temÃ¡tico foi a **Matemática voltada para o nível superior**, com foco especial na preparação para **Olimpíadas Universitárias de Matemática**, como a **Competição Elon Lages Lima**, cujo escopo abrange Cálculo Diferencial e Integral I, Álgebra Linear, Geometria Analítica e Matemática Discreta.

Os objetivos de estudo definidos para este material foram:

- 1 Preparação para competições matemáticas de nível avançado;
- 2 Aprimoramento particular das próprias habilidades matemáticas;
- 3 Apoio aos estudos do primeiro e segundo período de cursos de exatas, como Bacharelado em Matemática Pura ou Engenharias.

---

## Curadoria de Fontes

Foram selecionadas cinco fontes clássicas e amplamente reconhecidas na Academia, em português e em inglês, priorizando o rigor matemático necessário para demonstrações e provas complexas:

| # | Obra | Autor(es) | Ãrea |
|---|------|-----------|------|
| 1 | Álgebra Linear | Prof. Dr. José Luiz Boldrini | Álgebra Linear |
| 2 | Geometria Analítica: um Tratamento Vetorial | Prof. Dr. Ivan de Camargo e Prof. Dr. Paulo Boulos | Geometria Analítica |
| 3 | Discrete Mathematics and Its Applications | Dr. Kenneth H. Rosen | Matemática Discreta |
| 4 | Differential and Integral Calculus (1° edição) | Dr. Richard Courant | Cálculo Diferencial e Integral |
| 5 | A Course of Pure Mathematics | Prof. G. H. Hardy | Análise / Matemática Pura |

Links:


---

## Engenharia de Prompts e "Cicatrizes"

Nesta seção estão documentados os prompts estratégicos elaborados, as respostas obtidas, as referências utilizadas pela IA e as dificuldades encontradas no processo (troubleshooting).

### Prompt 1: Geometria da Integral segundo Courant

**Objetivo:** entender a lógica geométrica por trás da definição de integral e aplica-la em um exemplo prático.

**Prompt utilizado:**
> "Poderia me explicar como Richard Courant descreve a geometria por trás das ideias de integrais? Explique o passo a passo de toda a lógica que ele usou para construir esta ideia. ApÃ³s isso, faça um pequeno exemplo passo a passo de como resolver usando a definição formal desenvolvida por Courant. Após isso, no final, crie um pequeno resumo tocando em todos os tópicos importantes citados na resposta em lista com tópicos rápidos, focando na explicação matemática."

**Resposta da IA** (dividida em três partes: explicação conceitual, exemplo passo a passo e resumo final):

<img width="774" height="788" alt="ExplicaÃ§Ã£o da geometria da integral segundo Courant" src="https://github.com/user-attachments/assets/c5fd2c29-ea5a-4c1c-b7c9-8199936fb023" />
<img width="815" height="787" alt="Exemplo passo a passo da definiÃ§Ã£o formal de Courant" src="https://github.com/user-attachments/assets/c0e66b67-2c9d-47ca-ad83-9b2a65d00080" />
<img width="790" height="354" alt="Resumo final em tÃ³picos" src="https://github.com/user-attachments/assets/a7317966-013b-4d42-a7ab-2634be852f5d" />

**Referência usada pela IA:** livro de Richard Courant.

**Observações / troubleshooting:** pedir explicitamente a estrutura em três blocos (explicação; exemplo; resumo em tópicos) no mesmo prompt evitou respostas genéricas e garantiu que a IA seguisse a linha de raciocínio do autor, em vez de recorrer a uma definição de integral "padrão de livro didático" genérica.

---

### Prompt 2: Teorema da Invariancia da DimensÃ£o

**Objetivo:** obter uma demonstraÃ§Ã£o tÃ©cnica completa, com toda a linha de raciocÃ­nio lÃ³gico.

**Prompt utilizado:**
> "Explique o que Ã© e demonstre o Teorema da InvariÃ¢ncia da DimensÃ£o. Mostre toda a sua linha de raciocÃ­nio lÃ³gico atÃ© chegar na conclusÃ£o do Teorema."

**Resposta da IA:**

<img width="595" height="999" alt="DemonstraÃ§Ã£o do Teorema da InvariÃ¢ncia da DimensÃ£o" src="https://github.com/user-attachments/assets/50d90848-d346-44eb-b80b-4973e3129650" />

**ReferÃªncia usada pela IA:** livro de JosÃ© Luiz Boldrini.

**ObservaÃ§Ãµes / troubleshooting:** diferente do Prompt 1, aqui nÃ£o foi pedida uma estrutura em blocos â€” e a resposta veio mais "corrida", misturando definiÃ§Ã£o e demonstraÃ§Ã£o. Uma melhoria testada depois foi replicar a mesma lÃ³gica do Prompt 1 (pedir explicaÃ§Ã£o â†’ demonstraÃ§Ã£o â†’ resumo separados), o que deixou a resposta mais fÃ¡cil de revisar depois.

---

### Prompt 3 â€” ResoluÃ§Ã£o de questÃ£o da CompetiÃ§Ã£o Elon Lages Lima (2025)

**Objetivo:** resolver uma questÃ£o de prova real (6Âª ediÃ§Ã£o, 2025) enviando a imagem da questÃ£o diretamente como fonte, sem transcriÃ§Ã£o manual.

**Prompt utilizado:**
> "A imagem enviada se refere a uma questÃ£o da prova da CompetiÃ§Ã£o Elon Lages Lima de 2025, onde pede a resposta da integral. Resolva essa questÃ£o mostrando toda sua linha de raciocÃ­nio atÃ© a resposta, sem pular nenhuma parte. AlÃ©m disso, explique o porquÃª de cada tÃ©cnica usada, por exemplo: 'usei a tÃ©cnica de fraÃ§Ãµes parciais porque [explicaÃ§Ã£o]'."

**Imagem da questÃ£o enviada como fonte:**

<img width="1380" height="421" alt="QuestÃ£o da CompetiÃ§Ã£o Elon Lages Lima 2025" src="https://github.com/user-attachments/assets/92b4493c-be7f-4edc-b385-805850a534fb" />

**Resposta da IA:**

> âš ï¸ **PendÃªncia:** inserir aqui o print/imagem da resposta da IA para este prompt.

**ReferÃªncia usada pela IA:** livro de Richard Courant (alÃ©m da imagem enviada).

**ObservaÃ§Ãµes / troubleshooting:** enviar a imagem da questÃ£o diretamente como fonte no NotebookLM (em vez de digitar o enunciado) funcionou bem e evitou erros de transcriÃ§Ã£o â€” especialmente importante em questÃµes com notaÃ§Ã£o matemÃ¡tica mais densa. A principal dificuldade foi garantir que a IA justificasse *cada* tÃ©cnica usada e nÃ£o apenas apresentasse a conta pronta; pedir explicitamente o formato de justificativa ("usei a tÃ©cnica de X porque...") no prompt foi o que resolveu isso.

---

## ðŸ§­ Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### ðŸ“ CÃ¡lculo Diferencial e Integral â€” a ideia geomÃ©trica de integral (Courant)
- A integral definida surge da ideia de **medir a Ã¡rea sob uma curva** aproximando-a por retÃ¢ngulos cada vez mais finos (soma de retÃ¢ngulos â†’ soma de Riemann).
- Ao refinar a partiÃ§Ã£o do intervalo (aumentar o nÃºmero de retÃ¢ngulos e diminuir sua largura), a soma dessas Ã¡reas converge para um valor-limite: esse limite Ã©, por definiÃ§Ã£o, a integral definida da funÃ§Ã£o no intervalo.
- Essa construÃ§Ã£o geomÃ©trica Ã© o que dÃ¡ sentido intuitivo ao Teorema Fundamental do CÃ¡lculo, ligando a Ã¡rea sob a curva (integral) Ã  taxa de variaÃ§Ã£o (derivada) de uma primitiva.
- **FraÃ§Ãµes parciais** sÃ£o uma tÃ©cnica usada quando a funÃ§Ã£o a integrar Ã© um quociente de polinÃ´mios: decompÃµe-se a fraÃ§Ã£o em uma soma de fraÃ§Ãµes mais simples, cada uma com integral conhecida.

#### ðŸ§® Ãlgebra Linear â€” Teorema da InvariÃ¢ncia da DimensÃ£o
- Todo espaÃ§o vetorial de dimensÃ£o finita possui bases, e o teorema garante que **todas as bases de um mesmo espaÃ§o vetorial tÃªm exatamente o mesmo nÃºmero de elementos**.
- Isso Ã© o que permite falar em "a dimensÃ£o" de um espaÃ§o vetorial como um nÃºmero bem definido, e nÃ£o algo que muda dependendo da base escolhida.
- A demonstraÃ§Ã£o tipicamente usa o **Teorema do Completamento/Troca de Steinitz**: comparar dois conjuntos de vetores linearmente independentes que geram o mesmo espaÃ§o, mostrando que um nÃ£o pode ter mais elementos que o outro sem gerar contradiÃ§Ã£o de independÃªncia linear.

#### ðŸ“Š Geometria AnalÃ­tica â€” tratamento vetorial
- Trata objetos geomÃ©tricos (retas, planos, cÃ´nicas) por meio de vetores e coordenadas, unindo Ã¡lgebra e geometria.
- Serve de base prÃ¡tica para visualizar conceitos abstratos de Ãlgebra Linear, como independÃªncia linear e bases, em 2D e 3D.

#### ðŸ”¢ MatemÃ¡tica Discreta
- Cobre induÃ§Ã£o finita, contagem, relaÃ§Ãµes e estruturas discretas â€” ferramentas de demonstraÃ§Ã£o muito usadas em provas de olimpÃ­ada, incluindo a prÃ³pria tÃ©cnica de induÃ§Ã£o usada para validar fÃ³rmulas e teoremas gerais.

---

### 2. GlossÃ¡rio

| Termo | DefiniÃ§Ã£o resumida |
|---|---|
| **Soma de Riemann** | AproximaÃ§Ã£o da Ã¡rea sob uma curva pela soma de Ã¡reas de retÃ¢ngulos, base da definiÃ§Ã£o formal de integral. |
| **Integral definida** | Limite da soma de Riemann quando a partiÃ§Ã£o do intervalo se torna infinitamente fina. |
| **FraÃ§Ãµes parciais** | TÃ©cnica de integraÃ§Ã£o que decompÃµe uma fraÃ§Ã£o racional em fraÃ§Ãµes mais simples. |
| **EspaÃ§o vetorial** | Conjunto de vetores fechado sob soma e multiplicaÃ§Ã£o por escalar, respeitando os axiomas de espaÃ§o vetorial. |
| **Base** | Conjunto de vetores linearmente independentes que geram todo o espaÃ§o vetorial. |
| **DimensÃ£o** | NÃºmero de vetores em qualquer base de um espaÃ§o vetorial (garantidamente o mesmo, pelo Teorema da InvariÃ¢ncia da DimensÃ£o). |
| **IndependÃªncia linear** | Propriedade de um conjunto de vetores em que nenhum deles pode ser escrito como combinaÃ§Ã£o linear dos demais. |
| **InduÃ§Ã£o finita** | TÃ©cnica de demonstraÃ§Ã£o matemÃ¡tica usada para provar que uma proposiÃ§Ã£o vale para todos os nÃºmeros naturais, a partir de um caso base e um passo indutivo. |

---

### 3. Prompts ReutilizÃ¡veis para RevisÃ£o

Modelos genÃ©ricos, baseados nos prompts testados, prontos para reaproveitar em futuras sessÃµes de revisÃ£o no NotebookLM:

**ðŸ”¹ Para entender a lÃ³gica/construÃ§Ã£o de um conceito:**
> "Explique como [AUTOR] descreve a ideia de [CONCEITO]. Mostre o passo a passo do raciocÃ­nio usado para construir essa ideia. Em seguida, resolva um exemplo simples aplicando a definiÃ§Ã£o formal apresentada. Por fim, crie um resumo em tÃ³picos rÃ¡pidos com os pontos mais importantes."

**ðŸ”¹ Para demonstraÃ§Ãµes formais:**
> "Explique o que Ã© e demonstre o [NOME DO TEOREMA]. Mostre toda a linha de raciocÃ­nio lÃ³gico, passo a passo, atÃ© chegar Ã  conclusÃ£o do teorema, citando os resultados/teoremas intermediÃ¡rios usados."

**ðŸ”¹ Para resoluÃ§Ã£o de exercÃ­cios/provas com justificativa de tÃ©cnica:**
> "A imagem enviada se refere a uma questÃ£o de [NOME DA PROVA/COMPETIÃ‡ÃƒO, ANO]. Resolva a questÃ£o mostrando toda a linha de raciocÃ­nio atÃ© a resposta final, sem pular etapas. Para cada tÃ©cnica usada, explique o porquÃª: 'usei a tÃ©cnica de X porque [explicaÃ§Ã£o]'."

**ðŸ”¹ Para revisÃ£o rÃ¡pida antes de uma prova:**
> "Com base nas fontes carregadas, monte um resumo em tÃ³picos dos principais teoremas e definiÃ§Ãµes sobre [TEMA], incluindo para cada um: enunciado, ideia-chave da demonstraÃ§Ã£o e um exemplo curto de aplicaÃ§Ã£o."

---

## âœ… Checklist de pendÃªncias antes da entrega

- [ ] Adicionar links/ediÃ§Ãµes das 5 fontes na tabela de Curadoria de Fontes
- [ ] Inserir a imagem da resposta do Prompt 3
- [ ] Revisar se todas as imagens estÃ£o corretamente linkadas apÃ³s subir para o GitHub
- [ ] Colar a URL final do repositÃ³rio na plataforma da DIO
