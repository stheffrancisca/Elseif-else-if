# Elseif-else-if
É uma combinação das duas instruções vistas. Logo, sua função é definir fluxo (ou fluxos) alternativo caso uma condição verificada com if seja falsa. Entretanto, ela permite ainda que uma nova condição (ou até mesmo condições) seja avaliada. Vamos ao exemplo de seu uso:


<?php

 $var1 = 10;
 $var2 = 10;

 if($var1 > $var2){
	echo "$var1 é maior que $var2";
 }elseif($var1 < $var2){
	echo "$var1 é menor que $var2";
 }else{
	echo "$var1 e $var2 são iguais";
 }
