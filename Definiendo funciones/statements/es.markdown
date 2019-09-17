#Descripción

Para darle instrucciones a karel NO necesitas llevarlo a la escuela de Beeperopolis o repetirselo 100 veces, existe una funcion llamada "**define**" que ayuda a karel a recordar todo.

Por ejemplo, para moverse tres espacios hacia adelante, en vez de poner 3 veces el comando "*move();*",puedes poner solamente un **define**  fuera del "**program () {**" con su respectivo nombre (el que se desee), y de esta manera puedes llamar a la funcion dentro del "**program () {**"   las veces que lo desees y se cumplirá lo que se escribió en el **define** como por ejemplo:

     class program {
       define salto()
       {
         move();
         move();
         move();
       }
     program () {
        salto();
        turnoff();       
     }
    }

# Problema

Karel, caminando por el bosque y sin darse cuenta se perdió, solamente necesita dar media vuelta y  asi poder regresar por el mismo camino

Utiliza la funcion "**define**" para girar dos veces a la derecha.

# Entrada

![Entrada](entrada.png)

# Salida

![salida](salida.png)
