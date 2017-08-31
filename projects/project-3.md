---
layout: project
type: project
image: images/
title: Raquetball game
permalink: 
date: 2015
labels:
  - Digital design
  - VHDL
  - LogicWorks
summary: Built a racquetball game for EE 260 (Introduction to Digital Design.) 
---

The racquetball game consisted of two push buttons and six LED lights in a row. The six LEDs depicted the position of the ball. When the ball is served the first LED would light up, then the second, third and so on. When the sixth LED lit up, the ball would "bounce back" and start traveling through the LEDs again towards the players. The player that did not serve the ball, has to hit his/her button when the ball reaches the first LED. If the player misses, the game is over, but if the button is pressed at the right time the ball would go towards the sixth LED again. The project was to build the game with logic gates and the hardware description language VHDL. 

I worked on the project alone, although it was designed to be a group project. I started the project by building the smaller parts of the game. There were three main components to the game. The racquet module, controller and court display. The racquect module was the buttons, and the main part was designing a circuit that would send a signal out when the player presses their button. This seems fairly easy, but it had to be designed so the players can't just hold the button down and continuosly hit the ball back. When the player presses the button, it should send a signal that only lasts for a second or so. The second component was the controller which is the brains of the game. It controlled the LEDs and decided if the the player hit the button at the right time. Instead of builing it using logic gates, I used VHDL instead. VHDL was an easier route because its basically programming. When coding in VHDL, you're telling the hardware what to do through software. When the code was done I downloaded it into an EPROM. The court display was the six LEDs and making sure they light up correctly. Before I built the circuit I built the entire circuit on logicworks. A software that you can use to see how everything in your circuit connects. I built the game successfully. 

This project taught me how to design, build and test. It has been one of my favorite class projects so far. 

For more information about the project go to the link: http://www-ee.eng.hawaii.edu/~tep/EE260/Labsnew/Lab8/lab8.html
