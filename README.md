<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Trámite CECYTEM</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      color: #333; 
      padding: 2rem;
    }
    .container {
      border: 1px solid #867f7f;
      padding: 20px;
      max-width: 600px;
      margin: 0 auto;
      background-color: #d4d4d4b7;
      border-radius: 8px;
    }
    h2 {
      color: #333;
      text-align: center;
      margin-bottom: 1.5rem;
    }
    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    input, select {
      width: 100%;
      padding: 12px;
      margin-top: 5px;
      margin-bottom: 15px;
      border: 1px solid #ddd;
      border-radius: 4px;
      box-sizing: border-box;
    }
    .nota {
      text-align: center;
      color: #d32f2f;
      margin-bottom: 20px;
      font-weight: bold;
      font-size: 1.1em;
    }
  </style>  
</head>
<body>
  <h2>Colegio de Estudios Científicos y Tecnológicos del Estado de México</h2>
  <p class="nota">Los campos con * son necesarios.</p>

  <div class="container">
    <form>
      <h3>Datos del Alumno</h3>
      
      <label for="plantel">*Plantel:</label>
      <input type="text" id="plantel" name="plantel" required>

      <label for="control">*Número de Control:</label>
      <input type="text" id="control" name="control" required>

      <label for="nombre">*Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="carrera">*Carrera:</label>
      <input type="text" id="carrera" name="carrera" required>

      <label for="semestre">*Semestre:</label>
      <input type="text" id="semestre" name="semestre" required>

      <label for="situacion">*Situación Actual:</label>
      <input type="text" id="situacion" name="situacion" required>

      <h3>Selecciona el Tipo de Trámite</h3>
      
      <label for="tramite">*Tipo de Trámite:</label>
      <select id="tramite" name="tramite">
        <option value="CPCD">Cambio de Plantel Carrera Diferente - CPCD</option>
        <!-- Puedes añadir más opciones si se necesitan -->
      </select>
    </form>
  </div>
</body>
</html>
