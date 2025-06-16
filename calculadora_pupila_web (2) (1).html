<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Calculadora de Pupila Real</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 2rem;
      background: #f9fafb;
      max-width: 500px;
      margin: auto;
    }
    input, button {
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.6rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 0.5rem;
    }
    button {
      background-color: #007bff;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #0056b3;
    }
    .resultado {
      margin-top: 1rem;
      padding: 1rem;
      background-color: #e6ffed;
      border-left: 5px solid #28a745;
      font-weight: bold;
      white-space: pre-wrap;
    }
    .nota {
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #555;
      background: #fff3cd;
      padding: 1rem;
      border-left: 5px solid #ffc107;
    }
    h2 {
      margin-top: 2rem;
      text-align: center;
    }
  </style>
</head>
<body>

  <h2>Calculadora de Pupila Real (Plano del Iris)</h2>

  <label for="pt">Pupila Topográfica (mm):</label>
  <input type="number" id="pt" step="0.01">

  <label for="pip">PIP (Posición del plano del iris medida por OCT, mm):</label>
  <input type="number" id="pip" step="0.01">

  <label for="k">K (Poder corneal en D):</label>
  <input type="number" id="k" step="0.01">

  <button onclick="calcular()">Calcular Pupila Real</button>

  <div class="resultado" id="resultado"></div>

  <div class="nota">
    <strong>Nota:</strong> Esta herramienta calcula el tamaño real de la pupila a nivel del plano del iris utilizando las fórmulas descritas por Camellin et al. (Indian J Ophthalmol, 2024), adaptadas a unidades clínicas. El valor de PIP debe ser medido con OCT en milímetros, y se convierte automáticamente a metros para mantener la consistencia en las unidades.
  </div>

  <script>
    function calcular() {
      const pt = parseFloat(document.getElementById("pt").value);
      const pip = parseFloat(document.getElementById("pip").value) / 1000;
      const k = parseFloat(document.getElementById("k").value);
      const n = 1.336;

      if (isNaN(pt) || isNaN(pip) || isNaN(k) || pip <= 0) {
        document.getElementById("resultado").innerText = "Por favor, introduce todos los valores correctamente.";
        return;
      }

      const L = n / pip;
      const Lp = k + L;
      const M = Lp / L;
      const PI = pt / M;
      const magnificacion = ((M - 1) * 100).toFixed(2);

      document.getElementById("resultado").innerText =
        `Pupila real (plano del iris): ${PI.toFixed(2)} mm\n` +
        `Magnificación: ${magnificacion}%`;
    }
  </script>

</body>
</html>
