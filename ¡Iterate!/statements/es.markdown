# Descripcion

Al trabajar con Karel notaras que es sencillo darle una intrucción, como por ejemplo moverse un espacio al norte, entonces deberas escribir el comando "*move()*".

Pero digamos que quieres que Karel avance 12 espacios, entonces tendrías que escribir 12 veces el mismo comando "*move()*", para evitar esto Karel es capaz de usar el comando "***iterate()***", y funciona así:

    iterate(<numero-positvo>)
    {
    <instrucción>
    <instrucción>
    ...
    <instrucción>
    }

Por ejemplo, si Karel necesita ir 5 calles al norte, se veria algo asi:

    iterate(5)
    {
    move();
    }

# Problema

Karel necesita que le ayudes a llegar a la casa de su amigo Rodrigo, Rodrigo vive a 7 cuadras al norte de donde se encuentra Karel. Ayuda a Karel a reunirse con su amigo.

# Entrada

![Entrada](entrada.png)

# Salida

![Salida](salida.png)
