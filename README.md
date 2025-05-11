# pracc5

AUTORA: Genesis Chicaiza, Clara Álvarez

TITULO DESCRIPTIVO:

Calculadora de distancia mas corta entre 2 grafos dirigidos

DESCRIPCION:

Contiene una implementación en Java de un algoritmo llamado Budqueda de anchura (BFS) para encontrar el camino más corto entre dos vértices en un grafo dirigido.

INSTRUCCIONES DE INSTALACION:

Clonar el repositorio de GitHub de la calculadora de distancia más corta entre dos grafos.
Asegurarse de tener instalado Java en tu sistema.
Abre el proyecto en tu IDE preferido.
Compila el codigo si es necesario.
Ejecuta desde la clase main.
ESTRUCTURA DEL CODIGO:

La implementación consiste en una clase principal llamada Graph, que representa un grafo dirigido y contiene métodos clave como:
addVertex(V v) para agregar vértices,
addEdge(V v1, V v2) para agregar arcos entre vértices.
shortestPath(V v1, V v2) para encontrar el camino más corto entre dos vértices utilizando BFS.
La clase también incluye métodos auxiliares como obtainAdjacents(V v) para obtener vértices adyacentes y reconstructPath(V v1, V v2, Map<V, V> parentMap) para reconstruir el camino más corto.
Esta implementación proporciona una base sólida para trabajar con grafos dirigidos y encontrar caminos más cortos en aplicaciones como planificación de rutas y navegación.
LICENCIA:

Copyright [2024] [Genesis Chicaiza]Licensed under the Apache License, Version 2.0 (the "License");you may not use this file except in compliance with the License.You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0Unless required by applicable law or agreed to in writing, softwaredistributed under the License is distributed on an "AS IS" BASIS,WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.See the License for the specific language governing permissions andlimitations under the License.
