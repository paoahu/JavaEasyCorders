- [Ejercicion 1](#ejercicio1)
- [Ejercicion 2](#ejercicio2)
- [Solucion Ejercicio 1](#solucionEjercicio1)

### Ejercicio1

La Liga de eSports (LE) está formada por ocho equipos como, por ejemplo, los Code Warriors o los Stream Giants. Cada equipo tiene un nombre, una fecha de fundación, un presupuesto y una dirección donde realizan sus entrenamientos y competiciones. Por ejemplo, los Code Warriors, fundados el 12 de enero de 2010, tienen un presupuesto de 2.000.000 € y entrenan en la Calle Ficticia 123 de Madrid. Por otro lado, los Stream Giants tienen un presupuesto de 3.500.000 € y entrenan en la Avenida de los Streamers 45.

Cada equipo está compuesto por jugadores. La normativa indica que cada jugador debe tener un alias y un nombre que lo identifique. Además, todos los jugadores tienen un salario. Por ejemplo, el jugador más famoso de la liga, CyberAce, juega en los Cyber Knights y gana 120.000 € al año.

Según la normativa, los equipos solo pueden hacer ofertas a los jugadores, ficharlos cuando estos aceptan las ofertas y vender jugadores. Por su parte, los jugadores solo pueden entrenar, competir y aceptar o rechazar las ofertas.

**Recientemente, los Stream Giants han hecho una oferta a CyberAce para ficharlo durante tres años y pagarle 250.000 € al año**. Los Stream Giants están esperando recibir una respuesta de CyberAce.

Basándote en la descripción del problema anterior:

a) Indica los objetos o instancias que aparecen (solo el nombre).

b) Indica las clases que ves (solo el nombre).

c) Para cada una de las clases que has mencionado en el apartado "b", indica los atributos y métodos según lo que dice el texto.

d) Para cada objeto identificado en el apartado "a", indica a qué clase de las mencionadas en el apartado "b" pertenece.

e) Para cada objeto indica el valor que tienen los atributos de la clase a la cual pertenece. Si para un atributo no se indica el valor en el texto, pon "Desconocido".

f) ¿Con qué concepto de la POO se relaciona la frase en negrita?

### Ejercicio2

# Solucion Ejercicio 1


## a) Objetos o instancias que aparecen:
1. Code Warriors
2. Stream Giants
3. CyberAce

## b) Clases que veo:
1. Equipo
2. Jugador

## c) Atributos y métodos de cada clase:

**Clase `Equipo`**:
- **Atributos**:
  - nombre
  - fecha_fundacion
  - presupuesto
  - direccion
  - jugadores (lista de jugadores)
- **Métodos**:
  - hacerOferta(jugador, salario, años)
  - ficharJugador(jugador)
  - venderJugador(jugador)

**Clase `Jugador`**:
- **Atributos**:
  - alias
  - nombre
  - salario
- **Métodos**:
  - entrenar()
  - competir()
  - aceptarOferta(oferta)
  - rechazarOferta(oferta)

## d) Clase a la que pertenece cada objeto:
1. Code Warriors -> `Equipo`
2. Stream Giants -> `Equipo`
3. CyberAce -> `Jugador`

## e) Valores de los atributos de cada objeto:

**Code Warriors** (Clase: `Equipo`):
- nombre: "Code Warriors"
- fecha_fundacion: "12 de enero de 2010"
- presupuesto: 2.000.000 €
- direccion: "Calle Ficticia 123, Madrid"
- jugadores: Desconocido

**Stream Giants** (Clase: `Equipo`):
- nombre: "Stream Giants"
- fecha_fundacion: Desconocido
- presupuesto: 3.500.000 €
- direccion: "Avenida de los Streamers 45"
- jugadores: Desconocido

**CyberAce** (Clase: `Jugador`):
- alias: "CyberAce"
- nombre: Desconocido
- salario: 120.000 € al año
- equipo: "Cyber Knights"

## f) Concepto de la POO relacionado con la frase en negrita:
El concepto de la Programación Orientada a Objetos (POO) relacionado con la frase en negrita es **Polimorfismo**. En este contexto, significa que los jugadores pueden realizar acciones como entrenar, competir y aceptar o rechazar ofertas, mientras que los equipos pueden realizar acciones como hacer ofertas, fichar jugadores y vender jugadores. Las acciones que pueden realizar los objetos dependen de la clase a la que pertenecen.
