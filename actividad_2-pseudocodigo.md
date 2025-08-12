◉  Inicio / Fin  
   - Indica el punto de inicio o fin del algoritmo. También se llama "símbolo terminal".

▭  Proceso  
   - Representa una acción o instrucción a realizar. Puede ser una operación matemática, asignación, etc.

⬒  Entrada / Salida  
   - Se utiliza para mostrar datos al usuario o para leer datos ingresados. Ejemplos: Leer A, Mostrar resultado.

⬭  Decisión  
   - Representa una condición o pregunta que tiene dos posibles respuestas: Sí o No. Se usa en decisiones (IF, WHILE, etc.).

→  Flecha de Flujo  
   - Indica el orden y la dirección del flujo del algoritmo. Conecta los distintos símbolos.

**Imagen ilustrativa.**

![imagaen ilustrativa](<Captura de pantalla 2025-07-31 104623-1.png>)

**ejercicio 2**

Construye un algoritmo que, al recibir como datos el ID del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.

**solucion**

```
inicio
leer ID, S1, S2, S3, S4, S5, S6
Total = Total / 6
Escribir ID, Total, Promedio
Fin
```
**diagrama de flujo**

![diagrama de flujo](<diagrama ej 2.drawio.png>)

| variables | tipo | comentario|
|-----------|------|-----------|
| lapices   | entrada|cantidad de lapices|
| precio    | salida|precio total|
| valor_unidad| intermedia |valor unitario de cada lapiz|
| 85, 90    | constantes|no cambian|

```
inicio
leer lapices
si lapices >= 1000:
   valor_unidad = 85
si no
   valor_unidad = 90
fin si
precio = lapices * valor_unidad
escribir "el valor total es:" , precio
fin
```
**diagrama de flujo**

![imagen ilustrativa](<lapices m .drawio.png>)

**EJERCICIO 4**

|variables|tipo|comentario|
|---------|----|----------|
|total compra|entrada|valor de la compra|
|descuento|salida|descuento segun el valor de la compra
|precio final|salida|valor a pagar|
|15%, 8%, $250000|constantes|descuentos y valor limite|


**Pseudocodigo**

```

```

**diagrama de flujo**

**EJERCICIO 5**

|VARIABLES|TIPO|COMENTARIO|
|---------|----|----------|
|alumnos|entrada|la cantidad de alumnos|
|costo alumno|salida|el costo por alumno|
|costo total|salida|costo completo|
|>= 100, 65.00|constante|precio cuando es mas de 100 alumnos|
|(50-99), 70.00|constante|precio cuando los alumnos son entre 50 a 99|
|(30-49), 95.00|constante|precio cuando los alumnos son entre 30 a 49|
|<30, 4000.00|constante|precio cuando los alumnos son menores de 30|

**Pseudocodigo**

```
inicio
leer alumnos
si
alumnos >= 100
   costo alumno = 65.00
si no
   si
   alumnos >= 50
      costo alumno = 70.00
   si no
      si
      alumnos >= 49
         costo alumno = 95.00
      si no
         si

```

**diagrama de flujo**

**ejercicio 6**

**pseudocodigo**
```
Inicio
Leer Día_Nacimiento, Mes_Nacimiento, Año_Nacimiento
Leer Día_Actual, Mes_Actual, Año_Actual
Edad = Año_Actual - Año_Nacimiento
Si Mes_Actual < Mes_Nacimiento:
    Edad = Edad -1
Si no
    Si (Mes_Actual = Mes_Nacimiento) y (Dia_Actual < Dia_Nacimiento):
        Edad = Edad -1 
    Fin Si
Fin Si
Escribir "La edad es: ", Edad, " años"
Fin
```

**diagrama de flujo**

![alt text](<ej 6 df.jpg>)


**BUCLES**

Se requiere un algoritmo para obtener la suma de diez cantidades, que se leen del teclado, mediante la utilización de un ciclo while. Realice el diagrama de flujo y el pseudocódigo.

|input|output|control|
|-----|------|-------|
|Cantidad|Suma (acumulador)|i|

**pseudocodigo**

**while**

```
Inicio
SU = 0
i = 0
while C <  10
     Leer cantidad
     Suma = Suma + cantidad
     i = i + 1
Fin mientras
Escribir Suma
Fin
```

**for**

```
Inicio
SU = 0
for i = 1 hasta i = 10
     Leer cantidad
     Suma = Suma + cantidad
Fin desde
Escribir Suma
Fin