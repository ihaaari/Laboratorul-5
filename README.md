# Laboratorul-5
Comentarea codului

<?php
echo "<h3> Exersaiz 6 (c) Albot Igor </h3>"; 
//Declaram variabilele 
$aa=6;
$bb=12;
$cc=30;
echo "laturile triunghiului <br> a=$aa, b=$bb, c=$cc <br>";
//Calculam perimetrul triunghiului
$per2 = $aa+$bb+$cc;
echo "Perimetrul triunghiului = $per2 <br>";
//Calculam semi-perimetru
$semiper2 = $per2/2;
//Calculam aria
$a2 = sqrt($semiper2*($semiper2-$aa)*($semiper2-$bb)*($semiper2-$cc));
echo "Aria este =". round($a).  "<br>";

echo "<h3> Exersaiz 7 (c) Albot Igor </h3>";
//Declaram o variabila cu valoare 127
$n7=127;
echo "Valoarea initiala= $n7 <br>";
//Afisam ultima cifra anr. 127 
echo "Rezultatul=".$n7%10 ."<br>";

echo "<h3> Exersaiz 8 (c) Albot Igor </h3>";
//Declaram lungimea sirului n, deamenea o variabila ce va contine suma si o variabila contor
$n8=-10;
$s8=0;
$k8=0;
//Acest for calculeaza suma nr. negative pare mai mari ca n, iar contorul stocheaza cate aceste istante avem
for($i=-1;$i>$n8;$i--){
    if($i%2 == 0) {
        $s8+=$i;
        $k8++;
        echo $i;
        echo "<br>";
    }
}
//Calculam si afisam media aritmetica a nr. mai mari ca n
$m=$s8/$k8; 
echo "Media=" .round($m) . "<br>";
?>
