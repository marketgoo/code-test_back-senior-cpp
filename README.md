# Prueba de C++: Implementar una cascada de letras tipo "Matrix"

Seguro que eres tan "friky" como nosotros. ;-) Esta primera prueba se trata de implementar la "cascada" de código de Matrix en la consola. Para ello tienes la ayuda de la librería "termbox" que es una versión ligera de ncurses.

El código inicial en "matrix.cpp" contiene unos ejemplos de las funciones de termbox para que te sea más fácil interactuar con ella. (La prueba no es convertirte en un experto en termbox, sino el algoritmo que usas para la cascada).

El entorno que asumimos es linux o macOS, con compiladores compatibles gcc o clang.

## Requisitos principales:

- Implementar la "cascada de código" de Matrix para llegar a un resultado final tal como se muestra en el video `matrix.mp4` (adjunto a este test). El video se ha grabado usando iTerm en macOS.
- Al ejecutar "./matrix" debe mostrar la animación hasta que se pulse la tecla ESC.

## Requisitos alternativos (¡¡Extra puntos!!):

- Utilizar C++ "moderno", que básicamente es usar C++11 o superior.
- Morfeo estará más contento si usas threads (Ej: std::thread).

## Como compilar y requisitos del sistema

Para que no empieces desde cero, hemos creado un esqueleto de aplicación usando CMake. Para compilar por tanto tienes que tener CMake (aunque no es necesario si estás familiarizado con otro método de compilación).

Si usas CMake, tienes que compilar en un directorio alternativo, por ejemplo `build`. Sigue estos pasos:

    $ mkdir build
    $ cd build && cmake ..
    $ make

Esto te creará el ejecutable `matrix` en el directorio `build`.
