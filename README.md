# Jey_Jey
Este programa es un "semaforo" de advertencia de fechas de expiracion o vencimiento.

Es muy simple ya que se ingresa la fecha de elaboracion o produccion de un producto, y luego se 
ingresa la fecha de expiracion o vencimiento, ambas con el formato (dd mm aaaa)
Una vez ingresadas se ejecuta el programa y se obtienen distintos datos:

-La cantidad de segundos entre las dos fechas. (es la base del calculo ya que las fechas
son traducidas internamente a segundos por el programa). 

-La cantidad de dias entre las fechas ingresadas.

-La cantidad de dias restantes para la expiracion o vencimiento.

Ademas el fondo de la consola se va a teñir de alguno de los tres colores ( rojo, amarillo, verde)
el cual dependerá de la proximidad a la fecha de vencimiento teniendo en cuenta el rango entre la fecha de
elaboracion, la fecha actual y la fecha que va a expirar.

Funciona entonces como una ALERTA DE VENCIMIENTO ya que 
* Al salir color verde permite saber que proporcionalmente la fecha de vencimiento es lejana.
* Al salir color amarillo perimte saber que hay que estar atento ya que está en un rango intermedio y merece revisiones
periodicas. 
* Al salir color rojo, permite saber que es PROXIMA  a vencer o expirar y hay que poner ATENCION! y estar ALERTA!.


