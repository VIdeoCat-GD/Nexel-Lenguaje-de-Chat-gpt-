# Nexel-Lenguaje-de-Chat-gpt-
Nexel es un lenguaje de programación interpretado, simple e intuitivo, ideal para crear scripts rápidos y aprender programación. Soporta variables numéricas y de texto, concatenación con +, operaciones matemáticas, bucles while, condicionales if/else y funciones con parámetros. Fácil de usar y depurar.


Nexel – Descripción del Lenguaje

Nexel es un lenguaje de programación interpretado, diseñado para ser simple, intuitivo y flexible, con soporte para operaciones matemáticas, manipulación de strings y estructuras básicas de control de flujo. Está pensado para aprender programación o crear scripts rápidos, y es compatible con el intérprete Nexel v2.7 en C#.

Características Principales

Variables

Tipos: numéricas (double) y strings.

Declaración: var nombre = valor.

Ejemplo:

var nombre = "Ignacio"
var edad = 25


Impresión en pantalla

Comando: print().

Soporta concatenación de strings y números con +.

Ejemplo:

print("Hola " + nombre + ", tienes " + edad + " años")


Operaciones matemáticas

Soporta +, -, *, / y paréntesis.

Ejemplo:

var resultado = 10 + 5 * 2
print("Resultado: " + resultado)


Estructuras de control

Bucle while:

var i = 1
while i <= 5 {
    print("Contador: " + i)
    var i = i + 1
}


Condicional if:

if resultado > 10 {
    print("Resultado mayor que 10")
}


Funciones

Definición:

func saludar(nombre) {
    print("Hola " + nombre + "!")
}


Llamada: saludar("Ignacio")

Concatenación avanzada

Strings y números pueden combinarse libremente dentro de print.

Variables no definidas muestran advertencia y se tratan como 0 para evitar errores fatales.

Errores y depuración

Muestra el número de línea en caso de error de sintaxis o variable no definida.

Facilita identificar y corregir rápidamente los problemas en scripts.
