# php-nl2br-str_pad
PHP nl2br str_pad function
<?php
// nl2br and str_pad
$a = "Bangladesh is my motherland.\nl I proud of my country";
echo nl2br($a);
echo "<br>";
$a= "bangladesh";
echo str_pad($a,20,".");
?>
