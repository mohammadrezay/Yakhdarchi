# Yakhdarchi
https://quera.org/problemset/3429?tab=description
<?php
$T = (int)readline('Enter an integer: ');
if($T > 100) {
	echo "Steam";
} elseif($T < 0) {
	echo "Ice";
} else {
	echo "Water";
}
