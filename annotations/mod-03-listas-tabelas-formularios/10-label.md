# Label
Label é usado para definir os nomes dos campos
Ele tem um propriedade chamada **for** que podemos adicionar referencia a um input 
assim eles ficam associados. Ou podemos associar adicionando o  input no scope do label

~~~ html
 <form action="page2.html" method="GET">
      <label for="1001">Nome:</label>
      <br />
      <input type="text" name="nome" id="1001" />
      <br />
      <br />
      <label>
        <input type="checkbox" name="aceitaTermos" id="" />
        aceito os termos de compromisso
      </label>
      <br />
      <br />
      <!-- <input type="submit" value="send"> -->
      <button>Send</button>
    </form>
~~~