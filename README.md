![YouCardWord](https://lh6.googleusercontent.com/Qrlsap0HazwiUiznMHxxh5EwsYiA3O8R_TJ937gKyhkZbASbOM_4erDl7yKClluHvSoIO9dFuPU502w=w1920-h971)


### YouCardWord
YouCardWord Es un juego divertido y emocionante con el que podras aprender repasar la estructura de diferentes palabras en el idioma inglés, basado en el ppopular juego "Hearstone: Heroes of Warcraft"

### Descripción del juego/aplicación
El juego se centra en formar frases en inglés por medio de cartas, las dos posibilidades de frases que permiten un mayor daño son:
* Noun + Verb
* Noun + Verb + Conjuntion + Noun + Verb

![Card](http://i.imgur.com/IhhRuCu.png) ![Card2](http://i.imgur.com/zQTABvZ.png) ![Card3](http://i.imgur.com/7ciIvg7.png)

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
