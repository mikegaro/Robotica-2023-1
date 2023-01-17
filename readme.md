# Robotica 2023-1 **(Redesign team)**
---
## Integrantes
 - Garcia Oñate Miguel Angel
 - Mendoza Reyes Carlos Mauricio
 - Lazcano Romero Eduardo Alejandro
 - Torres Guerrero Adair
 ---
## Objetivo general
- Rediseñar el robot móvil dofbot para su posterior utilización en pruebas
---
## Objetivos específicos
- Definir una distribución de los elementos electrónicos en el robot, basándonos en el
modelo comercial
---
## Primer día, mié 30/11/22
- Instalacion SW 2020
- Inicio de planeación → probablemente iniciaremos con esquemáticos del robot
ROSMASTER X3 PLUS para comparar sus dimensiones y distribución con el actual
(Requerimos SW)
- Descargamos dofbot-cad-min.zip, el cad del robot. En este repo GITHUB
---
## Segundo dia, lun 05/12/22
- afecta la forma de la base? por que mantener el track?
- qué lleva el piso inferior? el comercial es mas chico, por qué lo queremos mas
grande?
- donde posicionar los soportes del motor?
---
## Lun 12/12/2022 fue puente
---
## Tercer dia, mie 14/12/22
- cads de partes faltantes
- distribucion de los elementos en los pisos
- tamaño de los pisos y alturas chance
---


## Cuarto día, mie 11/01/23
- La placa inferior del diseño comercial tiene unas dimensiones de 280 mm x 150 mm. Sin embargo, estas medidas no pueden ser tomadas debido al tamaño de la batería que chocaría con los motores.
Se propuso una placa inferior de 200 mm x 320 mm basándonos en las medidas del primer prototipo fabricado con MDF por el profesor Erik Peña Medina. La placa seguía siendo pequeña para posicionar la batería en la parte inferior.
Al final se propuso una placa de 320 mm x 170 mm la cual permitió tener el suficiente espacio para distribuir los componentes y realizar los respectivos agujeros para el cableado.

![Descripción de la imagen](/images/quince.png)

### Distancia entre motores
Para la propuesta de la distancia entre motores el equipo se basó en la distancia del robot comercial la cual es de 44 mm. Esta distancia entre motores es importante ya que le dará estabilidad al robot móvil.

![Descripción de la imagen](/images/uno.jpg)

### Orientación de IBT2
Por cada motor existirá un IBT2 y la para proponer la orientación más óptima de estos componentes se consideró las conexiones entre componentes.

![Descripción de la imagen](/images/tres.jpg)

A continuación, se muestra el diagrama de conexiones entre componentes:

![Descripción de la imagen](/images/dos.jpg)

### Orientación final propuesta:

![Descripción de la imagen](/images/dieciseis.png)

### Propuesta montaje de PCB
Al no conocer las dimensiones de la PCB se propuso crear un piso intermedio en voladizo. Se muestra la propuesta en la siguiente imagen:
 
![Descripción de la imagen](/images/seis.jpg)

 
Para simular la PCB y realizar el montaje de los componentes se insertaron dos protoboards.

![Descripción de la imagen](/images/Protoboard.jpg)


### Ensamble de componentes principales
Nos encontramos con el problema de no poder ensamblar los componentes a la placa inferior debido a todo el espacio que ocupa la batería. Para solucionar esto, se propuso un piso superior en donde se montaron cada uno de los IBT2. 

![Descripción de la imagen](/images/once.jpg)

Los IBT2 se montaron en voladizo esto ayudará a mejorar el paso del aire a través de los disipadores.

![Descripción de la imagen](/images/trece.jpg)

### Diseño del segundo Piso del Robot, para ensamblaje del brazo.
En este punto, se contempló que nuestro diseño (una vez optimizado el espacio) debería contener unas columnas que nos permitieran dejar un piso libre
para ensamblar el brazo del modelo comercial.

---imagen de la Garra
