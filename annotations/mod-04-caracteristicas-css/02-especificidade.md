# Conceito de especificidade

O conceito de especificidade diz que quanto mais especifico for a declaração de uma propriedade css
maior será sua hierarquia de aplicabilidade.
Normalmente o css é aplicado por ordem de inserção de cima para baixo. Então a ultima edição de um elemento
será a aplicada. Porem quanto mais especifico for o el referenciado o css manterá aquela formatação.

Se dentro de uma div tem uma tag strong. E eu adicionar uma formatação para a tag strong. Não importará a ordem de inserção
o css respeitará minha edição para o strong:

~~~ html
<style>
    strong {
    color: blue;
}
    .div {
    color: red;
}
</style>
    
    <div >
    there is a <strong>pen</strong> on the table
    </div>
~~~

Lembrando que class fica no top, acima até do próprio nome do el. Mas não em relação a elementos filhos.
no caso se a class strong tenha uma formatação, mas existe uma class na tag, a formatação da class que terá 
prioridade. Mas para seus filhos a regra seria se existir uma formatação para os filhos o css respeitará ela.

classificação

1 - class
2 - tag/el
3 - tagParent
