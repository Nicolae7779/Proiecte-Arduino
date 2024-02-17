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

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%202/Arhitectura%20Arduino.png)

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
Componente:

- Arduino Uno
- 2 Leduri
- 1 LCD
- 1 Motor servo
- 1 Difuzor
- 3 Buton

Cerință

Când se aplică energie sistemului, LED-ul roșu se va aprinde.

Când primul buton este apăsat, sistemul va face următoarele:

- LED-ul verde se va aprinde
- Un mesaj de pornire va fi afișat pe LCD
- Când al doilea buton este apăsat, motorul servo se va mișca spre stânga, și difuzorul va reda un anumit cântec
- Când al treilea buton este apăsat, motorul servo se va mișca spre dreapta, și difuzorul va reda alt cântec
  
Se va crea un document Word cu următoarele informații:

- Prima pagină va conține numele studentului
- A doua și a treia pagină vor conține:
  - Cerințele exercițiului
  - O figură realizată cu simulatorul Arduino
  - Codul sursă, vor exista și comentarii în cod
  - Linkul către sistemul pe Tinkercad

---
***Soluția:***

Arhitectura sistemului creat:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%204/Proiect%20Arduino.jpg)

Arhitectura sistemului creat în Thinkercad:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%204/Arhitectura%20sistemului%20-%20Tinkercad.png)

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

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%205/Diagrama%20timpi.png)

## Laboratorul 6
Componente:

- Arduino Uno
- 2 LED-uri RGB sau 4 LED-uri de culori diferite (pentru exterior și interior)
- 2 Senzori de temperatură
- 1 Buton
- 1 LED Roșu

Cerință

Asamblare Arduino:

- Când sistemul este alimentat de la portul USB și utilizatorul va apăsa butonul (se va folosi întreruperea), sistemul va porni și următoarele acțiuni vor fi efectuate:
  - Se va măsura temperatura din exteriorul serei și se va compara cu valorile normale:
    - Dacă citirile sunt normale atunci culoarea verde a LED-ului RGB exterior se va aprinde
    - Dacă citirile nu sunt normale atunci culoarea albastră a LED-ului RGB exterior se va aprinde dacă este prea frig sau culoarea roșie dacă este prea cald
  - Se va măsura temperatura din interiorul serei și se va compara cu valorile normale:
    - Dacă valorile citite sunt normale atunci culoarea roșie a LED-ului RGB interior se va aprinde
    - Dacă citirile nu sunt normale atunci LED-ul RGB interior va deveni albastru dacă este prea frig sau roșu dacă este prea cald și difuzorul va avea un sunet diferit pentru cele două situații
  - Când sistemul este pornit va fi afișat în Monitorul Serial:
    - Temperatura și umiditatea din exterior: valoare
    - Temperatura și umiditatea din interior: valoare
    - Când sistemul este oprit, va fi afișat în Monitorul Serial: OFF
    - Când butonul este apăsat a doua oară, sistemul de monitorizare se va opri și LED-ul roșu se va aprinde, iar în Monitorul Serial va fi afișat OFF.
    - 
Raport


1) Declarația temei și utilitatea în lumea reală

2) Componentele asamblării

3) Diagrama logică și diagrama de clasă

4) Codul sursă în limbajul C++

- codul va trebui să conțină comentarii
1) Fotografii în timpul laboratorului

2) Interfața aplicației C# și explicații

3) Capturi de ecran ale tabelor din baza de date

4) Grafice/rapoarte

5) Planul de testare

6) Concluzii

7) Arhivarea Codurilor Sursă Arduino și a Aplicației C#

---
***Soluția:***

Schema logică și diagrama de clasă:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%206/Schema%20logica%20si%20diagrama%20de%20clase.png)

Arhitectura sistemului:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%206/Arhitectura%20sistemului.png)

Interfața aplicației C#:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%206/Interfata%20din%20aplicatia%20C%23.png)

Tabelele din baza de date:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%206/Tabelele%20din%20baza%20de%20date.png)

Grafice/rapoarte:

![imagine](https://github.com/Nicolae7779/Proiecte-Arduino/blob/main/Laborator%206/Grafice%20si%20rapoarte.png)
