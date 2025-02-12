# LOGIN
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Login</title>
    <link rel="stylesheet" href="stylemio.css">
    </head>
    <body>
        <form>
            <div class="img-formulario">
            <img src="login.jpg" alt="Login" width="50">
        </div>
            <label for="nombre">Nombre:</label>
            <input type="name" id="name" name="nombre" required>
            <label for="email">Correo electronico:</label>
            <input type="email" id="email" name="email" required>
            <label for="contraseña">Contraseña:</label>
            <input type="password" id="contraseña" name="contraseña" required minlength="8">
            <button class="mi-boton">Login</button>
        </form>
    </body>
</html>
