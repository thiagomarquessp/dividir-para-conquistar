# Errar por preguiça é o pior erro

Errar é humano, mas errar por preguiça, em TI, deveria ser considerado um atentado contra a nossa classe, pois não podemos compactuar com a preguiça e no caso de estimativas, temos preguiça de olhar para o passado, e nem to falando de um passado tão passado assim, e sim um passado de um sprint, ou seja, temos preguiça de olhar para o que foi feito e comparar o nível de dificuldade e aceitar a derrota e de fato colocar uma "estimativa" que mais fazia sentido para aquele item. 

Não estou dizendo que devemos olhar para a nova estoria e filosofar em cima dela, e sim para pararmos um pouco e comparar com itens já entregues. Esse comparativo serve para colocarmos na nossa cabeça se o que estamos planejando é ou não complicado e o grau de dificuldade, se faz ou não sentido ter um item daquele tamanho, quais impactos reais a nível técnico e de negócio, etc.

Vamos tentar um exercício no próximo planning, quando o item chegar para sabermos quantos story points vamos colocar, **PARE**, pegue um post it e entregue a cada um dos developers para que **TODOS** possam refletir sobre essa história por 2 minutos, anotem aquilo que foi pensado nesses dois minutos e logo em seguida estimem todos juntos usando o planning poker.

O exercício acima vai confirmar três coisas:

- Se a tarefa for muito facil, os story points vão se alinhar (exemplo, 2 ou 3);
- Se a tarefa for muito difícil, os story points vão se alinhar (exemplo, 13);
- Se a tarefa for o meio termo, os story points vão divergir (basicamente entre 5 e 8).

Se convergir para cima, estaremos diante de algo possívelmente difícil e se for o contrário, algo fácil. Fazer o processo de pensar por dois minutos impede que alguém possa ser "manipulado" ou "induzido ao erro" na hora de estimar. 

Esse exercício pode ter uma variação quando colocamos o que pensamos num quadro e passamos a discutir aquilo antes mesmo de pontuar, e podemos (ou não) utilizar essa informação como base de comparação para as demais estimativas. Lembrando que comparativo é a primeira medida que pode ser utilizada.

## Teorema das 2 faixas iniciais

Com base no que lemos acima, no planning vamos trabalhar inicialmente com duas faixas (geralmente eu escolho: 3 e 8) e defino que estorias muito grandes (13) **não** podem fazer parte de um sprint e que devem ser partidas em vários fragmentos (basicamente assumimos que o 13 é algo muito difícil de se fazer e que não é possível terminar em um sprint) e no planning poker converse com todos sobre considerar inicialmente duas faixas. 

A ideia é bem simples, limitar a dois o erro ao invés de errar em mais faixas de sequência fibonacci, até porque quando estimamos alguma coisa, colocamos uma expectativa para os interessados no produto, incluindo a própria área de produto, principalmente quando estimamos algo baixo, como 1 ou 2 e estamos fartos de ver estorias de 1 ponto sendo levadas por dois, três sprints a frente e o ideal é não criar ou aumentar o clima de incerteza, tanto do time de engenharia, que fica desmotivado, quanto do time de produto, que coloca expectativas muito altas naquilo que "prometemos" entregar dentro do sprint.

Usando essas duas faixas, vamos para a primeira estoria: 

- **US001** -Criar fluxo de pagamento.

**Primeira questão:** "Essa estoria está **MAIS PERTO** do **3** ou do **8**?

No momento o time faz uma votação pra saber se está mais perto de um ou de outro e digamos que o time decidiu o seguinte: 

Time: "Está mais próxima do **3**."

**Segunda questão:** "Essa estoria é IGUAL (nível de complexidade) a estoria que definimos em nossa régua como **3**?

Time: "É mais difícil do que 3" 

E ai nesse momento não terá a tréplica e **assumimos essa estoria como 8** (porque pode ocorrer de nesse caso ser mais fácil que 8 e assumimos apenas duas faixas, ou seja, vamos definir para um lado e para o outro e de novo, não vamos arredondar para baixo).

Vai haver gente chorando e achando ruim, MAS, esse é o caminho para que em curto e médio prazo consigamos dar melhor previsibilidade as coisas, então você leitor (scrum master, agile coach ou pessoa que assumiu o processo) pegue pra si essa responsabilidade e vai até o fim porque os frutos vão aparecer.

- **US002** - Criar layout da página de Login/Logout/Esqueci Minha Senha

**Primeira questão:** "Essa estoria está **MAIS PERTO** do **3** ou do **8**?

No momento o time faz uma votação pra saber se está mais perto de um ou de outro e digamos que o time decidiu o seguinte: 

Time: "Está mais próxima do **3**."

**Segunda questão:** "Essa estoria é IGUAL (nível de complexidade) a estoria que definimos em nossa régua como **3**?

Time: "Sim, tem o mesmo grau de dificuldade ou até mais fácil que **3**"

E então assumimos essa estoria como **3** .

Essa prática funciona como um remédio amargo que tem que ser tomado, é uma maneira de acertarmos aos poucos o nível de planejamento e também nos coloca em uma situação que ao longo do tempo (e o ideal é que se faça isso APENAS em três sprints) passamos a ter mais confiança naquilo que fazemos.

Após o terceiro sprint utilizando dessa técnica, podemos então abrir a terceira faixa (5) e ficaria o diálogo mais ou menos assim: 

- **US001** -Criar fluxo de pagamento.

**Primeira questão:** "Essa estoria está **MAIS PERTO** do **3** ou do **8**?
**Time:** "Está mais próxima do **8**."

**Segunda questão:** "Essa estoria é IGUAL (nível de complexidade) a estoria que definimos em nossa régua como **3**?
**Time:** "Não, essa estoria é mais fácil que nossa estorias de 8 pontos"

**Terceira questão:** "Essa estoria é igual nossa estoria de **3**?
**Time:** "Não, é mais difícil"

E então nesse momento que abrimos a **terceira** faixa, justamente o 5 e colocamos essa estoria como primeira a herdar a posição para que nos plannings futuros possa ser comparada.

Esse exercício faz com que o 5 saia da zona de conforto e então chegamos ao momento que estimar 5 passa a ser mais "próximo da realidade" do que antigamente. 

## QAs podem ajudar

QAs podem ajudar a não errarmos por preguiça e vou listar algumas ações que possam fazer o time refletir sobre o tamanho do item a ser desenvolvido: 
- Planejar os testes antes do planning
    - Quando evitamos os problemas e os antecipamos, conseguimos mostrar para o time a quantidade de testes que supostamente vamos executar para aquele item em específico. Esses testes podem ser feitos junto com a área de produto, assim como pode ser apresentado ao Product Manager ou Product Owner antes de realizar o planning. Escrever antes os testes e os mostrar antes da fase de construção faz com que nosso time tome atenção a todos os casos durante o processo de desenvolvimento.
- Criar um mapa mental
    - O mapa mental é uma maneira vital para ajudar o time a pensar em quais pontos do nosso produto que supostamente aquela feature em questão pode ser decisiva (ou seja, que possa haver algum tipo de ligação). Mostrando no mapa, podemos enxergar quantas partes do nosso produto possa vir ser afetada caso façamos essa feature em questão. O mapa mental também serve como comparativo, pois conseguimos traçar a estimativa de acordo com a quantidade de lugares onde essa feature possa afetar no nosso produto.

## Conclusão

Para concluir esse tópico, quando passamos a ter comparativos, conseguimos chegar perto de estimativas mais confiáveis e uma das maneiras de termos um pouco de fator comparativo, podemos criar uma régua de estimativas para que possamos colocar o que foi feito (obviamente que não podemos colocar na nossa régua uma história que falamos 3 e estamos cerca de 10 sprints com a mesma historia sendo desenvolvida) e passar a comparar e claro, a régua é uma ferramenta que deve ser frequentemente atualizada.

Lembrando que comparativo não pode ser levado como verdade absoluta, e sim apenas como uma ferramenta de estimativa onde estaremos mais próximo do que julgamos ser "o certo."

Aceitar que muitas vezes utilizamos o 5 como muleta para "tirar o nosso da reta" e criar uma maneira efetiva de melhorar o que estimamos.

Quanto mais próximos do "certo" estivermos, melhor será para nossa auto estima e nosso lado para com a área de produto será melhor visto, teremos mais confiança e vão confiar mais no time.

[Início](https://github.com/thiagomarquessp/dividir-para-conquistar/blob/master/README.md)