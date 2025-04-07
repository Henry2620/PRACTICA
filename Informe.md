# Práctica: Configuración de un Proyecto Angular en Linux (WSL)

## 1. Titulo

**Creacion de la estructura basica de un proyecto Angular usando comando linux.**

## 2. Tiempo de duración

180 minutos (aproximadamente)

## 3. Fundamentos:

Angular es un framework frontend mantenido por Google, basado en TypeScript. Permite el desarrollo de aplicaciones web dinámicas mediante componentes, servicios y módulos. Gracias a Angular CLI (Command Line Interface), los desarrolladores pueden crear, compilar y servir proyectos directamente desde la terminal, lo cual resulta altamente productivo en entornos Linux.
Angular se instala sobre Node.js, por lo tanto, es crucial tener Node y npm en el sistema. El flujo de trabajo en Linux inicia con la verificación de dependencias, instalación del CLI de Angular y generación del proyecto. Esta estructura inicial incluye archivos de configuración (`angular.json`, `tsconfig.json`, `package.json`), y carpetas clave como `src/` y `app/`.
El conocimiento de los comandos de Linux agiliza todo este proceso, desde la navegación hasta la ejecución de scripts. Además, el uso de terminal permite un enfoque más ágil, limpio y directo al desarrollo, sin depender de interfaces gráficas.

## 4. Conocimientos previos.

Para realizar esta práctica, el estudiante necesita conocer:

- Comandos básicos de Linux.
- Uso de terminal en Windows.
- Conceptos de desarrollo web.
- Instalación de software en Linux.

## 5. Objetivos a alcanzar

- Configurar y ejecutar un proyecto Angular en Linux usando WSL2.
- Comprender la instalación y configuración de **Node.js** y **Angular CLI**.
- Servir una aplicación Angular en `localhost:4200` desde un entorno Linux dentro de Windows.

## 6. Equipo necesario:

- Computador con **Windows 10/11**.
- **WSL2** habilitado con **Ubuntu** instalado.
- **Node.js** y **npm** instalados.
- **Angular CLI** instalado.

## 7. Material de apoyo.

- [Documentación de Angular](https://angular.io/)
- [Documentación de WSL](https://learn.microsoft.com/en-us/windows/wsl/)
- Guía de comandos básicos de Linux.
- Guía video colocado en la plataforma virtual del Instituto https://drive.google.com/file/d/1OitqZ02pX7VHaVx3qH9eF31mQent65rk/view

## 8. Procedimiento

Paso 1: Verificar Node.js y npm
Paso 2: Instalar Angular CLI: sudo npm install -g @angular/cli
Paso 3: Crear nuevo proyecto Angular: ng new practica-trabajo
<img src = "C:\Users\henry\OneDrive\Documentos\4to Ciclo\PRACTICA\captures\Captura de pantalla 2025-04-06 221132.png" width = "500">
Paso 4: Ingresar al proyecto: cd practica-trabajo
<img src = "C:\Users\henry\OneDrive\Documentos\4to Ciclo\PRACTICA\captures\Captura de pantalla 2025-04-06 221659.png" width = "500">
Paso 5: Servir aplicacion: ng serve
<img src = "C:\Users\henry\OneDrive\Documentos\4to Ciclo\PRACTICA\captures\Captura de pantalla 2025-04-06 221727.png" width = "500">
Paso 6: Crear un componente nuevo: ng g c ejemplo
Paso 7: Crear un servicio nuevo: ng g s datos

## 9. Resultados esperados:

Se espera que el estudiante sea capaz de:

Generar correctamente un proyecto Angular desde cero usando la terminal.
-Entender la estructura de archivos y carpetas de Angular.
-Servir la aplicación y verla corriendo en el navegador.
-Crear componentes y servicios desde CLI.
-Tener un entorno Angular listo para desarrollo personalizado.
-Imagen del resultado final
<img src = "C:\Users\henry\OneDrive\Documentos\4to Ciclo\PRACTICA\captures\Captura de pantalla 2025-04-06 221727.png" width = "500">

## 🔊 Audio Explicativo del Proyecto

## 10. Bibliografía

- Angular Developers. (s.f.). Angular Documentation. Recuperado de https://angular.io/docs
  -Microsoft. (s.f.). Windows Subsystem for Linux Documentation. Recuperado de https://learn.microsoft.com/en-us/windows/wsl/
