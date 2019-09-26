# Descripción

Karel es un robot ocupado, siempre necesita tomar deciciones deficiles, para esto utiliza el comando "***If***" para especificar una condicion, y el comando "***Else***" si esta no se cumple:
    
    if( <Condicion> )
    {
        <instrucción>
        <instrucción>
        ...
        <instrucción>
    }
    else
    {
      <instrucción>
    }
        
Al ser un robot Karel es capaz de reconocer su entorno en todo momento; Para saber si alguna dirección (adelante "*front*", derecha "*right*", izquierda "*left*") esta despejada usa la instrucción
"*<dirección>*___IsClear___". O ésta bloqueada por una pared "*<dirección>*___IsBlocked___". Ejemplo:

    if ( frontIsClear ) {
       move();
    } else {
       turnleft();   
    }
    
# Problema

Este año se celebran las miniolimpiadas en la escuala de Karel. En ésta ocación Karel participa en la carrera de obstaculos, la pista tiene 10 yardas de largo, ayuda a Karel a llegar al final de la carrera y saltar los obstaculos de ser necesario.

# Entrada

![Entrada](entrada.png)

# Salida

![Salida](salida.png)
