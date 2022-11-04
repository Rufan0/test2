<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Test Login</title>
</head>
<body>




	<br>
	<hr>





	<?php 


	/*

	$dizi = array("alma","armud","heyva","nar","uzum");

	echo "<pre>";
	print_r($dizi);
	echo "</pre>";

	echo "$dizi[0]"; echo "<br>";echo "<br>";





	$sayi = count($dizi);

	for ($i=0; $i <=$sayi; $i++) { 
		


		echo $dizi[$i]; echo " ";
	}
*/
	?>

	<form action="" method="POST">

		<input type="number" name="$a">
		<input type="number" name="b">
		<input type="submit" value="Hesabla">

	</form>




	<?php 


	$deyer1=$_POST['a'];
	$deyer2=$_POST['b'];



	function topla($reqem1,$reqem2) {

		echo $reqem1+$reqem2;
	}
	

	echo "<br>";

	topla($deyer1,$deyer2);







	?>



<?php 	/* <?php 


	$deyer1=$_GET['a'];
	$deyer2=$_GET['b'];



	function topla($reqem1,$reqem2) {

		echo $reqem1+$reqem2;
	}
	

	echo "<br>";
	
	topla($deyer1,$deyer2); */ ?>
	
	<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>


</body>
</html>
