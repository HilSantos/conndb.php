# conndb.php
Criação do include do PHP.

<?php
$servidor = "localhost";
$banco = "db_proj35";
$db_user = "adminti35";
$db_senha = "789abc";
$link = mysqli_connect($servidor, $db_user, $db_senha, $banco);

-- Digitar "include('conn.php');" na outra pagina --
