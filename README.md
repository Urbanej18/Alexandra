# Alexandra
calculadora del índice de masa corporal
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora   
 de IMC</title>
    <link rel="stylesheet" href="styles.css">   
 </head>
<body>
    <h1>Calculadora de Índice de Masa Corporal (IMC)</h1>

    <form id="formularioIMC">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" required>

        <label for="apellido">Apellido:</label>
        <input type="text" id="apellido" required>

        <label for="peso">Peso   
 (kg):</label>
        <input type="number" id="peso" required>

        <label for="altura">Altura (cm):</label>
        <input type="number" id="altura" required> 1    
1.
github.com
github.com


        <label for="sexo">Sexo:</label>
        <select id="sexo">
            <option value="masculino">Masculino</option>
            <option value="femenino">Femenino</option>
        </select>   


        <label for="ejercicio">Realiza ejercicio regularmente:</label>
        <input type="checkbox" id="ejercicio">

        <label for="enfermedad">¿Tiene alguna enfermedad?</label>
        <select id="enfermedad">
            <option value="ninguna">Ninguna</option>
            <option value="diabetes">Diabetes</option>
            <option value="hipertensión">Hipertensión</option>
            </select>

        <button type="button" onclick="calcularIMC()">Calcular IMC</button>
    </form>

    <div id="resultado"></div>

    <script src="script.js"></script>
</body>
</html>
