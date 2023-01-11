# Ejercicio-2--formularios-en-html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Ejercicio 02 - Formularios en HTML</title>
</head>
<body>
    <form action="resultados.html" method="GET">
    <div>
        <label for="nombreusuario">Nombre de usuario</label>
        <input type="text" name="nombreusuario" id="nombreusuario" />
    </div>
    <br>
    <div>
        <label for="edad">Cuál es tu edad?</label>
        <input type="number" name="edad" id="edad" min="0" max="100" step="5" />
    </div>
    <br>
    <div>
        <label for="frase-favorita">Cuál es tu frase favorita?</label>
        <input type="date" name="nacimiento" id="nacimiento" />
    </div>
    <br>
    <button type="reset">Reset</button>
    <button type="submit">Enviar</button>
    </form>
</body>
</html>
