Este Programa clasifica números enteros usando estructuras dinámicas.

Clasificación
Par positivo: cola
Impar positivo: pila
Negativo: lista simple
Cero: no se guarda
Estructuras usadas
Pila
Cola
Lista simple
Lista doble
Árbol BST
Funciones principales
Ingresar números
Mostrar estructuras
Ver historial
Construir y recorrer BST
Buscar en BST
Eliminar negativos
Mostrar estadísticas
Reorganizar datos

Sistema de Estructuras Dinámicas en C++
1. Descripción del programa

Este programa fue desarrollado en C++ para practicar estructuras de datos dinámicas, punteros y manejo de memoria.

Permite ingresar números enteros y clasificarlos automáticamente según su tipo.

También guarda un historial, permite construir un árbol BST y realizar operaciones sobre las estructuras.


2 El programa utiliza las siguientes estructuras:

Punteros
Memoria dinámica con new y delete
struct
Nodos
Lista simplemente enlazada
Pila
Cola
Lista doblemente enlazada
Árbol Binario de Búsqueda

3 Logica de funcionamiento
Cada número ingresado se clasifica de la siguiente forma:

Si es par positivo, se guarda en una cola.
Si es impar positivo, se guarda en una pila.
Si es negativo, se guarda en una lista simple.
Si es cero, no se almacena.

Los valores válidos se guardan en una lista doblemente enlazada.

4 El historial almacena:

Valor ingresado
Estructura asignada
Orden de ingreso

5 Arbol BST

El árbol BST se construye cuando el usuario lo solicita desde el menú.

Se forma usando los números positivos almacenados.

Permite mostrar los recorridos:

InOrden
PreOrden
PostOrden


6 Lista de negativos

El programa permite trabajar con los números negativos guardados.

Puede:

Mostrar la lista original
Eliminar negativos cuya magnitud sea menor que 10
Mostrar la lista resultante
Indicar cuántos nodos fueron eliminados

7 Reorganización de las estructuras

El sistema permite reorganizar datos de la pila y la cola.
Vacía la pila en una lista simple auxiliar.
Vacía la cola en otra lista simple.
Muestra ambas listas.
Reconstruye el árbol BST con esos datos.

8 Estadísticas

El programa muestra estadísticas como:

Cantidad de pares positivos
Cantidad de impares positivos
Cantidad de negativos
Cantidad de ceros rechazados
Total de valores válidos
Mayor valor ingresado
Menor valor ingresado


Funcionamiento  
Abre CLion o cualquier otro IDE compatible con C++.
Luego, abre el archivo codigo.cpp que se encuentra en este repositorio.
Copia el contenido del archivo y pégalo en un nuevo proyecto de C++.
Finalmente, ejecuta el programa desde el IDE y utiliza el menú del sistema.
