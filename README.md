# Project-Ontwerp_2021-2022
## RGBDDigit Clock
The project started with the question “What are the minimal requirements to design a system that is both safe and user friendly - for an RGB Digit Clock”. The content of the application note is the methods used for the project, the Information about the materials and it also includes the result.

This project RGB Digit Clock which means the clock can change into many colours. If we connect a BME280 break-out board (BoB), then it is possible for this circuit to also display temperature, humidity, or air pressure very well. It is an interesting piece of equipment that has many useful functions, it is definitely worth taking a deeper look at. In the course of this project, the following auxiliary materials were used as a starting point: Elektor magazine.

The application note is structured as follows. All the materials and methods that are used can be found/retrieved. This chapter also explains the purpose of each component.

##	Material and methods

### Esp-12
The clock is controlled by an ESP12 module, so it can be synchronized with a time server on the Internet, con-trolled with a mobile device or computer in the network, or receive sensor data via Wi-Fi. 

![image](https://user-images.githubusercontent.com/43784134/120729252-ef35db00-c4de-11eb-9552-c910ad681a94.png)

### Multi-colour 7-segment

This display has eight 5050-RGB NeoPixel LEDs (seven segments plus decimal point) with integrated three-chip chips, allowing the user to control the color and brightness of each individual segment via a 3-wire bus (VCC, GND, and DATA). 

![image](https://user-images.githubusercontent.com/43784134/120729502-9ca8ee80-c4df-11eb-932e-048ad6a66bc9.png)

## PCB Design

![Pcb_3d](https://user-images.githubusercontent.com/43784134/120729898-96674200-c4e0-11eb-9319-ea3c14ec6ac2.PNG)
