# Questões de variáveis e condicionais

<details>
<summary>O Pequeno Príncipe</summary>

### Problema

O livro _O Pequeno Príncipe_ é conhecido por apresentar ao leitor frases bonitas e marcantes. Uma delas é:

_Se tu vens, por exemplo, às quatro da tarde, desde às três eu começarei a ser feliz._

Essa frase pode ser interpretada de várias maneiras. Um matemático, por exemplo, poderia interpretar, de uma forma absurdamente racional e exata, que a pessoa começa a ser feliz a exatamente uma hora antes da outra que ela está aguardando chegar.

Seguindo essa lógica, crie um programa que, ao receber a hora (sempre inteira) em que uma pessoa chegará, mostre a hora que a pessoa que está aguardando começará a ser feliz.

### Entrada

A entrada do problema será sempre composta por uma variável:

- `horaChegada` do tipo inteiro. Essa é a hora que a pessoa chegará.

### Saída

Você deve imprimir na tela a _hora_ em que a pessoa que está aguardando começa a ser feliz.

</details>

<details>
<summary>Dupla de prova</summary>

### Problema

Uma escola resolveu implementar um sistema de provas no qual a última prova de cada matéria é feita em dupla. A escola espera que isso ajude os alunos que estão indo mal a não desistirem.

Para não prejudicar os bons alunos, a escola decidiu que a diferença entre as notas dos dois alunos da dupla deveria ser menor que 1.5 pontos, pois, desta forma, a dupla estaria equilibrada com estudantes que estão com rendimentos próximo. Isso evitaria que algum aluno que estivesse com nota alta tivesse que fazer dupla com algum com nota muito baixa.

Você foi contratado pela escola para implementar o programa que indique aos professores se a dupla que eles estão formando é ou não válida de acordo com critério estabelecido acima.

### Entrada

Seu programa será composto por duas entradas:

- `notaAlunoA`: variável numérica que armazena a nota de um dos alunos da dupla;
- `notaAlunoB`: variável numérica que armazena a nota do outro aluno da dupla.

### Saída

Seu programa deve imprimir:

- `DUPLA VALIDA`: os membros da dupla tenham notas próximas;
- `DUPLA INVALIDA`: caso contrário.

</details>

<details>
<summary>Períodos históricos</summary>

### Problema

Como forma de facilitar o estudo, podemos dividir a história da humanidade em quatro grandes períodos, também chamados de "Idades". São eles:

- Idade antiga: vai de 4000 anos a.C., até a queda do Império Romano do Ocidente, em 476 da era cristã;
- Idade média: tem início depois de 476 e vai até a tomada de Constantinopla, pelos turcos otomanos, em 1453;
- Idade moderna: tem início depois de 1453 e vai até o ano de 1789, data da Revolução Francesa;
- Idade contemporânea: tem início após 1789 até os dias atuais.

Crie um programa que ao receber um ano retorne qual o período da história aquele ano se refere.

### Entrada

A entrada do problema será sempre composta por um variável:

- `ano` do tipo inteiro. Essa variável armazena o valor do ano que está sendo analisado.

### Saída

Você deve imprimir na tela qual o período da história o ano está inserido:

- `ANTIGA` se o ano está entre -4000 (4000 a.C.) e 476;
- `MEDIA` se o ano está entre 477 e 1453;
- `MODERNA` se o ano está entre 1454 e 1789;
- `CONTEMPORANEA` se o ano está após 1789.

</details>

<details>
<summary>Aprovação rigorosa</summary>

### Problema

Uma escola resolveu implementar um sistema de aprovação mais rigoroso. Para que um aluno seja aprovado e passe de ano ele deve:

- Ter uma `média` mínima de 60 pontos, `frequência` mínima de 75% e não ter zerado o `projeto final` ou
- Apesar de não ter obtido `média` mínima de 60, o aluno deve ter uma `frequência` mínima de 75% e ter obtido uma nota no `projeto final` de no mínimo 85 pontos.

Você deve criar um programa que verifique se um aluno está ou não aprovado de acordo com sua média, sua frequência e a nota que ele obteve no projeto final.

### Entrada

A entrada do problema será sempre composta por três variáveis:

- `media` do tipo number. Essa variável armazena o valor da média do aluno analisado;
- `frequencia` do tipo number. Essa variável armazena a frequência, em porcentagem, do aluno analisado;
- `projetoFinal` do tipo number. Essa variável armazena o valor da nota obtida no projeto final do aluno analisado.

### Saída

Você deve imprimir na tela:

- `APROVADO` caso o aluno tenha sido aprovado;
- `REPROVADO` caso o aluno tenha sido reprovado.

</details>

<details>
<summary>Superdotados</summary>

### Problema

Segundo a revista Veja, em uma matéria divulgada no ano passado, um paulistano de 8 anos tornou-se o mais novo membro da Mensa Internacional, associação fundada em 1946 na Inglaterra, presente em mais de 100 países e que reúne cerca de 150 000 superdotados. A inclusão é feita após a realização de testes de quociente intelectual (Q.I.). O jovem prodígio brasileiro obteve 140 pontos, bem acima da média mundial, que ronda os 90.

Sabendo que para uma pessoa ser considerada superdotada ela deve obter uma pontuação mínima de 130 pontos, crie um programa que diga se a pessoa analisada é ou não superdotada.

### Entrada

A entrada do problema será sempre composta por um variável:

- `qi` do tipo number. Essa variável armazena o valor do Q.I. da pessoa analisada.

### Saída

Você deve imprimir na tela:

- `SUPERDOTADA` caso a pessoa seja superdotada;
- `NAO SUPERDOTADA` caso a pessoa não seja superdotada.

</details>

<details>
<summary>Nível do tanque</summary>

### Problema

Um sensor de nível consegue detectar quando um tanque está quase vazio. Quando o nível do tanque é menor que 10 centímetros. Quando o tanque está quase vazio, aparece no console a mensagem `TANQUE QUASE VAZIO`. Caso contrário, a mensagem que aparece é `TANQUE OK`.

### Entrada

A entrada deste problema será sempre uma variável do tipo number chamada `nivel` que representa o nível atual do tanque, em centímetros.

### Saída

Você deve imprimir na tela `TANQUE QUASE VAZIO` caso o nível seja menor que 10 centímetros. Caso contrário, imprima na tela `TANQUE OK`.

</details>

<details>
<summary>Lavanderia self service</summary>

### Problema

Muito popular nos Estados Unidos e na Europa, na lavanderia self service, como o próprio nome indica, o cliente utiliza os serviços dos estabelecimentos para lavar e secar suas roupas por conta própria. O maquinário e os produtos necessários para a lavagem são disponibilizados pela empresa.

Uma empresa de lavanderia self service te contratou para programa um novo sistema de pesagem de roupa que eles estão desenvolvendo, que irá evitar que o cliente coloque mais roupa que a lavadora suporta ou menos roupa do que o permitido. Nesse sitema, o cliente coloca suas roupas em uma balança e uma mensagem é impresa em um visor avisando o cliente se ele pode ou não colocar as roupas na máquina.

A empresa solicitou que esse sistema imprima o seguinte na tela:

- `POUCA ROUPA`: caso o cliente queira colocar na máquina 10kg ou menos do que a máquina suporta. Isso evitará que o cliente tente colocar pouca roupa para lavar e ocupe a máquina que poderia estar sendo usada por outras pessoas;
- `MUITA ROUPA`: caso o cliente tente colocar mais roupa, em peso, que a quantidade de roupa que a lavadora suporta;
- `PERMITIDO`: caso contrário.

### Entrada

Sua entrada será formada por duas variáveis:

- `peso`: do tipo numérico. Peso da roupa do cliente;
- `pesoSuportado`: do tipo numérico. Peso suportado pela balança.

### Saída

Você deve imprimir na tela:

- `POUCA ROUPA`: caso o cliente queira colocar na máquina 10kg ou menos do que a máquina suporta;
- `MUITA ROUPA`: caso o cliente tente colocar mais roupa, em peso, que a quantidade de roupa que a lavadora suporta;
- `PERMITIDO`: caso contrário.
</details>

<details>
<summary>Resultado do jogo</summary>

### Problema

Você está trabalhando num site de notícias esportivas e ficou responsável pelo "Minuto a minuto" de jogos de futebol. Nesta parte do site é exibido o placar do jogo e informações atualizadas a cada minuto sobre a partida. A página já foi desenvolvida por um colega e o seu papel é fazer uma pequena atualização. Dado o placar de um jogo, você precisa exibir na tela um pequeno status que informa:

- Se o time A está ganhando
- Se o time B está ganhando
- Se o jogo está zero a zero
- Se o jogo está havendo um empate com gols

Cada partida necessariamente terá apenas um status.

### Entrada

A entrada será sempre composta por duas variáveis `golsA` e `golsB` que guardam, respectivamente, a quantidade de gols que cada um dos times A e B fez na partida até o momento. As variáveis são, claro, do tipo number.

### Saída

Você deverá imprimir na tela apenas um dos quatro status possíveis:

- `TIME A GANHANDO` - caso o time A esteja ganhando
- `TIME B GANHANDO` - caso o time B esteja ganhando
- `SEM GOLS ATE O MOMENTO` - caso o jogo esteja 0 a 0
- `EMPATE COM GOLS` - caso o jogo esteja empatado, mas com ambos os times tendo marcado gols

</details>

<details>
<summary>Sistema anticolisão</summary>

### Problema

A Tesla, empresa automotiva e de armazenamento de energia norte americana, está desenvolvendo carros autômatos, que são carros que oferecem algumas funções autônomas importantes da condução e uma direção sem qualquer interferência humana.

Você, como programador da empresa, está responsável por desenvolver o sistema que evitará que a colisão desses carros em rodovias. Para isso, o sistema inteligente desses veículos deve tomar alguma ação nas seguintes situações abaixo:

- Diminuir levemente a velocidade do carro: caso o sensor de distância identifique algum objeto a menos de 200 metros do carro;
- Diminuir drasticamente a velocidade do carro: caso o sensor de distância identifique algum objeto a menos 100 metros do carro;
- Parar o carro: caso o sensor de distância identifique algum objeto a uma distância menor ou igual a 50 metros do carro.

Sendo:

- Uma diminuição leve de velocidade é diminuir 15km/h;
- Uma diminuição drástica de velocidade é diminuir a velocidade do carro pela metade;
- Parar o carro e levar a velocidade do carro para 0.

### Entrada

Sua entrada será composta por duas variáveis:

- `velocidade`: variável numérica que mostra a velocidade atual do carro;
- `leituraSensor`: variável numérica que mostra a leitura que o sensor de distância está tendo.

### Saída

Você deve imprimir na tela velocidade do carro após receber a leitura do sensor e conseguir realizar a ação a ser tomada.

</details>

<details>
<summary>Marcador de vida</summary>

### Problema

Em um determinado jogo de plataforma, parecido com o jogo Mário, um personagem deve evitar diferentes tipos de inimigos. Os inimigos são divididos em classes pelo grau de periculosidade, ou seja, o quão perigosos eles são para o personagem. Existem 4 classes de inimigos:

- Classe 1: inimigos que tiram 20 pontos de vida;
- Classe 2: inimigos que tiram 30 pontos de vida;
- Classe 3: inimigos que tiram 40 pontos de vida;
- Classe 4: inimigos que tiram 50 pontos de vida.

Você deve criar a lógica do jogo que verifica a quantidade de vida de um personagem toda vez que ele encosta em um inimigo. Para isso, seu código deve, a partir de uma variável que armazena a vida atual do personagem, mostrar se o jogador perdeu o jogo (vida menor ou igual a zero). Se ele não tiver perdido, você deve mostrar quanto de vida ainda resta para que ele perca.

### Entrada

A entrada do problema será sempre composta por 2 variaveis:

- `vida` do tipo number. Essa variável mostra a vida do personagem antes de esbarrar no inimigo;
- `classe` do tipo number. Essa variável mostra a classe do inimigo que o jogador encostrou.

### Saída

Você deve imprimir na tela:

- A vida do personagem depois de ter esbarrado no inimigo, caso ele ainda esteja vivo;
- `PERDEU` caso a vida do personagem depois de ter encostado no inimigo seja menor ou igual a zero.

</details>

<details>
<summary>[Arrays] Pódio de uma corrida</summary>

## Problema

Você foi contratado pela Fórmula 01 para desenvolver um programa que mostre no telão os nomes dos competidores que pegaram pódio (três primeiros colocados) em uma corrida.

## Entrada

Sua entrada será composta por um _array_ chamado `colocacoes`, que armazena os nomes dos competidores em ordem de colocação, do primeiro ao último.

## Saída

Você deve imprimir os nomes dos competidores que pegaram pódio separados por vírgula.

</details>

<details>
<summary>[Arrays] Classificação uma corrida</summary>

## Problema

Você foi contratado pela Fórmula 01 para desenvolver um programa que mostre no telão os nomes, em ordem de colocação, dos competidores de uma corrida.

## Entrada

Sua entrada será composta por um _array_ chamado `colocacoes`, que armazena os nomes dos competidores em ordem de colocação, do primeiro ao último.

## Saída

Você deve imprimir os nomes dos competidores, do primeiro ao último colocado.

</details>

<details>
<summary>[Arrays] Correção da prova de redação </summary>

## Problema

A correção de provas de redação gera polêmicas por se tratar de algo subjetivo, ou seja, às vezes um professor acha uma determinada redação boa e outro professor não acha.

Com o intuito de evitar injustiças, uma escola resolveu adotar um sistema de correção de redações inspirado no ENEM. Esse sistema funciona da seguinte forma:

1. Dois professores corrigem a mesma prova e cada um dá uma nota entre 0 e 1000;
2. Um programa verifica se existe uma diferença maior que 100 entre as notas dadas por cada professor. Se não existir, a nota final do aluno é dada pela média entre essas duas notas; se existir, o programa avisa que aquela prova deve passar por um terceiro professor corretor.

Seu trabalho, enquanto programador dessa escola, é criar o programa que implementa a lógica descrita acima.

A média é dada por:

**Média = $\frac{nota1 + nota2}{2}$**

em que, **nota1** é a nota dada pelo primeiro professor corretor, e **nota2** pelo segundo.

## Entrada

Sua entrada será composta por um _array_ chamado `notas`, que armazena, respectivamente, as notas dadas pelo primeiro e segundo corretores.

## Saída

Você deverá imprimir na tela:

- O valor da média, caso a diferença entre as notas dadas pelos dois professores corretores seja de, no máximo, 100 pontos;
- `TERCEIRO CORRETOR DEVE SER CHAMADO`, caso contrário.

</details>

<details>
<summary>[Arrays - Desafio] Robô separador de frutas</summary>

## Problema

Um robô precisa coletar frutas de uma esteira e colocar numa caixa. Ele usa um sistema de câmeras para identificar quais frutas estão passando.

Você foi contratado pela empresa para realizar a programação deste robô e criar um sistema que mostre aos operadores a quantidade de frutas que o robô coletou. A esteira de frutas é representada por um array em que cada posição armazena uma fruta diferente que passou pela esteira. O robô recebe como parâmetro qual fruta ele deve coletar.

## Entrada

Sua entrada será composta de duas variáveis:

- `frutaColetada`: variável do tipo string que armazena a fruta a ser coletada pelo robô;
- `esteira`: array de strings em que cada posição armazena uma fruta que passou pela esteira.

## Saída

Você deve imprimir na tela a quantidade de frutas que o robô coletou.

</details>

<details>
<summary>[Objetos] Dados de um personagem</summary>

## Problema

Você foi contratado pela Ubisoft, uma das maiores empresas de desenvolvimento de jogos do mundo, como desenvolvedor. Seu papel é criar a parte do programa que exibe as informações do personagem de um jogador.

## Entrada

A entrada do seu programa será composta por um objeto chamado `personagem`, que armazena os dados do personagem do jogador. Cada personagem tem um nome, uma classe e um nível de força.

## Saída

Você deve imprimir na tela uma mensagem no seguinte modelo:

```
Olá, NOME_PERSONAGEM! Você é um NOME_CLASSE de nível NIVEL_FORCA.
```

## Exemplo

### Entrada

```js
let personagem = {
  nome: "Shaolin Matador de Porco",
  classe: "mago",
  nivel: 20,
};
```

### Saída

```
Olá, Shaolin Matador de Proco! Você é um mago de nível 20.
```

</details>

<details>
<summary>[Objetos] Luta entre personagens</summary>

## Problema

Você foi contratado pela Ubisoft, uma das maiores empresas de desenvolvimento de jogos do mundo, como desenvolvedor. Seu papel é criar a parte do programa responsável pelas batalhas de um jogo, dizendo qual personagem saiu vitorioso.

Cada personagem é representado por um objeto com o seguinte formato:

```js
let personagem = { nome: "Goku", classe: "mago", nivel: 28 };
```

## Entrada

A entrada do seu programa será composta por dois objetos:

- `personagem1`, que armazena os dados de um dos personagens a lutar;
- `personagem2`, que armazena os dados do outro personagens a lutar.

## Saída

Você deve imprimir na tela o nome do personagem que venceu a luta. A luta sempre é vencida pelo personagem com maior nível.

## Exemplo

### Entrada

```js
let personagem1 = {
  nome: "Shaolin Matador de Porco",
  classe: "mago",
  nivel: 20,
};

let personagem2 = {
  nome: "Flavim do Pneu",
  classe: "guerreiro",
  nivel: 10,
};
```

### Saída

```
Shaolin Matador de Proco venceu!
```

</details>

<details>
<summary>[Objetos - Desafio] Próximo nível</summary>

## Problema

Você foi contratado pela Ubisoft, uma das maiores empresas de desenvolvimento de jogos do mundo, como desenvolvedor. Seu papel é criar a parte do programa responsável por controle do nível do personagem.

## Entrada

A entrada do seu programa será composta por duas variáveis:

- Um objeto chamado `personagem`, que armazena os dados do personagem do jogador. Cada personagem tem um nome, uma classe, um nível de força, a informação de quantos pontos precisasse para avançar de nível e a pontuação atual do jogador;

- `pontosConquistados`, que armazena quantos pontos o jogador conquistou na rodada analisada pelo código.

## Saída

Você deve imprimir na tela qual o nível do personagem após conquistar os pontos na rodada.

## Exemplo

### Entrada

```js
let personagem = {
  nome: "Shaolin Matador de Porco",
  classe: "mago",
  nivel: 20,
  pontuacaoNecessaria: 1500,
  pontuacaoAtual: 1300,
};
let pontosConquistados = 200;
```

### Saída

```js
21;
```

### Explicação do exemplo

O personagem precisava de 1500 (`pontuacaoNecessaria`) pontos para avançar para o próximo nível. Ele tinha 1300 (`pontuacaoAtual`) pontos acumulados e conquistou mais 200 (`pontosConquistados`) pontos na rodada. Com isso, o jogador, ao final da rodada, tem 1500 pontos, o que é suficiente para o avanço de nível.

</details>