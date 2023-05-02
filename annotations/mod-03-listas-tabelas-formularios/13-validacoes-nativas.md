# Validações nativas

## require
Obrigamos o preenchimento de um campo input

## minlength
Ao adicionarmos valor ao input ele cobra o tamanho mínimo de acordo o informado no valor de **_minlength_**

# maxlength
Ao adicionarmos valor ao input ele cobra o tamanho máximo de acordo o informado no valor de **_minlength_**

## step (number)
para campo de number o step informa de **n** em **n** valor ira acrescentar ou decrementar do valor ao clicarmos. Onde **n** é
igual ao valor que definirmos.

## min (number), (dates)
min define o numero inicial aceito em um campo de number. No caso de datas, o valor min inicial de uma data permitida

## max (number), (dates)
min define o numero máximo aceito em um campo de number. No caso de datas, o valor max  de uma data permitida

## pattern (email)
na validação do email podemos adicionar o valor de pattern que será uma expressão regular que define o padrão aceito. 