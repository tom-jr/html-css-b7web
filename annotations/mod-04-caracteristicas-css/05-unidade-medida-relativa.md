# Unidade de medita absoluta (Fonte)

**em**: usa a medida de uma el pai como base progressiva.

el pai = 10px
então
el filho = 2em  equivale a 2.10 = 20px

caso o filho tenha um subElemento o mesmo se aplica em relação ao seu pai.

el grandFather = 10px

el father = 2em = 20px

el son = 3em = 60px

**rem**: funciona de forma semelhante, a diferença é que a base de medida não recebe do el pai. Mas sim de um root:

el grandFather = 10px

el father = 2rm = 20px

el son = 3rm = 30px

**porcentagem**:
sett valor em porcentagem. A porcentagem se aplica ao total do elemento pai.

body = 1000px
div child tem 50% de medida, então o tamanho será 500px. Que é 50% de 1000px.

**ch**: medida baseada no espaço que ocupa um caractere de uma font. Funciona de forma adequada com fonts mono-espaçadas.
**ex**: medida de unidade baseada no caractere 'x' da font que esta sendo usada

**vh/vh**: medida baseada no tamanho de viewport. Caso uma viewport tem o o tamanho de 1000px a medida de 50vh sera de 500px.
Assim vai escalando de acordo com a medida em tempo real da viewPort

**inherit** força uma herança de um valor de elemento PAI

