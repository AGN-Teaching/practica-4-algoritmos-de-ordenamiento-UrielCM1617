[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ke8zCzPd)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=13587245)
# Práctica 4: Algoritmos de ordenamiento

## Antecedentes


El problema de ordenamiento se define como:



Entrada: Una secuencia A=〈a1, a2, , an〉 de n números.
Salida: Una permutación A'=〈a'1, a'2, , a'n〉 de los números de la secuencia de A, tal que a'1a'2a'n.



Existen muchos algoritmos que resuelven este problema, siendo la diferencia entre ellos su eficiencia.



En clase estudiamos cinco algoritmos de ordenamiento: insertion sort, selection sort, bubblesort, merge sort y quicksort. Vimos que, en el caso promedio, el tiempo de ejecución de los primeros tres es de orden cuadrático (n2), mientras que el de los últimos dos es proporcional a n n.



¿Qué significa que un algoritmo de ordenamiento tenga eficiencia de n n?
Los algoritmos de ordenamiento con una complejidad de n n Son eficientes y se utilizan para ordenar conjuntos de datos grandes.


## Resultados:


Para poder hacer las pruebas con los algoritmos al mismo tiempo se consideró que el tamaño del arreglo iba ir creciendo de la siguiente manera: 


![Captura de pantalla 2024-01-31 135809](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/89e3b50b-f52f-4daf-a374-ebe81fae1b5d)


y la prueba por cada uno de ellos debíamos de ejecutarla 30 veces, esto quiere decir que para 5 elementos debíamos de ejecutar los 5 algoritmos 30 veces. Por lo que a continuación se mostrarán los resultados de dichas pruebas.


### TABLA TAMAÑO (5)


![Captura de pantalla 2024-01-31 162440](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/af6a304b-e7a1-42ff-a49e-c201552acf4d)


![Captura de pantalla 2024-01-31 162548](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/a25fba2f-6a51-426c-9bc4-848fa1acf3de)
(Gráfica 1, Tamaño 5)


En la siguiente tabla se puede observar que Merge sort tiene un mejor desempeño a comparación de las demás


### TABLA DE TAMAÑO (10)


![Captura de pantalla 2024-01-31 162702](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/cdf4e2ff-611b-4898-9fa3-3ff3bf916a72)


![Captura de pantalla 2024-01-31 162820](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/e74cb828-7e7a-4d18-8012-49ce25d62c0f)
(Gráfica 2, Tamaño 10)


En esta Gráfica se puede observar que el que tuvo un mejor desempeño fue quicksort a comparación del


### TABLA DE TAMAÑO (50)


![Captura de pantalla 2024-01-31 163253](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/f95b5c37-ecc2-4ef7-9f53-86b72e3ef912)


![Captura de pantalla 2024-01-31 164806](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/6e76b046-fd13-418c-83db-448128f883d2)
(Gráfica 3, tamaño 50)


En la siguiente tabla se puede mostrar que algunos algoritmos realizaron el ordenamiento de manera casi similar, y otros podían


### TABLA DE TAMAÑO (500)


![Captura de pantalla 2024-01-31 164652](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/407f1967-57d6-4384-a1d0-ac815864f47f)

![Captura de pantalla 2024-01-31 164727](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/a2584648-cbdc-4cc2-abfe-18a977dd0e58)
(Gráfica 4, tamaño 500)


En la gráfica anterior se puede mostrar que marge sort fue uno de los algoritmos que más rápido terminó el ordenamiento.


### TABLA DE TAMAÑO (1 000)


![Captura de pantalla 2024-01-31 165054](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/f941b86a-a510-426a-bce9-1f90e7eb0c28)


![Captura de pantalla 2024-01-31 165143](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/50d4ffca-a8fe-4a8a-b38c-8a436f9a1075)
(Gráfica 5, tamaño 1 000)


En esta gráfica podemos observar que bubblesort fue la que ejecutó de mejor manera el arreglo de tamaño 1,000, por esto tomando en cuenta que el tiempo hasta este punto fue relativamente rápido.



### TABLA DEL TAMAÑO (5 000)


![Captura de pantalla 2024-01-31 165445](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/ae6c5388-eb67-40bf-809a-39c74ad6e232)


![Captura de pantalla 2024-01-31 165518](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/47070009-36cc-4710-ae84-985573827e9b)
(Gráfica 6, tamaño 5 000)


Para esta gráfica, se tomó en cuenta que ahora el valor más alto es el que se tarda más, ya que a partir de este punto es cuando el ordenamiento empieza a tomar más de tiempo. Por lo que se puede observar que el algoritmo que más tardó en ordenar fue el bubblesort. 


### TABLA DEL TAMAÑO (10 000)


![Captura de pantalla 2024-01-31 165944](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/8cc3fe1b-7c80-4128-a44d-644940e45558)


![Captura de pantalla 2024-01-31 170011](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/896827b1-53fd-4a93-9565-64f5fb5efcc2)

(Gráfica 7, tamaño 10, 000)
Para esta gráfica nuevamente cambiamos la forma de visualizar el que tarda más y el que tarda menos, y se demuestra que el merge sort es muy eficiente en comparación a los demás, y que hace un mejor desempeño con cantidades más grandes.


### TABLA DE TAMAÑO (50 000)


![Captura de pantalla 2024-01-31 170307](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/7bc6cb62-3ca1-436b-b7e4-4052149e9ab7)


![Captura de pantalla 2024-01-31 170341](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/876f9f45-98e8-4d55-9474-9f8efecdcf39)
(Gráfica 8, tamaño 50 000)


En la (Gráfica 7) podemos observar que los primero tres algoritmos: insertion sort, selection sort, bubblesotr son de los más lento, y los últimos dos, quicksort y merge sort son de los más rápidos, eso tomando en cuenta el de tamaño 50 000


### TABLA DE TAMAÑO (100 000)


![Captura de pantalla 2024-01-31 170644](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/8123910f-647a-40c3-b01f-8d1304981a51)


![Captura de pantalla 2024-01-31 170726](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/6246261a-a108-4a57-b57a-dd914d3df7a1)
(Gráfica 9, tamaño 100 000)


En la gráfica de tamaño 100 000 podemos ir observando que de igual manera los tres algoritmos anteriores fueron los que más tiempo se tardaban en ordenar los elementos del arreglo.


## TABLA DE TAMAÑO (500 000)


![Captura de pantalla 2024-01-31 171001](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/5577a548-7056-45f4-b656-e4d973f92535)


![Captura de pantalla 2024-01-31 171031](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/7d6648d5-2ff5-4432-9616-6cc3b712e887)
(Gráfica 10, tamaño 500 000)


El arreglo de tamaño 500 000 fue el que más tardó en ordenar los elementos, en la gráfica se tuvo que ampliar los perímetros, del tiempo, ya que el bubble sort fue el que más tiempo le tomó en ordenarlos, y los últimos dos quicksort y merge sort  fueron los que más rápido lo acomodaron, en seguida se muestran resultados sacados directamente de la ejecución del programa 

![Captura de pantalla 2024-01-31 111438](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/5d2b133a-8052-4126-9c46-cc7e1a48cc4b)
(imagen 1)

![Captura de pantalla 2024-01-31 111503](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/6f4ae2bc-0c32-4323-9a81-0fb42f32c599)
(imagen 2)

### TABLA DEL PROMEDIO

![Captura de pantalla 2024-01-31 171435](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/6fed5078-ee7b-4f67-984a-15eb771441b8)


En la tabla anterior se puede observar el promedio para cada valor de n, a continuación se mostrará la gráfica del promedio.


![Captura de pantalla 2024-01-31 171525](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/458ece76-a426-4520-994d-215bace7f317)
(Gráfica 11, Promedio)


Se puede mostrar que marge sort tuvo un mejor desempeño en cada uno de los tamaños de n.

### TABLA DE Desviación  estándar


![Captura de pantalla 2024-01-31 171621](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/93288815-5a81-47d9-a26d-31569b01ce74)


![Captura de pantalla 2024-01-31 171812](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-UrielCM1617/assets/125332082/5fa5cdd0-5a09-4841-97be-529e90eeb2b0)
(Gráfica 12)


En esta gráfica con la desviación estándar se puede mostrar que tiene casi los mismos datos, tales que demusetran que merge sort es el que tuvo un mejor desempeño.


## Análisis:


Una vez que realizamos los ordenamientos con los distintos tipos de algoritmos, se pudo observar que gradualmente el tiempo iba aumentando, eso en cuestión de algunos, ya que mergesort y quicksort eran de los más rápido, ya que estos tienen la característica de   n n, por lo que en los experimentos que faltaron, los cuales fueron los de 1 000 000, 5 000 000 y 10 000, se puede calcular maso menos el tiempo de ejecución, en cuanto los otros tres, se pudo observar que el tiempo de ejecución era el que más se notaba en aumento, por lo que se decidió ya no probar los restantes. 

En cuanto a las gráficas nos ayudaba a que a representar los resultados y de esa manera, analizar cuáles eran sus ventajas y desventajas

## Conclusiones:

Una vez que se realizó la ejecución de los algoritmos, puedo decir de manera coloquial que hay algunos que tienen un mejor desempeño, incluso después de ejecutar uno con elementos más grandes. Durante esta práctica se usó la misma computadora para ordenar todos los elementos con diferentes. Y mediante las tablas y gráficas mostradas se puede concluir que a partir de elementos más grandes se puede considerar usar unos algoritmos a comparación de otros, de igual manera se puede notar que cada algoritmo funciona de manera distinta y esto igual puede variar del equipo que se tenga .


En conclusión, la elección del algoritmo de ordenamiento depende de varios factores, como el tamaño del conjunto de datos, la eficiencia en el peor caso, el uso de la memoria y la facilidad de implementación. Es crucial comprender las características y el rendimiento de cada algoritmo para seleccionar el más adecuado para una situación particular. Los algoritmos más avanzados como Merge Sort y Quicksort suelen ser preferibles para conjuntos de datos grandes, mientras que los algoritmos simples como Insertion Sort pueden ser útiles para listas pequeñas o cuando la complejidad no es una preocupación primordial.

