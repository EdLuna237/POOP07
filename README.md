# Práctica 7: Herencia en Java
# * Descripción
Esta práctica implementa un sistema de herencia en Java que modela una jerarquía de animales, demostrando los principios fundamentales de la Programación Orientada a Objetos. El proyecto consiste en una estructura de clases organizada donde clases especializadas heredan atributos y comportamientos de clases base, permitiendo la reutilización de código y el polimorfismo.

# * Estructura del Proyecto
El sistema está compuesto por una clase base Animal y tres categorías principales que heredan de ella: AnimalAcuatico, AnimalAereo y AnimalTerrestre. Cada categoría tiene a su vez clases específicas que representan animales concretos: Ballena, Pajaro y Perro respectivamente.

# * Características Implementadas
Herencia: Las clases especializadas extienden la funcionalidad de las clases base usando la palabra clave extends

Encapsulamiento: Todos los atributos son privados y se acceden mediante métodos getter y setter

Polimorfismo: Sobrescritura de métodos como comer() y toString() en cada nivel de la jerarquía

Reutilización de código: Las clases hijas heredan automáticamente los métodos y atributos de las clases padre

# * Funcionalidades
Métodos comunes en la clase Animal: sonido(), comer()

Métodos específicos por categoría: nadar(), volar(), correr()

Métodos únicos por animal: pelearconPinocho() en Ballena, hacerTrucos() en Perro

Constructores que utilizan super() para inicializar atributos heredados

# * Aprendizajes
Esta práctica demostró la importancia de la herencia para crear sistemas escalables y mantenibles, permitiendo modelar relaciones del mundo real de manera natural y organizada. La estructura jerárquica facilita la extensión del sistema con nuevas categorías y tipos de animales sin duplicar código.

Ejecución
El programa principal instancia objetos de diferentes niveles de la jerarquía y demuestra el funcionamiento de la herencia, la sobrescritura de métodos y el acceso a funcionalidades específicas de cada clase.
