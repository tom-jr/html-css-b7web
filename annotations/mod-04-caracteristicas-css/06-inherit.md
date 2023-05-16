# Inherit
Nesta aula é ensinado uma forma de pegar uma herança de uma class ou elemento

~~~ css
.class {
    font-size: 20px;

}

h1 {
    font-size: 10px
}
// se quiser que um h1 que esta dentro de class herde o font-size de 20px, devo add o seguinte

.class h1 {
    font-size: inherit;
}
~~~

Assim ao invés da especificidade, será obedecido a herança