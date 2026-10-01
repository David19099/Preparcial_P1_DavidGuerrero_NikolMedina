# Preparcial_P1_DavidGuerrero_NikolMedina
 Integrantes

* Nikol Fernanda Medina Monterrey
* David Santiago Guerrero García

 Descripción del proyecto

Este proyecto consiste en el desarrollo de un programa en Python para controlar el recaudo de dinero de una caja.

El programa solicita el código del cajero y un tope máximo de recaudo. Luego permite registrar diferentes transacciones, acumula el dinero recibido y cuenta la cantidad de transacciones realizadas.

El proceso finaliza cuando se alcanza o supera el tope de recaudo o cuando se ingresa un monto de 0, indicando el fin de la cola.

Al finalizar, el programa muestra un reporte con la información del turno.

 Objetivo

Desarrollar un programa que permita:

* Registrar el código del cajero.
* Establecer un tope máximo de recaudo.
* Registrar los montos recibidos en cada transacción.
* Calcular el total recaudado.
* Contar el número de transacciones.
* Calcular el promedio por transacción.
* Determinar el motivo de cierre de la caja.
* Validar valores inválidos y negativos.

 Funcionamiento

1. Solicitar el código del cajero.
2. Solicitar el tope máximo de recaudo.
3. Validar que el tope sea un valor válido y no negativo.
4. Inicializar el contador de transacciones y el total recaudado.
5. Solicitar el monto recibido en cada transacción.
6. Validar que el monto sea un número válido y no negativo.
7. Sumar el monto recibido al total recaudado.
8. Incrementar el contador de transacciones.
9. Verificar si el total recaudado alcanzó o superó el tope.
10. Verificar si el monto recibido es 0.
11. Calcular el promedio por transacción.
12. Mostrar el reporte final del turno.

 Motivos de cierre

 Tope Alcanzado

Ocurre cuando:

python
totalRecaudado >= topeRecaudo


 Fin de Cola

Ocurre cuando:

python
montoRecibido == 0


 Validación de datos

El programa controla los valores inválidos y negativos mediante ciclos de validación y manejo de excepciones.

Si se introduce un valor no numérico, se muestra:

text
Valor inválido. Inténtalo de nuevo


Si se introduce un número negativo, se solicita nuevamente el valor.

 Cálculos realizados

 Total recaudado

python
totalRecaudado += montoRecibido


 Número de transacciones

python
contadorTransacciones += 1


 Promedio por transacción

python
promedioTransacciones = totalRecaudado / contadorTransacciones


 Reporte final

Al finalizar, el programa muestra:

* Código del cajero.
* Tope asignado.
* Número de transacciones.
* Recaudo total.
* Promedio por transacción.
* Motivo de cierre.

 Pruebas realizadas

Se realizaron seis conjuntos de datos:

1. Cierre por fin de cola.
2. Tope alcanzado exactamente.
3. Se supera el tope.
4. Varias transacciones.
5. Valores inválidos y negativos.
6. Tope igual a cero.

 Tecnologías utilizadas

* Python
* Programación estructurada
* Ciclos while
* Condicionales if
* Manejo de excepciones try/except

 Autores

Nikol Fernanda Medina Monterrey

David Santiago Guerrero García

Universidad de Santander
Programación de Computadores I
Bucaramanga, Santander
2026
