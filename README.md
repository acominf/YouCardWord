![YouCardWord](https://scontent.fgdl3-1.fna.fbcdn.net/v/t31.0-8/18700537_1681478655200459_5470767357924799890_o.png?oh=9d7891cfd6b85e9d2e5a4d5ccb0b8389&oe=59BC7262)


### YouCardWord
YouCardWord Es un juego divertido y emocionante con el que podras aprender repasar la estructura de diferentes palabras en el idioma inglés, basado en el ppopular juego "Hearstone: Heroes of Warcraft"

### Descripción del juego/aplicación
El juego se centra en formar frases en inglés por medio de cartas, las dos posibilidades de frases que permiten un mayor daño son:
* Noun + Verb
* Noun + Verb + Conjuntion + Noun + Verb

![Card](https://scontent.fgdl3-1.fna.fbcdn.net/v/t1.0-9/18670970_1681477285200596_4226131143494742345_n.png?oh=aa2f52fa3418fb3150589b33405d7ed0&oe=59AFEB0A) ![Card2](https://scontent.fgdl3-1.fna.fbcdn.net/v/t1.0-9/18740259_1681477278533930_8745701218070817224_n.png?oh=5ab9aac1721988a45acefb1dcaac7ff3&oe=59B15816) ![Card3](https://scontent.fgdl3-1.fna.fbcdn.net/v/t1.0-9/18740388_1681477288533929_2053864633726795815_n.png?oh=35b99e3981e1b3c592e5f51dccb722f5&oe=59AE17C4)

Ejemplos:
* THE DOG + RUN ó
* THE GIRL + SLEEP + WHILE + THE BABY + CRY.

Se tiene como inicio el turno del jugador:
* El mazo cuenta con 40 cartas.
* Se utilizan Q,W,E,R,T,Y,U para selecciónar cuál carta se desea jugar y A para finalmente jugar dicha carta.
* Se inicia con 5 cartas en la mano.
* Se pueden tomar hasta 3 cartas por turno, con un límite de 7 en la mano.
* El turno no finaliza hasta dar clic en el botón amarillo que dice "Finish turn".
* El tiempo aplica una suma de puntos a cada verbo que esté jugado en el tablero: Future +1, Simple past +2, Participle past +3.
* No importa el orden en que estén acomodadas las cartas, siempre y cuando respeten la suma, se obtendrá el daño correcto.
* Cualquier combinación diferente generará un pequeño ataque, mucho menor al ataque generado por una frase completa.
La maquina jugará de forma automática, y el objetivo será vencerla antes de que ella lo haga a nosotros.

### Clases principales y sus características
1. Nivel
* Realiza los movimientos del jugador computadora.
* Dibuja todos los elementos gráficos del nivel.
* Es el encargado de realizar las interacciones entre ambos jugadores.

2. GameSystem
* Calcula el daño del mazo de cualquiera de los dos jugadores.
* Ordena el tablero para permitir la generación de las frases.
* Limpia el tabledo una vez terminado el turno.

3. Player
* Permite tirar y tomar cartas.
* Contiene los puntos de vida.
* Almacena los mazoz y manos de: jugador y computadora.

4. GCard
* Contiene un objeto tipo Card, con éste objeto permitimos el funcionamiento de GameSystem
* Contiene el icono correspondiente a cada carta.
* Contiene el tipo de Word que es, ya que esto es indispensable para la formación de frases correctas.

5. Hand
* Contiene una colección de objetos tipo GCard
* Permite regresar, agregar o eliminar cartas.
* Esta clase es usada por mazo, mano y tablero de: jugador y computadora.

### Diagrama de clases
<https://www.lucidchart.com/documents/view/4ee17192-e434-414b-8560-a1813f799770>

### Vídeo
<https://www.youtube.com/embed/ojbyeLdS5VU>

### Autor(es)
El autor(es) del proyecto son:
- Roberto Ignacio Zapata Govea @NaNiver
- Manuel Alejandro Robledo Briones @marbalexbriones
### Materia(s)
- Programación Orientada a Objetos

### Semestre
- 2016-2017/II

### Universidad Autónoma de San Luis Potosí, 2017
