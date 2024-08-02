<h1 align="center">Base Banco de Dados</h1>


-------------------------------------------------------------------------------------------------------------
## Repositório para sempre que eu precisar ver coisas sobre banco de dados

-------------------------------------------------------------------------------------------------------------

<h2> ${\color{purple}OPERAÇÕES}$ ${\color{purple}MATEMÁTICAS:}$ </h2>

SOMA +

SUBTRAÇÃO -

MULTIPLICAÇÃO *

DIVISÃO /

RESTO DA DIVISÃO %

--------------------------------------------------------------------------------------------------------------


<h2>  ${\color{purple}FILTRO}$ ${\color{purple}WHERE}$ </h2>

MAIOR >

MENOR < 

IGUAL =

DIFERENTE DE <>

DIFERENTE DE !=

ENTRE between

--------------------------------------------------------------------------------------------------------------

<h2> ${\color{purple}EXEMPLOS}$ </h2>

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

Países com população entre 0 e 1000 habitantes

SELECT * FROM world.country c

WHERE c.Population BETWEEN 0 AND 1000;
