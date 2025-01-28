# Taller 1

Este es el proyecto para el **Taller 1**. El código está contenido en el archivo comprimido **Taller1.zip**, que incluye la solución de Visual Studio para el proyecto **MyProject**. El proyecto está configurado para usar **CMake** para gestionar el proceso de compilación.

## Estructura del Proyecto

El archivo **Taller1.zip** contiene la siguiente estructura:


1. **Taller1.zip**: El archivo comprimido que contiene todos los archivos del proyecto.
2. **build/**: Carpeta que contiene los archivos generados por la compilación y la solución del proyecto.
3. **CMakeLists.txt**: Archivo de configuración de CMake utilizado para gestionar el proceso de compilación.
4. **src/**: Carpeta con el código fuente del proyecto, donde se encuentran archivos como **Main.cpp** y **Saludo.h**.
5. **MyProject.sln**: Archivo de solución de Visual Studio que puede abrirse directamente para trabajar con el proyecto en Visual Studio.

## Instrucciones para Compilar y Ejecutar

Para compilar y ejecutar el proyecto, sigue estos pasos:

### 1. **Descomprimir el archivo ZIP**:
   - Extrae el archivo **Taller1.zip** en una carpeta de tu elección.

### 2. **Abrir el Proyecto en Visual Studio**:
   - Abre el archivo **MyProject.sln** en Visual Studio.
   - Si no tienes Visual Studio, puedes descargarlo desde [aquí](https://visualstudio.microsoft.com/downloads/).

### 3. **Configurar el Proyecto con CMake**:
   - Asegúrate de tener instalado **CMake** en tu sistema. Si no lo tienes, puedes descargarlo desde [aquí](https://cmake.org/download/).
   - En Visual Studio, selecciona **CMake > Configure** para configurar el proyecto usando el archivo **CMakeLists.txt**.
   - Selecciona el generador adecuado (por ejemplo, "Visual Studio 16 2019").
   
### 4. **Compilar el Proyecto**:
   - Una vez configurado el proyecto, haz clic en **Build > Build Solution** para compilar el proyecto.

### 5. **Ejecutar el Proyecto**:
   - Después de compilar, puedes ejecutar el proyecto haciendo clic en **Debug > Start Without Debugging** o presionando **Ctrl + F5**.

## Requisitos

- **Visual Studio** (se recomienda la última versión).
- **CMake** para configurar el proyecto y gestionar la compilación.
- El proyecto está configurado para trabajar con **C++** y utiliza **librerías estándar** para manejar la fecha y hora.

## Descripción del Proyecto

Este proyecto realiza un saludo en consola, que incluye el nombre del estudiante y la fecha y hora actual del sistema. Se utiliza una clase **Saludo** para organizar el código y se muestra la fecha y hora en el formato adecuado.

## Archivos del Proyecto

- **CMakeLists.txt**: Archivo de configuración de CMake.
- **MyProject.sln**: Archivo de solución de Visual Studio.
- **Main.cpp**: Código fuente del proyecto.
- **Saludo.h**: Archivo de encabezado con la clase de saludo.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarme a través de mi correo electrónico: [af.vargasc1@uniandes.edu.co].
