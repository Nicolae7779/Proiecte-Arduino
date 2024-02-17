# SÎ (Sisteme Încorporate)
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
  - 
---
***Soluția:***

Arhitectura sistemului creat:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%202/Arhitectura%20Arduino.png)

## Laboratorul 3
Componente:

- Arduino Uno
- 2 LED-uri RGB sau 4 LED-uri de culori diferite (pentru exterior și interior)
- 2 Senzori de temperatură
- 1 Buton

Cerință

Asamblarea Arduino:

- Când sistemul este alimentat de la portul USB și utilizatorul va apăsa butonul (se va folosi întreruperea), sistemul va porni și următoarele acțiuni vor fi efectuate:
  - Se va măsura temperatura din exteriorul serei și se va compara cu valorile normale:
     - Dacă citirile sunt normale atunci culoarea verde a LED-ului RGB exterior se va aprinde
     - Dacă citirile nu sunt normale atunci culoarea albastră a LED-ului RGB exterior se va aprinde dacă este prea frig sau culoarea roșie dacă este prea cald
  - Se va măsura temperatura din interiorul serei și se va compara cu valorile normale:
     - Dacă citirile sunt normale atunci culoarea verde a LED-ului RGB interior se va aprinde
     - Dacă citirile nu sunt normale atunci culoarea albastră a LED-ului RGB interior se va aprinde dacă este prea frig sau culoarea roșie dacă este prea cald.

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
***Soluția:***

Arhitectura sistemului creat:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%204/Proiect%20Arduino.jpg)

System architecture created in Tinkercad:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%204/Arhitectura%20sistemului%20-%20Tinkercad.png)

## Laboratorul 5
- Să se implementeze un semafor pentru pietoni, semaphorePietoni, folosind clasa Traffic Light deja definită. Semafoarele se vor sincroniza astfel încât când pentru pietoni este verde, pentru vehicule este roșu (atenție la decalajele de timp).
- Să se implementeze un difuzor pentru semaforul pietonal destinat persoanelor nevăzătoare. Acesta va emite un sunet când semaforul este roșu și alt sunet când semaforul pietonal este verde.
- Să se implementeze un buton pentru semaforul pietonal. Odată ce butonul este apăsat, semaforul pentru mașini va deveni roșu, iar semaforul pentru pietoni va deveni verde.
  
Pentru vehicule, timpul va fi:

- 4 Secunde roșu;
- 6 Secunde verde;
- 2 Secunde galben;

Pentru pietoni, timpul va fi:

- 3 Secunde verde;
- 9 Secunde roșu;
  
Diagrama de timp a semafoarelor este prezentată în tabelul următor:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%205/Diagrama%20timpi.png)

## Laboratorul 6
Componente:

Arduino Uno
2 LED-uri RGB sau 4 LED-uri de culori diferite (pentru exterior și interior)
2 Senzori de temperatură
1 Buton
1 LED Roșu
Cerință

Asamblare Arduino:

Când sistemul este alimentat de la portul USB și utilizatorul va apăsa butonul (se va folosi întreruperea), sistemul va porni și următoarele acțiuni vor fi efectuate:
Se va măsura temperatura din exteriorul serei și se va compara cu valorile normale:
Dacă citirile sunt normale atunci culoarea verde a LED-ului RGB exterior se va aprinde
Dacă citirile nu sunt normale atunci culoarea albastră a LED-ului RGB exterior se va aprinde dacă este prea frig sau culoarea roșie dacă este prea cald
Se va măsura temperatura din interiorul serei și se va compara cu valorile normale:
Dacă valorile citite sunt normale atunci culoarea roșie a LED-ului RGB interior se va aprinde
Dacă citirile nu sunt normale atunci LED-ul RGB interior va deveni albastru dacă este prea frig sau roșu dacă este prea cald și difuzorul va avea un sunet diferit pentru cele două situații
Când sistemul este pornit va fi afișat în Monitorul Serial:
Temperatura și umiditatea din exterior: valoare
Temperatura și umiditatea din interior: valoare
Când sistemul este oprit, va fi afișat în Monitorul Serial: OFF
Când butonul este apăsat a doua oară, sistemul de monitorizare se va opri și LED-ul roșu se va aprinde, iar în Monitorul Serial va fi afișat OFF.
Raport

Membrii echipei:

Declarația temei și utilitatea în lumea reală

Componentele asamblării

Diagrama logică și diagrama de clasă

Codul sursă în limbajul C++

codul va trebui să conțină comentarii
Fotografii în timpul laboratorului

Interfața aplicației C# și explicații

Capturi de ecran ale tabelor din baza de date

Grafice/rapoarte

Planul de testare

Concluzii

Arhivarea Codurilor Sursă Arduino și a Aplicației C#

---
***Soluția:***

Arhitectura sistemului creat:

***Solution:***

Schema logică și diagrama de clasă:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Schema%20logica%20si%20diagrama%20de%20clase.png)

Arhitectura sistemului:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Arhitectura%20sistemului.png)

Interfața aplicației C#:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Interfata%20din%20aplicatia%20C%23.png)

Tabelele din baza de date:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Tabelele%20din%20baza%20de%20date.png)

Grafice/rapoarte:

![picture alt](https://github.com/victorcb0/ES/blob/main/Laborator%206/Grafice%20si%20rapoarte.png)
