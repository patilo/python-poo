Python-POO: Demostración de Herencia y Clases en Python
Este repositorio contiene una aplicación de ejemplo didáctica diseñada para ilustrar los conceptos fundamentales de la Programación Orientada a Objetos (POO) en Python, centrándose específicamente en el principio de Herencia entre clases.

El proyecto define una clase base (FiguraGeometrica) de la cual heredan otras clases específicas (Cuadrado, Rectangulo), demostrando cómo las clases hijas pueden reutilizar y extender la funcionalidad de la clase padre.

📌 Características Principales
Herencia de Clases: Implementación de una jerarquía de clases con FiguraGeometrica como clase base.

Encapsulamiento: Uso de métodos setter y getter para acceder y modificar atributos de forma controlada (ejemplo de la clase FiguraGeometrica).

Clase Principal (Testing.py): Uso de un script principal para instanciar, manipular y probar las diferentes clases.

Manejo de Dimensiones y Colores: Las figuras geométricas manejan sus dimensiones (alto, ancho) y un atributo de color.

📂 Estructura del ProyectoLa estructura del código está diseñada para ser modular y fácil de entender

FiguraGeometrica.py: Clase Base (Superclase). Define la estructura fundamental de una figura, incluyendo atributos básicos (ancho, alto, color) y sus métodos getter/setter.

Rectangulo.py: Clase hija que hereda de FiguraGeometrica. Extiende la funcionalidad para calcular el área específica de un rectángulo.

Cuadrado.py: Clase hija que hereda de FiguraGeometrica. Representa un cuadrado (un tipo de rectángulo con lados iguales) e implementa la lógica de inicialización y cálculo de área.

Color.py: Clase auxiliar que puede utilizarse para inicializar y gestionar el atributo de color de las figuras.

Testing.py: Módulo Principal. Contiene el código de ejemplo que importa, instancia y ejecuta los métodos de las clases Cuadrado y Rectangulo