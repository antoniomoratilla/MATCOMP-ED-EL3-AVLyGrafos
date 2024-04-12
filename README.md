# EL3 - AVL y Grafos

## AVL

**Ejercicio**:

Continuando con el trabajo realizado anteriormente, y reutilizando aquella parte que se pueda, se desea crear una clase de árbol equilibrado AVL.

El árbol deberá permitir operaciones de inserción y borrado, así como las operaciones necesarias para detectar desequilibrios y re-equilibrar el árbol.

Debe relizarse en su propio paquete.


## Grafos

Un grafo se define como G = <V,A>, donde V es un conjunto de vértices o nodos, y A es el conjunto de arcos que los une.

Existe una variante, denominada grafo dirigido, donde con la misma definición se impone que los arcos tienen una dirección.

El número de vértices o nodos de un grafo se le denomina grado del grafo.

Se denomina lazo o bucle a aquel arco que tiene como origen y fin al mismo nodo.

Un grafo se denomina "sencillo" si se dan dos condiciones:
* No existen lazos.
* No hay más de un arco para unir dos nodos.

Se denomina grafo "múltiple" a aquel que no es sencillo.

Un camino en un grafo es una secuencia de vértices. Dependiendo de si el grafo es múltiple o no, esa secuencia tendrá ciertos condicionantes. Generalizando, se propone un camino como una secuencia de arcos que deben navegarse, para llegar desde un nodo inicial ni a un nodo final nf.

Un camino es simple si los vértices no se repiten en la secuencia, con excepción del primero y el último, que pueden repetirse.

Un ciclo simple es aquel camino de longitud mínima 1 que empieza y termina en el mismo vértice o nodo.

Un grafo se le denomina planar si puede dibujarse en un plano sin que se cricen sus arcos.

Un grafo (no dirigido) se denomina conexo si existe un camino que para todo par de vértices u,v

Se denomina subgrafo a aquel grafo que contiene un subconjunto de nodos de otro grafo (no dirigido), y arcos comunes de ese subconjunto de nodos. Si contiene TODOS los arcos comunes del subconjunto de nodos, se le denomina además como "inducido".

Esta estructura de grafo es muy habitual en matemáticas, pero en aplicaciones de los grafos puede ser necesario añadir información al grafo. Esta información puede añadirse a los nodos del grafo, a los arcos del grafo o a ambos. En estos casos, se denominan como grafos "etiquetados", que pueden ser dirigidos o no dirigidos, si bien habitualmente son dirigidos. En este último caso, se les denomina como grafos anotados.


**Ejercicio**: 

Cree un grafo capaz de almacenar la estructura de un mapa de carreteras, y añada la funcionalidad necesaria para:
Calcular el camino mínimo entre dos nodos del grafo: 
public camino calculaCaminoMinimo(nodo inicial, nodo final)

Añada aquellos métodos que sean necesarios para la operación habitual del grafo: añadir nodos, borrar nodos, recuperar/buscar nodos, añadir arcos, borrar arcos, recuperar/buscar arcos...

Debe realizarse en su propio paquete.



