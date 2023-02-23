# Arquitectura Hexagonal

### Ejercicio de ejemplo
Dado una implementación en un seudo framework tipo Django, que contiene un modelo Package, 
con campos con sus dimensiones, realizar un seudo endpoint que calcule el volumen de todos los 
paquetes que estén en la base de datos.
La respuesta de dicho endpoind será una lista cuyos elementos tengan el id del paquete, 
el volumen del mismo y un campo que indique el tipo de error.
Si el cálculo de volumen presenta algún error, el parametro volumen será None. En caso contrario el 
parámetro error será None.

