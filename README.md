# tso-semaphores-monitors

## Sincronización y Comunicación de Procesos: Problema de la Fabrica

En una fabrica se disponen de tres robots denominados A, B y C; que producen
piezas de tipo A, B y C respectivamente. Los tres robots disponen de una plataforma
común para depositar las piezas que fabrican. El robot C requiere dos piezas de tipo
A y dos piezas de tipo B para producir una pieza de tipo C que es el resultado final.
Considere que los robots A y B pueden operar en cualquier orden, pero el robot C no
operará hasta que haya dos piezas de tipo A y dos piezas de tipo B. Una vez
producida la pieza C, los robots A y B pueden volver a operar. Además, considerar
que la plataforma dispone de una capacidad máxima para albergar dos piezas de
tipo A y dos piezas de tipo B. Realizar tres funciones que modelen el
comportamiento de los robots A, B y C teniendo en cuenta las condiciones
establecidas en el enunciado.