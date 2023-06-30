<!DOCTYPE html>
<html>
<head>
  <title>Calculadora de Matriz</title>
  <style>
    table {
      border-collapse: collapse;
    }
    
    table, th, td {
      border: 1px solid black;
      padding: 5px;
    }
    
    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>
  <h1>Calculadora de Matriz</h1>
  
  <h2>Matriz A</h2>
  <table id="matrixA">
    <tr>
      <th></th>
      <th>Coluna 1</th>
      <th>Coluna 2</th>
      <th>Coluna 3</th>
    </tr>
    <tr>
      <th>Linha 1</th>
      <td><input type="text" id="a11"></td>
      <td><input type="text" id="a12"></td>
      <td><input type="text" id="a13"></td>
    </tr>
    <tr>
      <th>Linha 2</th>
      <td><input type="text" id="a21"></td>
      <td><input type="text" id="a22"></td>
      <td><input type="text" id="a23"></td>
    </tr>
  </table>
  
  <h2>Matriz B</h2>
  <table id="matrixB">
    <tr>
      <th></th>
      <th>Coluna 1</th>
      <th>Coluna 2</th>
      <th>Coluna 3</th>
    </tr>
    <tr>
      <th>Linha 1</th>
      <td><input type="text" id="b11"></td>
      <td><input type="text" id="b12"></td>
      <td><input type="text" id="b13"></td>
    </tr>
    <tr>
      <th>Linha 2</th>
      <td><input type="text" id="b21"></td>
      <td><input type="text" id="b22"></td>
      <td><input type="text" id="b23"></td>
    </tr>
  </table>
  
  <button onclick="calcularMatriz()">Calcular</button>
  
  <h2>Resultado</h2>
  <table id="resultado">
    <tr>
      <th></th>
      <th>Coluna 1</th>
      <th>Coluna 2</th>
      <th>Coluna 3</th>
    </tr>
    <tr>
      <th>Linha 1</th>
      <td id="r11"></td>
      <td id="r12"></td>
      <td id="r13"></td>
    </tr>
    <tr>
      <th>Linha 2</th>
      <td id="r21"></td>
      <td id="r22"></td>
      <td id="r23"></td>
    </tr>
  </table>
  
  <script>
    function calcularMatriz() {
      // Obter os valores da matriz A
      var a11 = parseFloat(document.getElementById("a11").value);
      var a12 = parseFloat(document.getElementById("a12").value);
      var a13 =
# D
