Para elevar el nivel de las prácticas base deberan realizar las siguintes mejoras para veificar que han comprendido la integración de las **estructuras selectivas, repetitivas, el manejo de operadores lógicos/matemáticos y los arreglos unidimensionales**.

Al tener la lógica base ya resuelta, el reto ahora es la **optimización, validación y escalabilidad** de los algoritmos usando DFD y pseudocódigo.

A continuación, la tabla con las 40 prácticas y la mejora o implementación específica solicitada para cada una:

### Tabla de Mejoras (Prácticas Nivel Examen)

| No. | Práctica Base (Lógica original) | Mejora Solicitada (Implementación Nivel Examen) |
| --- | --- | --- |
| **01** | Mensaje de Bienvenida | **Ciclos:** Pedir al usuario un número $N$ y repetir el mensaje de bienvenida exactamente $N$ veces usando un ciclo `Para` o `Mientras`. |
| **02** | Ficha Informativa Multilínea | **Arreglos 1D:** Guardar el nombre, materia y carrera en un arreglo de texto de 3 posiciones e imprimir su contenido recorriéndolo con un ciclo. |
| **03** | Saludo Personalizado | **Validación (Ciclos):** Usar un ciclo `Repetir-Hasta Que` para evitar que el usuario ingrese un nombre en blanco o un dato numérico (validar longitud). |
| **04** | Registro de Datos Personales | **Operadores Lógicos:** Validar que la edad sea un valor congruente (`edad > 0 Y edad <= 120`). Si es falso, atrapar el error en un ciclo hasta que ingrese una edad real. |
| **05** | Suma de Dos Números | **Acumuladores:** Modificar para sumar $N$ números ingresados por teclado (la cantidad $N$ la decide el usuario al inicio). Usar un acumulador en un ciclo. |
| **06** | Calculadora 4 Operaciones | **Menú y Excepciones:** Crear un menú con `Segun` y validar que el denominador de la división NUNCA sea cero. Si es cero, pedir otro número. |
| **07** | Promedio de Calificaciones | **Arreglos y Condicionales:** Leer 5 calificaciones, guardarlas en un arreglo. Calcular el promedio y contar cuántas calificaciones fueron *mayores o iguales* al promedio. |
| **08** | Cuadrado y Cubo | **Iteración de Rangos:** Generar una tabla de salida para los cuadrados y cubos de los números del 1 al $N$ usando un ciclo determinístico. |
| **09** | División Entera y Módulo | **Lógica Matemática:** Usar un ciclo con restas sucesivas para calcular el cociente y el residuo sin usar los operadores de división ni `MOD`. |
| **10** | Perímetro y Área (Rectángulo) | **Arreglos Paralelos:** Solicitar las bases y alturas de 3 rectángulos diferentes, almacenarlas en dos arreglos, calcular las áreas y decir cuál es el mayor. |
| **11** | Geometría Circular | **Centinela:** Usar un ciclo infinito que calcule áreas hasta que el usuario ingrese un radio negativo o cero (`radio <= 0` como condición de salida). |
| **12** | Volumen de un Cilindro | **Ciclos y Selectivas:** Permitir al usuario elegir entre calcular el volumen de un cilindro, un cubo o una esfera a través de un menú interactivo. |
| **13** | Conversor de Temperatura | **Banderas / Lógica O:** Validar que la temperatura ingresada en Kelvin no sea negativa (`K < 0`). Si lo es, mostrar un mensaje de "Error: Cero Absoluto violado". |
| **14** | Movimiento Rectilíneo Uniforme | **Arreglos y Búsqueda:** Guardar las velocidades calculadas de 5 vehículos en un arreglo unidimensional y determinar cuál fue el vehículo más rápido. |
| **15** | Conversión de Tiempo | **Manejo de Operadores:** Si el usuario ingresa un tiempo negativo, usar una función o multiplicación matemática por $-1$ para forzarlo a positivo antes de convertir. |
| **16** | Cálculo de Interés Simple | **Proyección Iterativa:** Usar un ciclo para mostrar en pantalla cuánto dinero se acumula año con año (desde el año 1 hasta el año $T$). |
| **17** | Cálculo de Nómina Básica | **Arreglos y Acumuladores:** Guardar los sueldos netos de $N$ empleados en un vector y mostrar al final el sueldo neto mayor y el gasto total de la nómina. |
| **18** | Teorema de Pitágoras | **Operadores Relacionales:** Validar con un operador lógico `O` (`catetoA <= 0 O catetoB <= 0`) que los lados sean estrictamente positivos antes de operar. |
| **19** | Distancia entre Dos Puntos | **Arreglos Estructurados:** Recibir las coordenadas $(x, y)$ de 5 puntos, guardarlas en dos arreglos y calcular la distancia de cada punto hacia el Origen $(0,0)$. |
| **20** | Desglose en Billetes | **Arreglos:** Guardar las denominaciones admitidas (1000, 500, 200, 100, 50, 20) en un arreglo unidimensional y hacer el desglose recorriendo el arreglo con un ciclo `Para`. |
| **21** | Determinación de Paridad/Signo | **Vectores y Contadores:** Leer 10 números, guardarlos en un vector. Contar e imprimir cuántos fueron pares, cuántos impares y el porcentaje de positivos. |
| **22** | Clasificación de Triángulos | **Ciclos Anidados:** Poner el programa en un bucle general que pregunte `¿Desea evaluar otro triángulo? (S/N)`. Si responde N, el programa termina. |
| **23** | Calculadora Estadística | **Historial (Arreglos 1D):** Guardar el resultado de las últimas 5 operaciones en un vector. Crear la opción 6 para "Ver Historial de Resultados". |
| **24** | Año Bisiesto | **Filtro de Arreglos:** Solicitar un rango (ej. 2000 a 2050). Guardar en un vector *solamente* los años bisiestos de ese rango y al final imprimir el vector. |
| **25** | Impuestos por Tramos | **Actualización (Update):** Leer los sueldos de 5 trabajadores. A los que ganen menos del salario mínimo, sumarles un bono del $5\%$ y guardar los resultados actualizados. |
| **26** | Promedio con Centinela | **Mínimo y Máximo (Iterativo):** A la par de calcular el promedio, agregar condicionales dentro del ciclo `Mientras` para encontrar el número más alto y más bajo ingresado. |
| **27** | Menú Interactivo (Banco) | **Seguridad con Ciclos:** Solicitar un NIP de 4 dígitos. El usuario tiene un límite de 3 intentos (usar un contador). Si falla 3 veces, finalizar el programa por seguridad. |
| **28** | Generador de Tablas y Factorial | **Inversión de Arreglo:** Guardar los resultados de la tabla de multiplicar en un vector de tamaño 10. Imprimir el vector de reversa (del índice 10 al 1). |
| **29** | Validador de Primos | **Vectores Booleanos/Lógicos:** Dado el número $N$, llenar un vector donde cada índice $i$ guarde `1` si es primo o `0` si no lo es, y recorrerlo para imprimir los primos. |
| **30** | Serie de Fibonacci | **Búsqueda en Arreglo:** Guardar la serie en un vector de $N$ posiciones. Luego, pedir al usuario un índice $X$ y mostrarle directamente el valor guardado en esa posición. |
| **31** | Llenado/Análisis de Vector | **Filtrado de Duplicados:** Desarrollar una lógica anidada que, al momento de imprimir, omita los valores del vector que se encuentren repetidos. |
| **32** | Mínimo, Máximo y Posición | **Condicionales Avanzados:** Modificar la lógica de búsqueda para encontrar el **segundo valor más grande** del vector (requiere mantener memoria de dos máximos simultáneos). |
| **33** | Inversión y Filtrado | **Inversión In-Place:** En lugar de usar un segundo arreglo $B$, invertir los elementos del arreglo $A$ *sobre sí mismo* utilizando una variable temporal de intercambio (Swapping). |
| **34** | Matriz Identidad y Suma | *(Adaptación a 1D)* **Suma por Lotes:** Tener un vector grande de 12 posiciones, dividirlo lógicamente en 3 secciones (de 4 en 4) y sumar los bloques por separado usando condicionales de índice. |
| **35** | Transposición de Matrices | *(Adaptación a 1D)* **Rotación de Vector:** Tomar un vector unidimensional y mover todos sus elementos una posición hacia la derecha (el último elemento pasa a ser el primero). |
| **36** | Subprocesos y Encabezados | **Parámetros Dinámicos:** Modificar la función para que reciba el arreglo unidimensional con los datos, y calcule el tamaño exacto del marco dependiendo de la longitud de las cadenas. |
| **37** | Funciones Matemáticas | **Recursividad / Ciclos:** Replicar la función de Potenciación usando únicamente ciclos de multiplicaciones sucesivas (sin usar el operador `^` o potencias nativas). |
| **38** | Modificación por Referencia | **Ordenamiento Dual:** Agregar un parámetro numérico u operador lógico a la función que le indique si el arreglo debe ordenarse de forma Ascendente o Descendente. |
| **39** | Sistema de Gestión Escolar | **Búsqueda Secuencial (Arreglos):** Tener un vector con los nombres y otro con las calificaciones (Arreglos Paralelos). Pedir un nombre, buscarlo con un ciclo y mostrar si aprobó o reprobó. |
| **40** | Proyecto de Inventarios | **Validación Integral de Operadores:** Al vender un producto (restar cantidad del vector inventario), validar con condicionales lógicos que la cantidad solicitada no exceda el stock actual. |

