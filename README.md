<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Malla Curricular Medicina - Estilo Claro Elegante</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<style>
  body {
    font-family: 'Poppins', sans-serif;
    background-color: #f9f7f9; /* Blanco suave */
    margin: 40px 60px;
    color: #4a3f55; /* Morado grisáceo oscuro */
    min-height: 100vh;
  }
  h1 {
    text-align: center;
    color: #7e5ca2; /* Lavanda elegante */
    font-weight: 700;
    font-size: 3rem;
    margin-bottom: 50px;
    text-shadow: 1px 1px 2px #b8a6c8;
  }
  table {
    border-collapse: collapse;
    width: 100%;
    max-width: 900px;
    margin: 0 auto 60px;
    background: #fff; /* Fondo blanco */
    border-radius: 12px;
    box-shadow: 0 0 20px #c9b7dfcc; /* Sombra lavanda clara */
    overflow: hidden;
  }
  th, td {
    padding: 14px 20px;
    border-bottom: 1px solid #d6c7e4;
    text-align: left;
    cursor: pointer;
    user-select: none;
    transition: background-color 0.3s ease;
  }
  th {
    background-color: #a892c7; /* Lavanda medio */
    color: #f2eff7; /* Blanco lavanda */
    font-weight: 700;
    letter-spacing: 0.07em;
    cursor: default;
  }
  tbody tr:nth-child(even) {
    background-color: #f3eff9; /* Lavanda muy claro */
  }
  tbody tr:nth-child(odd) {
    background-color: #e8e1f3; /* Lavanda claro */
  }
  tbody tr:hover td {
    background-color: #d6c7e4; /* Lavanda suave */
  }
  td.aprobado {
    background-color: #c9b7dfcc !important; /* Lavanda pastel */
    color: #5b4780;
    font-weight: 700;
    box-shadow: inset 0 0 10px #9a7bc1;
  }
</style>
</head>
<body>

<h1>Malla Curricular Medicina</h1>

<table id="malla">
  <thead>
    <tr>
      <th>1er Nivel</th>
      <th>2do Nivel</th>
      <th>3er Nivel</th>
      <th>4to Nivel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Lenguaje y Comunicación Académica</td>
      <td>Investigación I</td>
      <td>Deontología y Bioética</td>
      <td>Prácticas Servicio Comunitario 1</td>
    </tr>
    <tr>
      <td>Histología y Embriología</td>
      <td>Morfofisiología I</td>
      <td>Bioestadística</td>
      <td>Medicina Comunitaria Intercultural I</td>
    </tr>
    <tr>
      <td>Bioquímica y Nutrición</td>
      <td>Microbiología y Parasitología</td>
      <td>Morfofisiología II</td>
      <td>Anatomía Patológica</td>
    </tr>
    <tr>
      <td>Introducción a la Medicina General Integral</td>
      <td>Genética e Inmunología</td>
      <td>Medicina General Integral</td>
      <td>Morfofisiología III</td>
    </tr>
    <tr>
      <td>Biología Celular y Molecular</td>
      <td>Educación y Prevención para la Salud</td>
      <td>Inglés Médico</td>
      <td>Psicología Médica</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td>Propedéutica Clínica y Semiología</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>5to Nivel</th>
      <th>6to Nivel</th>
      <th>7mo Nivel</th>
      <th>8vo Nivel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Prácticas Servicio Comunitario 2</td>
      <td>Medicina Interna</td>
      <td>Imagenología</td>
      <td>Gerencia y Administración de Salud</td>
    </tr>
    <tr>
      <td>Medicina Comunitaria Intercultural II</td>
      <td>Farmacología Clínica</td>
      <td>Pediatría</td>
      <td>Cirugía General</td>
    </tr>
    <tr>
      <td>Fisiopatología</td>
      <td>Salud Ocupacional y Bioseguridad</td>
      <td>Epidemiología</td>
      <td>Ginecología y Obstetricia</td>
    </tr>
    <tr>
      <td>Farmacología Básica</td>
      <td>Informática Médica y Telemedicina</td>
      <td>Medicina Alternativa y Complementaria</td>
      <td>Cuidado Integral de la Salud (APS)</td>
    </tr>
    <tr>
      <td>Sexualidad, Género y Salud</td>
      <td>Infectología y Medicina Tropical</td>
      <td>Dermatología</td>
      <td>Anestesia y Medicina del Dolor</td>
    </tr>
    <tr>
      <td>Laboratorio Clínico</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>9no Nivel</th>
      <th>10mo Nivel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Salud Pública y Atención en Crisis Humanitarias</td>
      <td>Titulación</td>
    </tr>
    <tr>
      <td>Endocrinología</td>
      <td>Traumatología y Ortopedia</td>
    </tr>
    <tr>
      <td>Medicina Legal</td>
      <td>Nefrología y Urología</td>
    </tr>
    <tr>
      <td>Neurología</td>
      <td>Geriatría y Gerontología</td>
    </tr>
    <tr>
      <td>Psiquiatría</td>
      <td>Otorrinolaringología y Oftalmología</td>
    </tr>
  </tbody>
</table>

<script>
  function setCellIds() {
    const tables = document.querySelectorAll('table');
    tables.forEach((table, tIndex) => {
      Array.from(table.tBodies).forEach(tbody => {
        Array.from(tbody.rows).forEach((row, rIndex) => {
          Array.from(row.cells).forEach((cell, cIndex) => {
            cell.id = `t${tIndex}_r${rIndex}_c${cIndex}`;
          });
        });
      });
    });
  }

  function loadApproved() {
    const approved = JSON.parse(localStorage.getItem('celdasAprobadas') || '[]');
    approved.forEach(id => {
      const cell = document.getElementById(id);
      if(cell) cell.classList.add('aprobado');
    });
  }

  function saveApproved() {
    const allCells = document.querySelectorAll('td');
    const approved = [];
    allCells.forEach(cell => {
      if(cell.classList.contains('aprobado')) approved.push(cell.id);
    });
    localStorage.setItem('celdasAprobadas', JSON.stringify(approved));
  }

  function setupClicks() {
    const allCells = document.querySelectorAll('td');
    allCells.forEach(cell => {
      cell.addEventListener('click', () => {
        cell.classList.toggle('aprobado');
        saveApproved();
      });
    });
  }

  window.onload = function() {
    setCellIds();
    loadApproved();
    setupClicks();
  }
</script>

</body>
</html>
