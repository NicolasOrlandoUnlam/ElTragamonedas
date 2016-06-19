# ElTragamonedas
Programación Básica 2

Consigna
Un Tragamonedas está compuesto por 3 Tambores.
Cuando el Tragamonedas se activa, giran los 3 Tambores. Cada Tambor se detiene en una posición
comprendida entre 1 y 10.
El Tragamonedas entrega un premio cada vez que, luego de ser activado los 3 Tambores se detienen
en la misma posición.
A efectos de poder realizar las pruebas y simular el giro el tambor se crea con un NumberGenerator ,
Hay dos implementaciones encargadas de generar el número del tambor, RandomNumberGenerator y
FixNumberGenerator .
Deberá hacer los test´s aplicando lo visto en clase y comprobando la totalidad de la funcionalidad
requerida.
Implementar la clase Tragamonedas y Tambor a partir de las siguientes Clases e Interfaces:
public Interface NumberGenerator {
/* post: devuelve el número de posición en la que se
* encuentra el Tambor. Es un valor comprendido
* entre 1 y 10.
*/
Integer generate();
}
public class RandoNumberGenerator implements NumberGenerator {
/* post: devuelve el número de posición en la que se
* encuentra el Tambor. Es un valor comprendido
* entre 1 y 10.
*/
public Integer generate() {
}
}
public class FixNumberGenerator implements NumberGenerator {
/* Este generador devolverá siempre number cuando se llame al método generate()
*/
public FixNumberGenerator (Integer number) {
}
/* post: devuelve el número de posición en la que se
* encuentra el Tambor. Es un valor comprendido
* entre 1 y 10.
*/
public Integer generate() {
}
}
public class Tambor {
public Tambor(NumberGenerator generator) {
}
/* post: devuelve el número de posición en la que se
* encuentra el Tambor. Es un valor comprendido
* entre 1 y 10.
*/
public Integer getPosicion() {
}
/* post: hace girar el tambor y luego se detiene en
* una posición comprendida entre 1 y 10.
*/
public void girar() {
}
}
public class Tragamonedas {
/* post: los 3 Tambores del Tragamonedas están
* en la posición 1.
*/
public Tragamonedas() {
}
/* post: activa el Tragamonedas haciendo girar
* sus 3 Tambores.
*/
public void activar() {
}
/* post: indica si el Tragamonedas entrega un premio
* a partir de la posición de sus 3 Tambores.
*/
public Boolean entregaPremio() {
}
}
