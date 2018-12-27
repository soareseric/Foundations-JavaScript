O JavaScript possui 6 tipos primitivos no momento, os quais veremos com mais detalhes depois.

São eles:

Boolean - possuem apenas dois valores: verdadeiro ou falso;
Undefined - indica que não foi definido um valor;
Null - indica que um valor é nulo;
Number - armazena valores numéricos;
String - armazena textos;
Symbol - armazena símbolos.




***************** BOOLEAN **************************
Boolean (também chamado em português como tipo Booleano) é o tipo mais básico existente nas linguagens de programação.

Assim como os bits, eles também só armazenam 2 possíveis valores: true ou false (verdadeiro ou falso).

Esse tipo é muito importante para que a gente faça o computador tomar decisões.




***************** UNDEFINED AND NULL **************************

Há dois tipos especiais de valores, undefined e null. Eles indicam a ausência de valor.

Imagine que você tenha um formulário que pergunta a idade de uma pessoa, e ela não respondeu ainda. Não podemos dizer que a idade dessa pessoa é 0. O melhor seria indicar que um valor não foi dado, e nesse caso, usaríamos undefined ou null.

Há uma diferença bem pequena entre undefined e null. Na verdade a existência de ambos para definir um valor inexistente foi devido a um acidente no projeto do desenvolvimento do JavaScript. Em outras linguagens de programação, normalmente existe apenas o Null.

Não precisa se preocupar em saber a diferença entre eles agora. Apenas saiba que são usados para definir algo que não tem valor.




***************** NUMBER **************************

O tipo number é usado para armazenar valores numéricos.

Podemos ter números inteiros (sem casas decimais) e números flutuantes (com casas decimais, a qual é indicada por um ponto). As linguagens de programação normalmente têm vários tipos de valores numéricos, mas no JavaScript tudo é Number.

Número inteiro: 5

Número flutuante: 5.3157

Para números muito grandes, podemos usar a notação científica, adicionando um "e" seguido pelo expoente do número.

Ex: 2.998e3  isso é o mesmo que 2,998 x 108, que é igual a 299.800.000

//// Números Especiais

Também temos três valores especiais no JavaScript que são considerados do tipo Number, mas não são números comuns.

Os dois primeiros são o Infinity e -Infinity, que indicam valores infinitos positivos e negativos.

O último é o NaN (not a number). Esse valor do tipo Number indica que um valor não é um número. Por exemplo, se você tentar multiplicar a letra "a" pelo número 5, o resultado não pode ser um número, então resultará em NaN.




***************** STRINGS **************************

As Strings são usadas para representar textos. Sempre que quisermos um texto teremos que incluir aspas entre o texto, duplas ou simples.

As aspas servem para definir onde um texto começa e onde ele termina. Em JavaScript, para manter um padrão de código, é recomendado usar as aspas simples.

Porém, se você precisar usar aspas simples em um texto, é mais fácil criar a String com aspas duplas, ou sua String será fechada:

"Mc Donald's" → A aspa simples pôde ser usada normalmente dentro desta String

'Mc Donald's' → Após o "d", a aspa simples fechou a string, deixando o "s" e a outra aspa soltos. Isso irá resultar em um erro.

Hoje em dia também temos um novo tipo de string, que usa o acento grave (crase) ao invés de aspas. Mais para frente veremos melhor sobre como trabalhar com Strings e a importância desse novo tipo de String.



***************** SYMBOL **************************

O Symbol é um novo tipo primitivo do JavaScript. Ele é um tipo de dado que é único e imutável. Podemos usá-los como identificadores de propriedades de objetos, que conheceremos melhor mais para frente.


***************** VALORES VERDADEIROS E FALSOS **************************


Outros valores no JavaScript possuem valores equivalentes ao true e false.

Um exemplo é o número 0. Ele representa tanto o número zero quanto o valor false. Isso signifca que fazer uma comparação com ele seria o equivalente a fazer uma comparação com false.

Os seguintes valores são considerados falsos no JavaScript:

0;
-0;
null;
false;
NaN;
undefined;
"" (string vazia).
Qualquer outro valor é considerado true, até mesmo a String "false" e "0", pois não são Strings vazias.