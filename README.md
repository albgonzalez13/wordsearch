# Sopa de Letras - README

## Descripción
Este proyecto es un juego interactivo de Sopa de Letras desarrollado en HTML, CSS y JavaScript. Los usuarios pueden buscar palabras relacionadas con un tema navideño dentro de una cuadrícula y ganar puntos al encontrarlas. El juego incluye un temporizador para agregar un desafío adicional.

## Características
- Generación dinámica de una sopa de letras con palabras predefinidas.
- Interfaz gráfica adaptada a diferentes tamaños de pantalla.
- Temporizador de 120 segundos para completar el juego.
- Lista de palabras que se actualiza al encontrar una palabra.
- Sistema de puntuación basado en las palabras encontradas.

## Requisitos
- Navegador web moderno con soporte para HTML5 y Canvas.

## Instalación
1. Descarga los archivos del proyecto.
2. Abre el archivo `index.html` en tu navegador web.

## Instrucciones de Juego
1. Observa la lista de palabras a buscar en la sección inferior del tablero.
2. Haz clic y arrastra el mouse o tu dedo (en dispositivos táctiles) para seleccionar una palabra en la cuadrícula.
3. Si la palabra seleccionada es correcta, será marcada como encontrada y tu puntuación aumentará.
4. Completa todas las palabras antes de que termine el temporizador.


## Personalización
- Las palabras de la sopa de letras se pueden modificar en el arreglo `words` dentro del archivo JavaScript.
- Puedes cambiar el tiempo del juego ajustando la variable `timeRemaining`.
- Los tamaños del tablero y las celdas se ajustan automáticamente al tamaño del navegador, pero se pueden configurar manualmente.
