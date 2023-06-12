# @media
Utilizamos no css o @media para definir formatações de acordo com a largura que definirmos para essas formatações que
declararmos dentro do scope do @media

```css
@media(min-width: 1020px) {
    body {
        background-color: #ff00ff;
    }
}
```

a propriedade se declara com o @media() {}
entre os parâmetros passamos o arg de min-width. Assim indicando que as formatações de css iram durar até o domínio
determinado nos args. No exemplo apresentado estamos dizendo para o browser renderizar no body o background com  a cor FF00FF
até que o menor tamanho da viewport for 1020px

```css
@media(min-width: 770px) and (max-width:1019px) {
    body {
        background-color: blue;
    }
}
```

no exemplo acima definimos o escopo de aplicação da media em questão entre as larguras de 770 a 1019 o background do elemento 
body será azul


## only print

O media only print define propriedades apenas ao imprimir, que tem o atalho control+p.
```css
@media only print {
    body{
        color: black;
        font-size:50px.
    }
}
```

## only screen
O only screen define propriedades css que serão renderizada apenas no render da page web. Ao tentarmos imprimir as propriedades não 
estarão mais presente.

## all

No all, as propriedades definidas serão aplicada para o modo screen e print

## media orientation
No Orientation as propriedades css serão aplicadas de acordo com a orientação da tela. 
landscape(paisagem) ou portrait(vertical/retrato). A orientação é calculada pelos valores de width e height do screen

```css
@ media (orientation: portrait) {
    body {

    }
}

@media (orientation: landscape) {
    body {

    }
}
```

## aspect-ratio

Aspect ratio define propriedades com base em proporção de tela

1/1 : quando os valores de width e height forem idênticos
2/1 : quando os valores de width forem o dobro de height
1/2 : inverso de 2/1

Se usarmos o prefixo de min ou max as propriedades continuaram vigente.
```css
@media (aspect-ratio: 1/1) {}
@media (min-aspect-ratio: 2/1) {}
@media (max-aspect-ratio: 1/2) {}
```

## Função min e max


```css
img {
    width: max(50%, 300px);
}

div {
    width: max(50%, 300px);
}
```

## Função calc

podemos settar valores baseados em cálculos
```css
.container {
    width: calc(100% - 14px);
}
```