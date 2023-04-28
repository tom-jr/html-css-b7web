# Select
O elemento select é bem autoexplicativo. Uma tag select onde em seu escopo declaramos as options
caso queiramos selecionar múltiplos, adicionamos o size máximo de intens selecionáveis e informamos
que é **multiple**

~~~ html
 <form action="page2.html" method="GET">
      <select name="single-select">
      <option value="value_001">option 001</option>
      <option value="value_002">option 002</option>
      <option value="value_003">option 003</option>
      <option value="value_004">option 004</option>
      </select> <br>
      <select name="multiple-select" multiple size="2">
      <option value="value_001">option 001</option>
      <option value="value_002">option 002</option>
      <option value="value_003">option 003</option>
      <option value="value_004">option 004</option>
      </select> <br>
      <input type="submit" value="send">
    </form>
~~~