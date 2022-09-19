# Diagrama 17
## Resolución de problemas en clase con Diagramas de Flujo de Datos
### Ejercicio 17. Escribe un dfd que indique cuanto te falta para llegar a 10 o si pasaste de 10
#### 1.1 Análisis
Pedir al usuario un número mediante el símbolo de salida de datos y el ingreso de este por el símbolo de entrada de datos, posteriormente por medio del símbolo de decisión verificar si el número es mayor o menor a 10, si no es mayor a 10 realizar una resta de 10-número, si es mayor a 10 realizar una resta de número-10, indiar al usuario si le falta para llegar a 10 y cuánto o si se paso de 10 y por cuánto
#### 1.2 Diagrama de Flujo de Datos
![Diagrama_17](https://user-images.githubusercontent.com/113486125/190940434-563104be-bc5c-4cad-b4f1-cbb42cee3f24.png)

Diagrama_17
#### 1.3 Prueba de Escritorio
| Datos | num>10 | Operación | mensaje |
| -------- | ----------- | ----------- | ----------- |
| num | si | r1=num-10 | "te pasaste por", r1 |
| num | no | r2=10-num | "te falta", n2 |
#### 1.4 Entradas
Números enteros
#### Salidas
Te pasaste por...
Te falta...
