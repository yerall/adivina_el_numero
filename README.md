# Adivina_el_Numero

Un pequeño juego desarrollado en Python donde el jugador debe adivinar un número secreto generado aleatoriamente.

El programa genera un número aleatorio entre **1 y 10**. El jugador dispone de **3 intentos** para descubrir cuál es.

Después de cada intento, el juego indica si el número ingresado es **mayor** o **menor** que el número secreto hasta que el jugador gane o se quede sin intentos.
## Características

- Número aleatorio entre 1 y 10.
- Tres intentos para adivinar.
- Pistas después de cada intento.
- Validación para números fuera del rango permitido.
- Interfaz sencilla y amigable mediante la consola.

## Cómo ejecutar el juego

1. Clona este repositorio.

```
git clone https://github.com/tu_usuario/adivina-el-numero.git
```

2. Ingresa a la carpeta del proyecto.

```
cd adivina-el-numero
```

3. Ejecuta el programa.

```
python adivina_numero.py
```

## Ejemplo de ejecución

```
================================
    BIENVENIDO AL JUEGO
     ADIVINA EL NÚMERO
================================
Debes adivinar un número entre 1 y 10.
Tienes 3 intentos.

Intentos restantes: 3
Ingresa un número: 5

Muy alto.
Te quedan 2 intentos.

Intentos restantes: 2
Ingresa un número: 3

¡FELICIDADES!
Adivinaste el número secreto: 3
```

# Lo que aprendí

Con este proyecto practiqué conceptos básicos de Python como:

- Variables.
- Condicionales (`if`, `elif`, `else`).
- Ciclos `while`.
- Entrada y salida de datos (`input()` y `print()`).
- Uso del módulo `random`.
- Validación de datos.
- Uso de operadores de comparación.
