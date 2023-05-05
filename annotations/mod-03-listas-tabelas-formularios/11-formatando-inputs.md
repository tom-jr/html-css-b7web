# Formatando

Dados interessante sobre css

Propriedade **display** pode ser *inline* ou *block*. No decorrer de elementos que vou adicionando na pagina que sejam
display in line os elementos vão se acumulando ao lado um do outro, pois todos por default são inline. Caso eu mudar para 
block os elementos ficam um abaixo do outro.

Quando queremos especificar mais a formatação, podemos adicionar o type input que nos referimos
input[type='text']
input[type='email']

~~~ css
label {
  display: block;
  margin-bottom: 3px;
}
input[type='text'],
input[type='email'],
input[type='number'] {
  margin-bottom: 3px;
  border: 1px solid #bbb;
  border-radius: 5px;
  display: block;
}
~~~

A propriedade css **outline** altera aquele efeito de quando clicamos em um input.
Caso queiramos que não apareça sett o valor como zero

Para o text area podemos definir uma propriedade css **_resize_** como none para
que não seja mais possível alterar o tamanho do text area a vontade