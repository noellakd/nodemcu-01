# nodemcu-01

# Blinkprogram med Mikroprocessor

## Översikt
Det klassiska "Blinkprogrammet" är ofta det första steget när man lär sig programmera en mikrokontroller. Programmet får en LED lampa att blinka med jämna intervall som indikerar att blinkprogrammet man skapat på datorn i Arduino fungerar.

## Mikroprocessor (som används)
NodeMCU bygger på **ESP8266**, en liten och billig WiFi‑mikroprocessor. Den används ofta i IoT‑projekt (Internet-of-Things) och kan programmeras via Arduino IDE, ett program med öppen källkod, skapat av Arduino

## Två basfunktionerna i Arduino
- **setup()** – Körs endast en gång när mikrokontrollern startar eller resetas.
- **loop()** – Körs om och om igen i en evig loop så länge mikrokontrollern är på.

## Hämta blinkprogram
 Blinkprogrammet kan hämtas under `File` - `Examples` - `01.Basics` - `Blink`

## Setup och Loop
 Under **setup()** - Talar vi om för mikrokontrollen vilken port som ska användas.
 Under **loop()** - Talar vi om hur ofta lampan ska blinka.

## Hämta blinkprogram
 Blinkprogrammet kan hämtas under `File` - `Examples` - `01.Basics` - `Blink`

 
 <img width="1230" height="482" alt="image" src="https://github.com/user-attachments/assets/80208035-a4f6-46dc-b753-a3b11d72d6f8" />


`digitalWrite(ledPin, HIGH)` tänder LED.

`digitalWrite(ledPin, LOW)` släcker LED.

`delay(1000) pausar i 1000 millisekunder (1 sekund).

Resultatet blir att LED blinkar på och av med en sekunds intervall.
 



