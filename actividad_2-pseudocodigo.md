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

