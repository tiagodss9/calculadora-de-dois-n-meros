# calculadora-de-dois-n-meros
calculadora simples de dois números para incrementar o aprendizado
<?php
echo "calculadora de dois numero simples.\n";
echo "Digite seu primeiro número:";
$n1 = fgets(STDIN);
echo "$n1";
echo "Digite seu segundo número:";
$n2 = fgets(STDIN);
echo "$n2";
echo "\nDigite a operação desejada:\n";
$operacao = floatval(fgets(STDIN));
switch ($operacao) {
    case "+":
    echo "a operação selecinada foi soma portanto o valor da sua soma é:\n",$n1+$n2;
    break;
      case "-":
    echo "a operação selecinada foi subtração, portanto o valor da sua subtração é:\n",$n1-$n2;
    break;
     case "*":
    echo "a operação selecinada foi multiplicação, portanto o valor da sua multiplicação é:\n",$n1*$n2;
    break;
 case "/":
    echo "a operação selecinada foi divisão, portanto o valor da sua divisão é:\n",$n1/$n2;
    break;
    default:
    echo "infelimente você digitou uma operação invalida.";
        break;
}



?>
