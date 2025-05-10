# 🧪 Laboratorio 06: Comandos de Terminal en Linux

**Curso:** Sistemas Operativos  
**Tema:** Manejo de comandos de terminal en Linux  
**Autor:** [Jauregui Bendezu, Frank Kevin]  
**Fecha:** [07/05/2025]

---

## 🎯 Objetivos del Laboratorio

- ✅ Familiarización con el entorno de terminal de Linux.  
- ✅ Desarrollo de habilidades prácticas en la ejecución de comandos de terminal.  
- ✅ Progresión desde comandos básicos hasta tareas más avanzadas.  
- ✅ Comprensión de conceptos fundamentales de la línea de comandos de Linux.

---

## 🧩 Parte I: Comandos de Nivel Básico

### 📁 Ejercicio 1.1: Navegación y Gestión de Archivos

**🎯 Objetivo:**  
Crear una estructura de directorios y realizar operaciones básicas con archivos.

**💡 Solución:**

```bash
# 1. Crear el directorio principal del laboratorio
mkdir Laboratorio06
cd Laboratorio06

# 2. Crear subdirectorios para organización
mkdir Documentos Scripts Resultados

# 3. Crear archivos dentro de los directorios
touch Documentos/nota.txt
touch Scripts/script.sh
touch Resultados/datos.txt

# 4. Copiar un archivo
cp Documentos/nota.txt Resultados/

# 5. Mover un archivo
mv Scripts/script.sh Documentos/

# 6. Renombrar un archivo
mv Resultados/datos.txt Resultados/resultado_final.txt

# 7. Eliminar un archivo
rm Documentos/nota.txt

# 8. Ver estructura resultante
tree

