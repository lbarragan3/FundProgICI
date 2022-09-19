# Diagrama 18
## Resolución de problemas en clase con Diagramas de Flujo de Datos 
### Ejercicio 18. Realizar un dfd que capture números positivos mayores a cero y que indique si el número es par o inpar.
#### 1.1 Análisis
Pedir un número al usuario mediante el símbolo de salida de datos, este será ingresado por el usuario mediante el símbolo de entrada de datos, mediante el símbolo de decisión verificar que el número sea mayor a 0, posteriormente usando de nuevo este mismo símolo verificar que este sea par o inpar.
#### 1.2 Diagrama de Flujo de Datos
![Diagrama_18](https://user-images.githubusercontent.com/113486125/190941675-d2dde5db-7d18-4597-8b63-ec98ecf47c7a.png)

Diagrama_18
#### Prueba de Escritorio
| Datos | n>0 | n%2==0 | salida |
| ----------- | ----------- | ----------- | ----------- |
| num | si | si | es par |
| num | si | no | es inpar |
| num | no | no | no | num, no puede ser negativo |
#### 1.4 Entradas
valor numérico
#### Salidas
Tu número es par
Tu número es inpar
