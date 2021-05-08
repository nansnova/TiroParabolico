# TiroParabolico
Siguiendo el uso de las librerías turtle y freegames implementamos la modelacion de un fenómeno físico

El programa muestra un juego donde una serie de bolas azules que avanzan en la pantalla y con base al click que se le realice en el jueho, se lanzara una bola pequeña roja que va en forma de tiro parabólico. El juego acaba si cualquier bola azul llegue al otro extremo de la pantalla

Lo que se necesita modificar es la velocidad en la que va la bola roja, y que el juego no tenga fin.

# Análisis.

* Se reconocieron cada una de las funciones y que realizaban al momento de ejecutar el código.
* Se ubicaron los valores que establecían la velocidad del proyectil y la función que marca el final del juego.

## Ricardo

1.- Sólo cambié el número 50 de la parte "ontimer(move, )" para que la velocidad del proyectil aumente.

    ontimer(move, 10)

## Nancy

2. Eliminé el "return" ubicado en el "for target" y coloqué una igualación target a 200 para que se pepita el ciclo.

        for target in targets:
            if not inside(target):
                target = 200
