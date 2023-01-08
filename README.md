# Comunicacion UART entre dispositivos con distintos sistemas operativos

### 2do Proyecto Taller de circuitos empotrados
En este proyecto se utiliza el protocolo de comunicacion UART, con el cual se comunican los dispositivos:

  - PC (Ubuntu )
  - Raspberry pi 3 (Raspbian)
  - Microcontrolador de uso especifico (PIC18F4550)
  
De igual forma la recreacion del videojuego de 1973 "Space Race" es capaz de jugar en modo un jugador contra la computadora, la cual cuenta con un sistema basico de 
toma de desiciones variando de la ubicacion y direccion de los asteriodes que detecte en un area cercana a la nave.

En orden de correr el juego en Ubuntu o Raspbian, se deben seguir los siguientes pasos:
  1. Descargar el archivo correspondiente al sistema operativo en el que se va a correr.
  2. Abrir la terminal y ubicarse en el directorio que se descargó recientemente.
  3. Escribir los siguientes comandos:
      ### Para correr en raspbian
        - `gcc -o Raspberry_SpaceRace.c` 
        - `./Raspberry_SpaceRace.c`
        
      ### Para correr en Ubuntu
        - `gcc -o Ubuntu_SpaceRace.c` 
        - `./Ubuntu_SpaceRace.c` 
        
      ### Para correr en el PIC18F4550
        -Se debe descargar la carpeta (PIC_Space_Race) []

Las conexiones alcanzadas son:
  - PIC18F4550 <-> Ubuntu
  - PIC18F4550 <-> Raspberry
  - Raspberry <-> Ubuntu
  - Ubuntu <-> Ubuntu
  - PIC18F4550 <-> PIC18F4550
  - Raspberry <-> Raspberry 
