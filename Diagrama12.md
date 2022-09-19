# Diagrama 12
## Resolución de problemas en clase con Diagramas de Flujo de Datos
### Ejercicio 12. Preguntar año de nacimiento, año actual y calcular edad (desiciones)
#### 1.1 Análisis
Utilizar el símbolo de salida de datos para preguntar el año de nacimiento al usuario, usando el símbolo de entrada de datos el usuario ingresara su año de nacimiento, usar el mismo procedimiento para el año actual, usar el símbolo de decisión para corroborar que el año de nacimiento sea mayor a 0, y que el año actual sea mayor al año de nacimiento, si esto no es así regresar a pedir año de nacimiento, si es verdadero trminar con una resta del año actual menos el año de nacimiento
#### 1.2 Diagrama de Flujo de Datos
![Diagrama_12](https://user-images.githubusercontent.com/113486125/190937257-faaceccb-4fa5-45bc-bdf0-186a4dc1e1d3.png)

Diagrama_12
#### 1.3 Prueba de Escritorio
| Datos | a_nac-a_act | Salida |
| ----------- | ----------- | ----------- |
| a_nac, a_act | no, retroceder y pedir a_nac, si continuar con el calculo de edad | a_act-a_nac |

#### 1.4 Entradas
Año de nacimiento del usuario y año actual
#### Salidas
a_act-a_nac
