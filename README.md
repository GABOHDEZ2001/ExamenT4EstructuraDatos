# ExamenT4EstructuraDatos

## Árboles
```
TDA
Descripción
Es una estructura de datos jerárquica que consta de nodos conectados entre sí de
manera organizada. La estructura de árbol se caracteriza por tener un nodo especial
llamado "nodo raíz" desde el cual se ramifican otros nodos, y cada nodo puede
tener cero o más "nodos hijos", que a su vez pueden tener sus propios hijos y así
sucesivamente.
Operaciones básicas
1. Inserción: Agregar un nuevo nodo al árbol.
2. Búsqueda: Buscar un valor específico en el árbol.
3. Eliminación: Eliminar un nodo específico del árbol.
4. Recorridos: Visitar todos los nodos del árbol en un orden específico, como
preorden, inorden y postorden.
5. Altura: Calcular la altura del árbol, es decir, la longitud del camino más largo
desde la raíz hasta una hoja.
6. Tamaño: Contar el número total de nodos en el árbol.
7. Búsqueda del mínimo y máximo: Encontrar el valor más pequeño y el más
grande en el árbol, respectivamente.
8. Verificación de vacío: Comprobar si el árbol está vacío o no.

```
#### Códigos implementados en java

Recorridos de los  Árbol (PRE- IN-POST ORDEN)

[Ejemplo: PRE- IN-POST ORDEN](https://github.com/GABOHDEZ2001/EXAMENT4ED/blob/main/EXAMENTEMA4ESTRUCTURA/src/Arboles/ARBOL.java)


Transformación de la expresión de infija a postfija

[Ejemplo: Transformación](https://github.com/GABOHDEZ2001/EXAMENT4ED/blob/main/EXAMENTEMA4ESTRUCTURA/src/Arboles/Transformacion.java)



## Grafos
```

TDA
Descripción:
Es una estructura de datos que se utiliza para representar relaciones entre objetos.
Consiste en un conjunto de nodos (también llamados vértices) que están
conectados entre sí mediante enlaces (también llamados aristas). Cada arista puede
tener una dirección (grafo dirigido) o no tenerla (grafo no dirigido).
Operaciones básicas:
1. Agregar un nodo: Permite añadir un nuevo nodo al grafo.
2. Eliminar un nodo: Elimina un nodo existente del grafo, junto con todas las
aristas asociadas a él.
3. Agregar una arista: Añade una arista que conecta dos nodos existentes en
el grafo. Dependiendo del tipo de grafo (dirigido o no dirigido), la arista puede
tener una dirección específica o no.
4. Eliminar una arista: Elimina una arista existente del grafo, rompiendo la
conexión entre dos nodos.
5. Verificar la existencia de un nodo: Permite verificar si un nodo específico
está presente en el grafo.
6. Verificar la existencia de una arista: Permite verificar si existe una arista
que conecta dos nodos específicos en el grafo.
7. Obtener los vecinos de un nodo: Devuelve una lista de nodos adyacentes
a un nodo específico en el grafo. En un grafo dirigido, esto puede incluir los
nodos que son sucesores o predecesores del nodo.
8. Recorrer el grafo: Permite visitar todos los nodos y aristas del grafo, ya sea
en profundidad (DFS) o en anchura (BFS), con el fin de realizar tareas como
búsqueda de caminos, análisis de componentes conectados, etc.
```

#### Códigos implementados en java

Implementación de un Grafo (dirigido Y No dirigido )

[Ejemplo Dirigido](https://github.com/GABOHDEZ2001/EXAMENT4ED/blob/main/EXAMENTEMA4ESTRUCTURA/src/Grafos/GrafoDirigido.java)

[Ejemplo No Dirigido](https://github.com/GABOHDEZ2001/EXAMENT4ED/blob/main/EXAMENTEMA4ESTRUCTURA/src/Grafos/GrafoNoDirigido.java)

Implementación mediante matrices de adyacencia

[Ejemplo Con Matriz de adyacencia](https://github.com/GABOHDEZ2001/EXAMENT4ED/blob/main/EXAMENTEMA4ESTRUCTURA/src/Grafos/MatrizAdyacencia.java)



