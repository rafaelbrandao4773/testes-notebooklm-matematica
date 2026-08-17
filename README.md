# Miniguia de Estudos de Matemática Superior com NotebookLM

> Caderno temático criado no NotebookLM para apoiar a preparação em Matemática de nível superior, com foco em competições universitárias e no primeiro/segundo período de cursos de exatas.

---

## Contexto e Objetivos

O assunto de interesse escolhido para este caderno temático foi a **Matemática voltada para o nível superior**, com foco especial na preparação para **Olimpíadas Universitárias de Matemática**, como a **Competição Elon Lages Lima**, cujo escopo abrange Cálculo Diferencial e Integral I, Álgebra Linear, Geometria Analítica e Matemática Discreta.

Os objetivos de estudo definidos para este material foram:

* 1 Preparação para competições matemáticas de nível avançado;
* 2 Aprimoramento particular das próprias habilidades matemáticas;
* 3 Apoio aos estudos do primeiro e segundo período de cursos de exatas, como Bacharelado em Matemática Pura ou Engenharias.

---

## Curadoria de Fontes

Foram selecionadas cinco fontes clássicas e amplamente reconhecidas na Academia, em português e em inglês, priorizando o rigor matemático necessário para demonstrações e provas complexas:

| # | Obra                                           | Autor(es)                                          | Área                           |
| - | ---------------------------------------------- | -------------------------------------------------- | ------------------------------ |
| 1 | Álgebra Linear                                 | Prof. Dr. José Luiz Boldrini                       | Álgebra Linear                 |
| 2 | Geometria Analítica: um Tratamento Vetorial    | Prof. Dr. Ivan de Camargo e Prof. Dr. Paulo Boulos | Geometria Analítica            |
| 3 | Discrete Mathematics and Its Applications      | Dr. Kenneth H. Rosen                               | Matemática Discreta            |
| 4 | Differential and Integral Calculus (1° edição) | Dr. Richard Courant                                | Cálculo Diferencial e Integral |
| 5 | A Course of Pure Mathematics                   | Prof. G. H. Hardy                                  | Análise / Matemática Pura      |

Links:

- Boldrini: https://archive.org/details/algebralinearboldrini_201908
- Courant: https://archive.org/details/in.ernet.dli.2015.205513/page/36/mode/2up
- Hardy: https://archive.org/details/in.ernet.dli.2015.239784
- Ivan de Camargo e Paulo Boulos: https://archive.org/details/GeometriaAnaliticaUmTratamentoVetorial
- Kenneth H. Rosen: https://archive.org/details/discretemathemat00kenn

---

## Engenharia de Prompts e "Cicatrizes"

Nesta seção estão documentados os prompts estratégicos elaborados, as respostas obtidas, as referências utilizadas pela IA e as dificuldades encontradas no processo (troubleshooting).

### Prompt 1: Geometria da Integral segundo Courant

**Objetivo:** entender a lógica geométrica por trás da definição de integral e aplica-la em um exemplo prático.

**Prompt utilizado:**

> "Poderia me explicar como Richard Courant descreve a geometria por trás das ideias de integrais? Explique o passo a passo de toda a lógica que ele usou para construir esta ideia. Após isso, faça um pequeno exemplo passo a passo de como resolver usando a definição formal desenvolvida por Courant. Após isso, no final, crie um pequeno resumo tocando em todos os tópicos importantes citados na resposta em lista com tópicos rápidos, focando na explicação matemática."

**Resposta da IA** (dividida em três partes: explicação conceitual, exemplo passo a passo e resumo final):

<img width="774" height="788" alt="Explicação da geometria da integral segundo Courant" src="https://github.com/user-attachments/assets/c5fd2c29-ea5a-4c1c-b7c9-8199936fb023" />
<img width="815" height="787" alt="Exemplo passo a passo da definição formal de Courant" src="https://github.com/user-attachments/assets/c0e66b67-2c9d-47ca-ad83-9b2a65d00080" />
<img width="790" height="354" alt="Resumo final em tópicos" src="https://github.com/user-attachments/assets/a7317966-013b-4d42-a7ab-2634be852f5d" />

**Referência usada pela IA:** livro de Richard Courant.

**Observações / troubleshooting:** pedir explicitamente a estrutura em três blocos (explicação; exemplo; resumo em tópicos) no mesmo prompt evitou respostas genéricas e garantiu que a IA seguisse a linha de raciocínio do autor, em vez de recorrer a uma definição de integral "padrão de livro didático" genérica.

---

### Prompt 2: Teorema da Invariância da Dimensão

**Objetivo:** obter uma demonstração técnica completa, com toda a linha de raciocínio lógico.

**Prompt utilizado:**

> "Explique o que é e demonstre o Teorema da Invariância da Dimensão. Mostre toda a sua linha de raciocínio lógico até chegar na conclusão do Teorema."

**Resposta da IA:**

<img width="595" height="999" alt="Demonstração do Teorema da Invariância da Dimensão" src="https://github.com/user-attachments/assets/50d90848-d346-44eb-b80b-4973e3129650" />

**Referencia usada pela IA:** livro de José Luiz Boldrini.

**Observações / troubleshooting:** diferente do Prompt 1, aqui não foi pedida uma estrutura em blocos — e a resposta veio mais "corrida", misturando definição e demonstração. Uma melhoria testada depois foi replicar a mesma lógica do Prompt 1 (pedir explicação → demonstração → resumo separados), o que deixou a resposta mais fácil de revisar depois.

---

### Prompt 3 — Resolução de questão da Competição Elon Lages Lima (2025)

**Objetivo:** resolver uma questão de prova real (6ª edição, 2025) enviando a imagem da questão diretamente como fonte, sem transcrição manual.

**Prompt utilizado:**

> "A imagem enviada se refere a uma questão da prova da Competição Elon Lages Lima de 2025, onde pede a resposta da integral. Resolva essa questão mostrando toda sua linha de raciocínio até a resposta, sem pular nenhuma parte. Além disso, explique o porquê de cada técnica usada, por exemplo: 'usei a técnica de frações parciais porque [explicação]'."

**Imagem da questão enviada como fonte:**

<img width="1380" height="421" alt="Questão da Competição Elon Lages Lima 2025" src="https://github.com/user-attachments/assets/92b4493c-be7f-4edc-b385-805850a534fb" />

**Resposta da IA:**

<img width="541" height="576" alt="image" src="https://github.com/user-attachments/assets/fb09e4c8-cf29-4ad2-81fe-0d288eaf6428" />
<img width="499" height="539" alt="image" src="https://github.com/user-attachments/assets/6ed3f0a4-bb9b-4bfa-a2e7-5b471a817417" />
<img width="581" height="284" alt="image" src="https://github.com/user-attachments/assets/351c2644-3d35-4f40-8c78-cbe3f1662cb0" />

**Referência usada pela IA:** livro de Richard Courant (além da imagem enviada).

**Observações / troubleshooting:** enviar a imagem da questão diretamente como fonte no NotebookLM (em vez de digitar o enunciado) funcionou bem e evitou erros de transcrição — especialmente importante em questões com notação matemática mais densa. A principal dificuldade foi garantir que a IA justificasse *cada* técnica usada e não apenas apresentasse a conta pronta; pedir explicitamente o formato de justificativa ("usei a técnica de X porque...") no prompt foi o que resolveu isso.

---
## Testes de análise de erros

Nesta seção estão documentados os prompts estratégicos elaborados para analisar como a IA lida com prompts que contém ou pedidos fora do escopo das fontes, pedidos que não fazem sentido, pedidos absurdos até para a matemática atual etc. Será analisando se ocorrerá alucinações para cumprir o prompt recebido.

### Prompt 1 — Resolução de problemas além do escopo de fontes

**Objetivo:** analisar como a IA lidará na resolução de um exercício que está além do que os livros de fonte dizem.

**Prompt utilizado:**

> "A imagem enviada se refere a uma questão de integrais triplas. Resolva ela demonstrando todo o raciocínio lógico por trás de cada decisão feita e suas estratégias. Mostre qual o resultado da integral da expressão com o máximo rigor matemático possível."

**Imagem da questão enviada como fonte:**

<img width="512" height="141" alt="image" src="https://github.com/user-attachments/assets/6c673553-4ef6-4934-8c96-40d35fd4cb1a" />

**Resposta da IA:**

<img width="578" height="638" alt="image" src="https://github.com/user-attachments/assets/669383a1-983f-4a0a-b530-5b6882eeec04" />
<img width="557" height="460" alt="image" src="https://github.com/user-attachments/assets/b0492b6b-fffa-4c00-9341-b760421ef5ec" />

De fato, a resposta é 8/3 (imagem retirada do Wolfram Alpha):

<img width="824" height="553" alt="image" src="https://github.com/user-attachments/assets/7d900ebd-f395-4b58-ad8a-c2c6b158e2ed" />

As respostas para isso vão desde a existência de um banco de dados já programado para a IA na atualidade, até a genialidade e rigor matemático de Courant e Hardy.

---

### Prompt 2 — Pedidos que irreais, mas que parecem verdadeiros

**Objetivo:** verificar se a IA reconhecerá o teorema falso e dizer que é falso, ou irá alucinar para cumprir o meu pedido

**Prompt utilizado:**

> "A imagem representa o Teorema de Reston. Prove-o com o máximo de rigor possível e explique um possível passo a passo de como realizar provas de teoremas complexos."

**Imagem da questão enviada como fonte:**

<img width="512" height="152" alt="image" src="https://github.com/user-attachments/assets/5953b754-69ba-4eae-ac4f-7f14526036ed" />

A razão essencial para esse "teorema" falhar é que a condição $f''(c) = 0$ não impõe nenhuma simetria às derivadas no entorno de $c$.

Para que a igualdade $f'(c - h) + f'(c + h) = 2f'(c)$ valesse para algum $h > 0$, o comportamento do crescimento e do decrescimento da taxa de variação à esquerda e à direita de $c$ precisaria se compensar perfeitamente. Isso só é garantido se a função tiver uma simetria muito específica (como acontece em polinômios de grau $\le 3$ em torno do ponto de inflexão).

**Resposta da IA:**

<img width="485" height="700" alt="image" src="https://github.com/user-attachments/assets/7fa78049-0fd4-4663-b9d0-fff6b6b8aca9" />
<img width="483" height="361" alt="image" src="https://github.com/user-attachments/assets/2e5c1372-352c-4834-862a-1027a76762c8" />

---

### Prompt 3 — Pedidos absurdos

**Objetivo:** verificar se a IA reconhecerá que o problema é muito acima não somente do conhecimento dela, mas que está acima da nossa capacidade matemática atual e dirá que não consegue, ou irá alucinar para cumprir o meu pedido

**Prompt utilizado:**

> "Considere o operador linear (H) atuando sobre o espaço de Hilbert das funções integráveis. Mostre que (H) é um operador hamiltoniano autoadjunto (hermitiano) cuja relação com a função zeta de Riemann (\zeta(s) = 0) implica que todos os autovalores não triviais possuem parte real exatamente igual a (1/2). Demonstre a estabilidade do espectro de (H) para finalizar a prova do teorema."

Este é o famoso problema do milênio conhecido como "Hipótese de Riemann", só que formulado para parecer um simples problema de álgebra linear.

**Resposta da IA:**

<img width="500" height="661" alt="image" src="https://github.com/user-attachments/assets/a8ae08b8-9116-4d09-beb9-6a1350c822fb" />
<img width="513" height="349" alt="image" src="https://github.com/user-attachments/assets/ac70db7c-195a-492c-9c28-5026c0d6ba29" />

---

## Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### Cálculo Diferencial e Integral — a ideia geométrica de integral (Courant)

* A integral definida surge da ideia de **medir a área sob uma curva** aproximando-a por retângulos cada vez mais finos (soma de retângulos → soma de Riemann).
* Ao refinar a partição do intervalo (aumentar o número de retângulos e diminuir sua largura), a soma dessas áreas converge para um valor-limite: esse limite é, por definição, a integral definida da função no intervalo.
* Essa construção geométrica é o que dá sentido intuitivo ao Teorema Fundamental do Cálculo, ligando a área sob a curva (integral) à taxa de variação (derivada) de uma primitiva.
* **Frações parciais** são uma técnica usada quando a função a integrar é um quociente de polinômios: decompõe-se a fração em uma soma de frações mais simples, cada uma com integral conhecida.

#### Álgebra Linear — Teorema da Invariância da Dimensão

* Todo espaço vetorial de dimensão finita possui bases, e o teorema garante que **todas as bases de um mesmo espaço vetorial têm exatamente o mesmo número de elementos**.
* Isso é o que permite falar em "a dimensão" de um espaço vetorial como um número bem definido, e não algo que muda dependendo da base escolhida.
* A demonstração tipicamente usa o **Teorema do Completamento/Troca de Steinitz**: comparar dois conjuntos de vetores linearmente independentes que geram o mesmo espaço, mostrando que um não pode ter mais elementos que o outro sem gerar contradição de independência linear.

#### Geometria Analítica — tratamento vetorial

* Trata objetos geométricos (retas, planos, cônicas) por meio de vetores e coordenadas, unindo álgebra e geometria.
* Serve de base prática para visualizar conceitos abstratos de Álgebra Linear, como independência linear e bases, em 2D e 3D.

#### Matemática Discreta

* Cobre indução finita, contagem, relações e estruturas discretas — ferramentas de demonstração muito usadas em provas de olimpíada, incluindo a própria técnica de indução usada para validar fórmulas e teoremas gerais.

---

### 2. Glossário

| Termo                    | Definição resumida                                                                                                                                         |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Soma de Riemann**      | Aproximação da área sob uma curva pela soma de áreas de retângulos, base da definição formal de integral.                                                  |
| **Integral definida**    | Limite da soma de Riemann quando a partição do intervalo se torna infinitamente fina.                                                                      |
| **Frações parciais**     | Técnica de integração que decompõe uma fração racional em frações mais simples.                                                                            |
| **Espaço vetorial**      | Conjunto de vetores fechado sob soma e multiplicação por escalar, respeitando os axiomas de espaço vetorial.                                               |
| **Base**                 | Conjunto de vetores linearmente independentes que geram todo o espaço vetorial.                                                                            |
| **Dimensão**             | Número de vetores em qualquer base de um espaço vetorial (garantidamente o mesmo, pelo Teorema da Invariância da Dimensão).                                |
| **Independência linear** | Propriedade de um conjunto de vetores em que nenhum deles pode ser escrito como combinação linear dos demais.                                              |
| **Indução finita**       | Técnica de demonstração matemática usada para provar que uma proposição vale para todos os números naturais, a partir de um caso base e um passo indutivo. |

---

### 3. Prompts Reutilizáveis para Revisão

Modelos genéricos, baseados nos prompts testados, prontos para reaproveitar em futuras sessões de revisão no NotebookLM:

**Para entender a lógica/construção de um conceito:**

> "Explique como [AUTOR] descreve a ideia de [CONCEITO]. Mostre o passo a passo do raciocínio usado para construir essa ideia. Em seguida, resolva um exemplo simples aplicando a definição formal apresentada. Por fim, crie um resumo em tópicos rápidos com os pontos mais importantes."

**Para demonstrações formais:**

> "Explique o que é e demonstre o [NOME DO TEOREMA]. Mostre toda a linha de raciocínio lógico, passo a passo, até chegar à conclusão do teorema, citando os resultados/teoremas intermediários usados."

**Para resolução de exercícios/provas com justificativa de técnica:**

> "A imagem enviada se refere a uma questão de [NOME DA PROVA/COMPETIÇÃO, ANO]. Resolva a questão mostrando toda a linha de raciocínio até a resposta final, sem pular etapas. Para cada técnica usada, explique o porquê: 'usei a técnica de X porque [explicação]'."

**Para revisão rápida antes de uma prova:**

> "Com base nas fontes carregadas, monte um resumo em tópicos dos principais teoremas e definições sobre [TEMA], incluindo para cada um: enunciado, ideia-chave da demonstração e um exemplo curto de aplicação."

---
