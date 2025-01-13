# Conversor de monedas de Alura Latam

Este proyecto es un conversor de monedas desarrollado en Java como parte del curso de Back-end con Java impartido por Alura LATAM en colaboración con Oracle.
Estas conversiones se realizan mediante la API ExchangeRate, la cual permite realizar conversiones en tiempo real entre diferentes monedas que se desee seleccionar.

# Características y funcionalidades

1. Elige conversiones entre el Dólar,el Sol Peruano, Real Brasileño, Peso Colombiano y Viceversa.
2. Conversion actualizada al momento del cambio de moneda: Usa una funcionalidad específica de ExchangeRate-API para convertir cantidades de moneda con la tasa de conversión vigente al momento de realizar la petición.
3. Interfaz simple: Cuenta con un menú de opciones con el cual el usuario podrá interactuar de manera fácil y rápida.
4. Excepciones para manejo de errores: Utiliza excepciones que permiten que el programa sea robusto ante posibles errores al momento de realizar la petición a la API.
5. Salida del programa: El menú de opciones cuenta con una opción para salir del programa, sólo mediante esta opción el programa dejará de ejecutarse y el usuario no tendrá que inicializar nuevamente el programa después de una conversión para volver a realizar conversiones.

# Tecnologías empleadas en el programa

**1. Java 21.0.5**

**2. Gson**

**3. ExchangeRate-API**

# Requisitos previos para instalación y uso del programa

**1. Java Development Kit (JDK) 21.0.5 o más reciente:** Esta versión o cualquier otra versión más reciente debe estar instalada en tu computador antes de ejecutar el programa. Puedes descargar Java 22.0.2 [aquí](https://www.oracle.com/java/technologies/javase/jdk22-archive-downloads.html) o puedes descargar cualquier otra versión más reciente [aquí](https://www.oracle.com/co/java/technologies/downloads/archive/).

**2. Librería Gson:** Se utiliza para obtener los datos de la API que llegan al programa en formato JSON para luego procesarlos con el fin de mostrar los resultados de las conversiones. Se recomienda descargar la versión más reciente, puedes encontrarla [aquí](https://mvnrepository.com/artifact/com.google.code.gson/gson).
