<h1 align="center">Base Banco de Dados MySQL</h1>


-------------------------------------------------------------------------------------------------------------
<h3 align="center">:information_source:Repositório para sempre que eu precisar ver coisas sobre banco de dados:information_source: </h3>

-------------------------------------------------------------------------------------------------------------

<h2> ${\color{gray}OPERAÇÕES}$ ${\color{gray}MATEMÁTICAS:}$ </h2>

SOMA +

SUBTRAÇÃO -

MULTIPLICAÇÃO *

DIVISÃO /

RESTO DA DIVISÃO %

--------------------------------------------------------------------------------------------------------------


<h2>  ${\color{gray}FILTRO}$ ${\color{gray}WHERE}$ </h2>

MAIOR >

MENOR < 

IGUAL =

DIFERENTE DE <>

DIFERENTE DE !=

ENTRE between
<br></br>


<h2> ${\color{silver}EXEMPLOS}$ </h2>

Países com população acima de 100.000.000 de habitantes 
<br></br>
SELECT * FROM world.country c
<br></br>
WHERE c.Population >= 100000000; 
<br></br>
<br></br>

Países com população abaixo de 10.000 habitantes

SELECT * FROM world.country c

WHERE c.Population <= 100000; 
<br></br>
<br></br>

Países com população entre 0 e 1000 habitantes

SELECT * FROM world.country c

WHERE c.Population BETWEEN 0 AND 1000;
<br></br>
<br></br>






-------------------------------------------------------------------------------------------------------------

<h2> ${\color{gray}WHERE}$ ${\color{gray}com}$ ${\color{gray}texto}$ </h2>

AND - Mostra um registro se ambas as condições forem verdadeiras. <br></br>
OR - Mostra um registro se pelo menos uma das condições forem verdadeiras.<br></br>
IN - É utilizado quando desejamos consultar uma tabela filtrando o valor de um de seus campos.<br></br>
LIKE - Quando se deseja fazer uma busca por um caracter.<br></br>


<h2> ${\color{silver}EXEMPLOS}$ </h2>



SELECT * FROM world.country c
<br></br>
WHERE c.Continent = 'Asia';  <kbd>(**Filtrando para países da Asia apenas.**)</kbd>

<br></br>
<br></br>

SELECT * FROM world.country c
<br></br>
WHERE c.Continent IN ('Asia', 'Europe');  <kbd>(**Filtrando para países da Asia e Europa apenas.**)</kbd>

<br></br>
<br></br>

SELECT * FROM world.country c
<br></br>
WHERE length(c.Name) <=5;  <kbd>(**Filtrando para buscar todos os nomes que tenham 5 ou menos letras.**)</kbd> 

<br></br>
<br></br>

SELECT * FROM world.country c
<br></br>
WHERE c.Name LIKE 'A%';  <kbd>(**Filtrando para trazer tudo que começa com A e não importa oq venha depois, usando o LIKE pra isso.**)</kbd> 

<br></br>
<br></br>

SELECT * FROM world.country c
<br></br>
WHERE c.Name LIKE '_a%'; <kbd>(**Filtrando todos os países que tenham a segunda letra com a.&nbsp;
Pode-se usar quantos _ quiser, ele usa antes para ir pulando as letras até chegar na que precise.
Exemplo: Quero achar a palavra 'Mochila' mas só sei que tem o ch no meio, ai faço __ch% e coloco para rodar.**)</kbd> 





