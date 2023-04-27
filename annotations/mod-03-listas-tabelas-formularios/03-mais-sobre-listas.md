# Mais sobre Listas

Sabemos que existe as listas ordenadas e as desordenadas
ol ul

Podemos adicionar subList a uma lista

~~~ html
    <ul>
        <li>
            item 001
            <ul>
                <li>
                    sub_item 001
                    <ul>
                        <li>sub_sub_item 001</li>
                        <li>sub_sub_item 002</li>
                        <li>sub_sub_item 003</li>
                    </ul>
                </li>
                <li>sub_item 002</li>
                <li>sub_item 003</li>
            </ul>
        </li>
        <li>item 002</li>
        <li>item 003</li>
    </ul>
~~~

Styles de lista desordenadas ul
- **list-style-type:** disc|square|circle|none

Style de lista ordenada ol
- **type:** 1|A|a|I|i
- **start:** (n). Onde n é o numero que inicia a classificação dos itens da list 