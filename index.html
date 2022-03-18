<?php
include("config.php");
session_start();

if($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = mysqli_real_escape_string($db, $_POST['name']);
    $pass = mysqli_real_escape_string($db, $_POST['pass']);
    $sql = "SELECT id_usuario FROM usuario WHERE name = '$name' AND pass = '$pass'";
    $result = mysqli_query($db,$sql);
    $row = mysqli_fetch_array($result,MYSQLI_ASSOC);
    //$active = $row['active'];
    $count = mysqli_num_rows($result);


    if ($count == 1){
        //session_register("name");
        $_SESSION['login_user'] = $name;

        header("location: index.php");
    }else{
        $error = "¡La combinación de usuario y contraseña son incorrectas!";
    }
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iniciar Sesión</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <div class="container-login">
        <form action="" method="post">
            <div class="user">
            <div class="labelA"><label for="name">Nombre:</label></div>    
            <div class="inputA"><input type="text" name="name" id="name"></div>
            </div>
            <div class="pass">
            <div class="labelA"><label for="pass">Contraseña:</label></div>    
            <div class="inputA"> <input type="password" name="pass" id="pass"></div>   
            </div>
            <div class="boton-login">
                <input type="submit" value="Entrar" class="botonA">
            </div>
        </form>
    </div>
</body>
</html>