# Laboratorio 06: Comandos de Terminal en Linux

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
# 1. Verificar ubicación actual
pwd

# 2. Crear la estructura de directorios
mkdir -p ~/laboratorio/datos/entrada
mkdir -p ~/laboratorio/datos/salida
mkdir -p ~/laboratorio/scripts
mkdir -p ~/laboratorio/respaldo

# 3. Verificar la estructura creada
ls -la ~/laboratorio
```

![Captura del ejercicio 1.1](imagenes/cap1.png)

📁 Ejercicio 1.2: Operaciones con Archivos

🎯 Objetivo:
Practicar navegación entre directorios y manipulación básica de archivos.

💡 Solución:

```bash
# 4. Navegar entre los diferentes directorios
cd ~/laboratorio
cd datos
cd entrada

# 5. Crear tres archivos de texto vacíos
touch datos1.txt datos2.txt config.cfg

# 6. Copiar "datos1.txt" al directorio "respaldo"
cp datos1.txt ~/laboratorio/respaldo/

# 7. Mover "config.cfg" al directorio raíz del laboratorio
mv config.cfg ~/laboratorio/

# 8. Eliminar "datos2.txt"
rm datos2.txt
``` 

