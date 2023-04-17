# Tags(Elements)

Os primeiros components relacionados a html que estudaremos são os **_elementos_**, tbm conhecidos como **_tags_**
HTML nada mais é que um conjunto de vários elementos organizados de forma hierárquica em um documento de extensão **_.html_**.
alguns exemplos de elementos:

~~~ html
<h1>Cabeçalho de nível 01</h1>
<h2>Cabeçalho de nível 02</h2>
<h4>Cabeçalho de nível 02</h4>

linha horizontal
<hr/>

<p>Elemento para representar um paragrafo</p>
tag 'u' é o underline 
<strong>elemento que da ênfase a um <u>trecho</u></strong>

~~~

## Estrutura dos elementos
Como podemos notar os elementos são definidos por nomes onde se repetem para definir seu escopo de ação. Um elemento tem
se inicio definido pelos sinais de menor  **<**  e maior **>** com o nome do elemento dentro
ex:
~~~ html
<element-name>
~~~ 
e se fecha com a repetição  do elemento com uma barra assim definindo que é uma tag de fechamento. Agora tudo o que for 
definido dentro do escopo do elemento receberá o comportamento referente ao elemento definido

~~~ html
<element-name>
</element-name>
~~~

caso adicionássemos uma tag sem o '/' estaríamos definindo mais um elemento do mesmo tipo dentro do escopo do primeiro e o html
estaria esperando que ambos fossem fechados

~~~ html
<element-name>
    <element-name>
    </element-name>
</element-name>
~~~

Podemos observar que a uma das tags que não se comporta como essa estrutura que acabamos de  demonstrar, o elemento **<hr/>**
Esse elemento é um tipo que não recebe conteúdo, logo não precisa de um escopo. Podendo ser definida já como uma tag de 
fechamento. No caso o hr é usado para definir uma linha horizontal.

