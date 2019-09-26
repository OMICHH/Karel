# Descripción

Karel siendo in increible robot, tiene muchas habilidades bajo la manga, por ejemplo, Karel tiene una pequeña brujula que le permite saber en que dirección esta mirando y en cuál no lo esta haciendo. Para saber esto puedes hacerle a Karel las siguientes preguntas:

* **facingNorth**, sí esta mirando hacia el Norte.
* **notFacingNorth**, sí NO esta mirando al Norte.
* **facingSouth**, sí esta mirando hacia el Sur.
* **notFacingSoutth**, sí NO esta mirando al Sur.
* **facingEast**, sí esta mirando hacia el Este.
* **notFacingEast**, sí NO esta mirando al Este.
* **facingWest**, sí esta mirando hacia el Oeste.
* **notFacingWest**, sí NO esta mirando al Oeste.

Ejemplo:

    if ( facingNorth ) {
       move();
    } else {
       turnleft();   
    }

# Problema

Karel ha tenido unos cuantos problemas ultimamente, para relajarse ha decidido meditar de vez en cuando, siempre mirando hacia el *Este*, sin embargo, Karel no esta en su lugar habitual de meditacion y se le dificulta orientarse correctamente. Ayuda a Karel a mirar hacia el ***Este***.

**Nota:** La orientacion inicial de Karel puede ser cualquier dirección (Norte, Sur, Este u Oeste).

# Entrada

![Entrada](entrada.png)

# Salida

![Salida](salida.png)
