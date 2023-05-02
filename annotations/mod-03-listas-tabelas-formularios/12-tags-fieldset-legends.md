# FieldSet Legends

FieldSet é usado para separar os dados de formulários que queremos classificar
Um exemplo simples é a separação dos dados pessoais e dados de endereço

A legenda é como o title do field set. 

E claro que podemos formata-los com CSS livremente.

~~~ html
    <form action="page2.html" method="GET">
      <fieldset class="no-bord">
        <legend>Personal Data</legend>
        <label for="nome">Nome</label>
        <input type="text" id="nome" />
        <label for="idade">Idade</label>
        <input type="number" id="idade" name="idade" />
        <label for="">E-mail</label>
        <input type="email" id="email" name="email" />
      </fieldset>

      <fieldset class="no-bord">
        <legend>Adress Data</legend>
        <label for="rua">Rua</label>
        <input type="text" name="rua" id="rua" />
        <label for="rua">Numero</label>
        <input type="number" name="numero" id="numero" />
        <label for="rua">Bairro</label>
        <input type="text" name="bairro" id="bairro" />
      </fieldset>
      <button class="no-bord">Send</button>
    </form>
~~~

