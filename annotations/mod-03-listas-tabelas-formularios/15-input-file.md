# Input File
O input type file serve para que possamos enviar arquivos pelo form.
Devemos sempre add essa property no form quando adicionamos o input type:file
**enctype="multipart/form-data"**: essa property faz com que os dados seja mandado de forma
de bytes.

~~~ html
<form method="POST" action="action_path" enctype="multipart/form-data">
      <input type="file" name="file" id="file" accept="application/*">
</form>
~~~

O accept pode ter vários valores. Os explicados na aula
- image/.extension: imagem informando a extensão
- image/*: imagem informando a extensão pode ser de qualquer tipo de extensão de image
- application/pdf: filtra arquivos em formato pdf
- application/*: filtra arquivos em qualquer formato 

Lembrando que ainda é possível pegar qualquer formato. Mas em toda aplicação é natural que
o recebedor do recurso crie métodos de validação.