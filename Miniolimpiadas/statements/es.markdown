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
        
Al ser un robot Karel es capaz de reconocer su entorno en todo momento. Para esto tiene varias preguntas que le puedes hacer a karel:

* **frontIsClear**, si el frente esta libre.
* **frontIsBlocked**, si el frente esta bloqueado.
* **rightIsClear**, si la derecha esta libre.
* **rightIsBlocked**, si la derecha esta bloqueada.
* **leftIsClear**, si la izquierda esta libre.
* **leftIsBlocked**, si la izquierada esta bloqueada.

**Nota:** Si te das cuenta las condiciones tienen una forma muy particular de escribirse ejemplo: "primeroSegundoTercero" la primer palabra se escribe toda en minusculas y las siguientes palabras la primer letra es Mayuscula.

A continuacion un codigo de ejemplo:

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
