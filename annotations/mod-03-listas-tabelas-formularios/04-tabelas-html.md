# Tabelas
Tabelas são formas de exibir dados estruturados.
Criamos uma tabela com a tag **_table_** e configuramos quantas linhas e colunas ela terá

## Estrutura básica
table como o nome da tag, **tr** é a linha e **td** as colunas. Podemos aumentar a nossa vontade
a quantidade de linhas.
~~~ html
<table>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>
~~~

## Adicionando header da tabela
Para adicionar cabeçalho a tabela com usamos a tag **thead** e dentro dela declaramos:
a tag **th** é usado para declarar um coluna header
~~~ html
<table border="1">
    <thead>
        <tr>
            <th>item_001</th>
            <th>item_002</th>
            <th>item_003</th>
        </tr>
    </thead>
</table>
~~~

##  Properties
- **border**: define uma borda

## Formatar com css
É possível formatar nossa tabela livremente utilizando CSS.
Podemos usar as tags como selectors ou criar ID's/classes e se divertir alterando
tamanho de font, alinhamento de texto, background-color, bordar e etc
uma formatação interessante que aplica formatação de forma alternada no body da tabela
~~~ css
tbody tr:nth-child(even) {
    background-color: #EEE
}
~~~

thead
tr(table-row) th(table-head)
tbody
tr(table-row) td(table-data)


~~~ html
 <table>
      <thead>
        <tr>
          <th>Item_001</th>
          <th>Item_002</th>
          <th>Item_003</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>content_001</td>
          <td>content_002</td>
          <td>content_003</td>
        </tr>

        <tr>
          <td>content_001</td>
          <td>content_002</td>
          <td>content_003</td>
        </tr>

        <tr>
          <td>content_001</td>
          <td>content_002</td>
          <td>content_003</td>
        </tr>
        <tr>
          <td>content_001</td>
          <td>content_002</td>
          <td>content_003</td>
        </tr>
      </tbody>
    </table>
~~~