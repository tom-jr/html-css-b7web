# Inputs
Input são usados para fazer inputs

## Properties
- Input tem uma property para definir seu tipo **type**
- **name**: define um nome para aquele input
- **value**: define um valor default


~~~ html
<form action="path" method="POST">
      <label> text </label> <br />
      <input type="text" name="" id="" />
      <br />

      <label for="">password</label> <br>
      <input type="password" name="" id="" />
      <br>

      <label for="">radio</label> <br>
      <input type="radio" name="gender" id="">
      <input type="radio" name="gender" id=""> <br>

      <label for="">CheckBox</label><br>
      <input type="checkbox" name="" id=""> <br>

      <label for="">Email</label> <br>
      <input type="email" name="" id=""> <br>

      <input type="submit" value="Subimt"> <br>
    </form>
~~~

## Inputs do html_5
- **email** é um dos types que é suportado apenas na versão 05
- **color**: input de seleção de color.
- **date**: seleção de data, retorna ao submit com a data no formato internacional. É possível usar o type month que selecionará apenas
o mês. O type time para pegarmos apenas a hora. type week
- **number**: autoexplicativo
- **range**: um campo para selecionarmos um range
- **search**: uma variação do type text
- **tel**: type para telefones
- **url**: type text com validação para url
