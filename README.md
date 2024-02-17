# ES (Sisteme Încorporate)
Sistemele încorporate sunt sisteme de calcul specializate pentru sarcini specifice, integrate în dispozitivele din jurul nostru. Arduino este o platformă de dezvoltare open-source, folosită frecvent pentru prototipare rapidă în acest domeniu. În laboratoarele prezentate, veți explora Arduino și veți învăța să interacționați cu componente hardware și să programați microcontrolere pentru diverse aplicații practice.

## Laboratorul 1
După parcurgerea exemplelor din acest laborator, creați următoarea asamblare și folosind mediul de programare Arduino IDE scrieți codul sursă. Pentru testarea funcționalității codul sursă va fi încărcat pe Arduino UNO.

Componente:
- Arduino UNO
- 2 Senzori de temperatură
- Buton
- 1 LED
- Fire de conectare
- 1 LCD
  
Dacă utilizatorul apasă butonul o dată, LED-ul se va aprinde, iar dacă apasă de două ori, valoarea citită de la senzori va fi afișată pe Monitorul Serial.

## Laboratorul 2
Folosind exemplele prezentate în acest laborator, se va crea următoarea asamblare și folosind Arduino IDE codul sursă va fi scris și încărcat pe Arduino din simulator pentru a verifica funcționalitatea.

Componente:

- Arduino UNO
- Senzor de temperatură
- Buton
- 3 LED-uri
- Fire de conectare

  Când placa de dezvoltare este alimentată, LED-ul roșu se va aprinde, iar când utilizatorul apasă butonul următoarele acțiuni se vor întâmpla:

- LED-ul verde se aprinde și LED-ul roșu se stinge
- Sistemul va măsura temperatura
- Se vor defini 4 scenarii pentru intervale de temperatură, pentru fiecare interval LED-ul galben/albastru va avea o intensitate diferită.
- Temperatura va fi afișată pe Monitorul Serial

  Dacă utilizatorul apasă de două ori, sistemul se va opri, LED-ul roșu se va aprinde și LED-ul verde se va stinge.

Se va crea un document Word cu următoarele informații:

- Prima pagină va conține numele studentului
- A doua și a treia pagină vor conține:
  - Cerințele exercițiului
  - O figură realizată cu simulatorul Arduino
  - Codul sursă, vor exista și comentarii în cod
---
***Soluția:***

Arhitectura sistemului creat:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%202/Arhitectura%20Arduino.png)

## Laboratory 3
Components:
- Arduino Uno
- 2 RGB LEDs or 4 LEDs of different colors (for exterior and interior)
- 2 Temperature sensors
- 1 Button

Requirement

Arduino assembly:
- When the system is powered from the USB port and the user will press the button (interrupt will be used), the system will start and the following actions will be performed:
  - Will measure the temperature outside the greenhouse and compare it with the normal values:
    - If the readings are normal then the green color of the outdoor RGB LED will light up
    - If the readings are not normal then the blue color of the outdoor RGB LED will light up if it is too cold or the red color if it is too hot
  - Will measure the temperature inside the greenhouse and compare with normal values:
    - If the readings are normal then the green color of the indoor RGB LED will light up
    - If the readings are not normal then the blue color of the indoor RGB LED will light up if it is too cold or the red color if it is too hot.

## Laboratory 4
Components:
- Arduino Uno
- 2 Leds
- 1 LCD
- 1 Servo motor
- 1 Speaker
- 3 Buttons

Requirement

When power is applied to the system the red LED will light up.

When the first button is pressed the system will do the following:
- The green LED will light up
- A startup message will be displayed on the LCD
- When the second button is pressed, the servo motor will move to the left, and the speaker will play a certain song
- When the third button is pressed, the servomotor will move to the right, and the speaker will play another song

A Word document will be created with the following information:
- The first page will contain the name of the student
- The second and third pages will contain:
  - Exercise requirements
  - A figure made with the Arduino simulator
  - The source code, there will also be comments in the code
  - The link to the system on Tinkercad

---
***Solution:***

The architecture of the created system:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%204/Proiect%20Arduino.jpg)

System architecture created in Tinkercad:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%204/Arhitectura%20sistemului%20-%20Tinkercad.png)

## Laboratory 5
- To implement a traffic light for pedestrians, semaphorePietoni, using the already defined Traffic Light class. The traffic lights will synchronize so that when pedestrians are green, vehicles are red (pay attention to time lags).
- To implement a pedestrian traffic light speaker for blind people. It will emit a sound when the traffic light is red and another sound when the pedestrian traffic light is green.
- To implement a button for the pedestrian traffic lights. Once the button is pressed, the traffic light for cars will turn red, and the traffic light for pedestrians will turn green.

For vehicles the times will be:
- 4 Red seconds;
- 6 Seconds green;
- 2 Seconds yellow;

For pedestrians the times will be:
• 3 Seconds green;
• 9 Seconds red;

The timing diagram of the traffic lights are presented in the following table:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%205/Diagrama%20timpi.png)

## Laboratory 6
Components:
- Arduino Uno
- 2 RGB LEDs or 4 LEDs of different colors (for exterior and interior)
- 2 Temperature sensors
- 1 Button
- 1 Red LED

Requirement

Arduino Assembly:
- When the system is powered from the USB port and the user will press the button (interrupt will be used), the system will start and the following actions will be performed:
  - Will measure the temperature outside the greenhouse and compare it with the normal values:
    - If the readings are normal then the green color of the outdoor RGB LED will light up
    - If the readings are not normal then the blue color of the outdoor RGB LED will light up if it is too cold or the red color if it is too hot
  - Will measure the temperature inside the greenhouse and compare with normal values:
    - If the read values are normal then the red color of the indoor RGB LED will light up
    - If the readings are not normal then the indoor RGB LED will turn blue if it is too cold or red if it is too hot and the speaker will have a different sound for the two situations
  - When the system is started it will be displayed in Serial Monitor:
    - Outside temperature and humidity: value
    - Indoor temperature and humidity: value
  - When the system is turned off, it will be displayed in Serial Monitor: OFF
  - When the button is pressed a second time, the monitoring system will stop and the red LED will light up, and OFF will be displayed in the Serial Monitor.

Report

Team members:

1. Theme statement and real-world utility

2. Assembly components

3. Logical diagram and class diagram

4. Source code in C++ language
- the code will have to contain comments

5. Photos during the laboratory

6. C# application interface and explanations

7. Screenshots of the database tables

8. Graphs/reports

9. Test plan

10. Conclusions

11. Archived Arduino Source Codes and C# Application

---
***Solution:***

Logical scheme and class diagram:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Schema%20logica%20si%20diagrama%20de%20clase.png)

System architecture:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Arhitectura%20sistemului.png)

C# application interface:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Interfata%20din%20aplicatia%20C%23.png)

The tables in the database:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Tabelele%20din%20baza%20de%20date.png)

Graphs/reports:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Grafice%20si%20rapoarte.png)
