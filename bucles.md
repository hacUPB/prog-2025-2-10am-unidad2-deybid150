**Ejercicios de bucles**

**Ejercicio 2**

|input|output|control|
|-----|------|-------|
|N|ceros, mayores, menores (contador)|N|
|Cantidad|


**pseudocodigo**

```
inicio
leer N
ceros = 0 
menores = 0
mayores = 0
mientras N > 0
    leer cantidad
    Si cantidad > 0:
        mayores  = mayores +1
    si no
        si cantidad = 0
            ceros = ceros + 1
        si no 
            menores = menores + 1
        Fin si
    Fin si
    N = N - 1
    Fn mientras
mostrar ceros, mayores, menores
Fin
```
**diagrama de flujo**

**Ejercicio 3**

**Pseudocodigo**

|input|output|control|
|-----|------|-------|
|N!|SOL|N!|


```
INICIO
leer N!
si N! = 0
    sol = 1
si no 
    si N! = 1
        SOL = 1
    Si no 
        mientras N > 1
         SOL = N!*(N!-1) N! > 1
       fin mientras
    fin si
fin si

