.. -*- coding: utf-8 -*-

.. _documentando:

=====================
Reconocimiento Facial
=====================


  :Autores: Luis Antonio Makepeace de León, Luis Emilio García Aguilón 
  :Usuarios GIT: MaKeIA, Lega1991

Proyecto orientado a la inteligencia artificial donde se hará uso de las redes neuronales artificiales 
para la implementacion de un reconocimiento de rostros. El reconocimiento de rostros humanos en imágenes 
digitales se compone de un conjunto de técnicas para la preparación de imágenes y reconocimiento de patrones, así como, 
también, métodos de aprendizaje de rostros. Para reconocer un rostro se debe de realizar los siguientes pasos:

- Pre-procesamiento de la imagen
- Extracción de características
- Entrenamiento
- Reconocimiento


Entradas y Salidas
===================

Entradas:
   Se tomaran aleatoriamente imagenes con rostros de diferentes puntos de vista. Aproximadamente unas 5 diferentes estilos por cada foto.
   Con el fin de tener una mejor eficiencia al reconocer un rostro. Por cada rostro se hara una extraccion de informacion de la imagen
   que sea irrelevante, normalizacion de tamaño (para todos los rostros) y metodo de filtrado. 

Salidas:
  Al finalizar todo el proceso se tendra una base donde ya se habra identificado los rostros y cada vez que se muestra cada uno de ello se sabra de quien es el rostro mostrando un numero o nombre.
  
Ambientes del Sistema
======================

Accesible:
	Es accesible, ya que este agente tiene acceso completo al estado del medio ambiente al que está sometido (el rostro humano) todo el tiempo.

No Determinista:
	Es no determinista, porque el agente no realiza una serie de pasos en especifico para reconocer el rostro humano ya que este puede estar desde varios angulos y en diferentes posiciones.

Discreto:
	Es discreto, por la cantidad limitada de aspectos que el agente debe evaluar para poder detectar el rostro humano, por ejemplo 
	todo humano tiene una boca, una nariz, dos ojos y dos orejas, además de una estructura facial determinada que involucra un 
	mentón, dos mejillas, dos pómulos y una frente.

No Episódico:
	Es no episódico, porque este agente tendrá como fin un solo objetivo el cual es “Detectar el rostro humano” y no tendrá algún 
	otro objetivo que este.
