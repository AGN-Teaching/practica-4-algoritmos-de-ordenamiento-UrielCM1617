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

## Análisis:
## Conclusiones:
