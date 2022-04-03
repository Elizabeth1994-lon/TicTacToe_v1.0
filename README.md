# TicTacToe_v1.0
Industrial Robotics final project University of Antioquia, the Tic-Tac-Toe game is won by completing a row or diagonal using X or O

La robótica aplicada a juegos interactivos constituye un excelente problema para explorar la colaboración humana-robot, ya que presenta una estructura cuya complejidad (al menos en términos de software) es fácil de ser incrementada.

En este trabajo se presenta un sistema basado en un robot capaz de jugar al triqui con un oponente humano de forma natural.

La interacción con el oponente humano se lleva a cabo mediante visión artificial, la principal ventaja de este sistema mecatrónico frente a otros similares es que opera con una estructura general, por lo cual podrá ser adaptado para realizar otras tareas.

Pasos a seguir del juego
el humano hace un moviemiento (coloque una ficha en el tablero de juego)
se captura una imagen del tablero de juego
procesa la imagen para determinar el movimiento realizado por el humano
determina dónde mover su ficha
usa el brazo para hacer su movimiento
determina si hay victoria o empate
pide al humano que se mueva de nuevo o indica un empate o una victoria del robot
Este conjunto de acciones continúa hasta que se completa el juego o el humano indica el deseo de abandonar.

Archivos ejecutar con su resultado fina
Para poder llevar a acabo los pasos anteriores se hace necesario la utilizacion de tres archivos .py los cuales son:
  * Funciones_del_robot: en este archivo se encuentran las funciones con las cuales se podrá mover el robot, se inicializa el puerto serial, se inicializan los        movimientos en x, y, z, y también velocidad, aceleración de los motores de cada articulación, 
  * Funciones_tres_en_raya: por medio de este archivo encontramos funciones que nos ayudaran para el movimiento del robot donde podrá validar si es ganador o  donde debería realizar el próximo movimiento, también como validación el tablero se irá creando  en la pantalla del PC y en este archivo también se encuentra la forma de dibujar este tablero 
  * identify_player: por medio de este archivo, se hace el reconocimiento de imágenes, las áreas para dibujar el tablero digitalmente,se identifican los centroides de cada uno de las imágenes y el área del tablero en la que se encuentre, de esta manera nos indica, en qué posición del tablero de ha hecho alguna de las jugadas.

Archivos contienen los experimentos previos
