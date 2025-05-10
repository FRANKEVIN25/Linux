<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Laboratorio 06: Comandos de Terminal en Linux</title>
</head>
<body>

  <h1>Laboratorio 06: Comandos de Terminal en Linux</h1>
  <p>Este repositorio contiene los resultados del Laboratorio 06 del curso de Sistemas Operativos, enfocado en el manejo de comandos de terminal en Linux.</p>

  <h2>Objetivos del laboratorio</h2>
  <ul>
    <li>Familiarización con el entorno de terminal de Linux</li>
    <li>Desarrollo de habilidades prácticas en la ejecución de comandos de terminal</li>
    <li>Progresión desde comandos básicos hasta tareas más avanzadas</li>
    <li>Comprensión de conceptos fundamentales de la línea de comandos Linux</li>
  </ul>

  <h2>Parte I: Comandos de nivel básico</h2>

  <h3>Ejercicio 1.1: Navegación y Gestión de Archivos</h3>
  <p><strong>Objetivo:</strong> Crear una estructura de directorios y realizar operaciones básicas con archivos.</p>

  <h4>Solución:</h4>
  <pre><code>
# Crear directorio principal
mkdir laboratorio06
cd laboratorio06

# Crear subdirectorios
mkdir documentos imagenes scripts

# Crear archivos vacíos
touch documentos/archivo1.txt
touch documentos/archivo2.txt
touch scripts/script1.sh

# Copiar archivo
cp documentos/archivo1.txt documentos/archivo1_copia.txt

# Mover archivo
mv documentos/archivo2.txt imagenes/

# Eliminar archivo
rm documentos/archivo1_copia.txt
  </code></pre>

</body>
</html>
