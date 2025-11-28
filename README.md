# Blinkprogram med NodeMCU-01

## Översikt
Det klassiska **Blinkprogrammet** är ofta det första steget när man lär sig programmera en mikrokontroller. Programmet får en LED‑lampa att blinka med jämna intervall, vilket visar att koden fungerar på din NodeMCU via Arduino IDE.

## Mikroprocessor
NodeMCU bygger på **ESP8266**, en liten och billig WiFi‑mikroprocessor. Den används ofta i IoT‑projekt (Internet of Things) och kan programmeras via Arduino IDE, ett program med öppen källkod.

## De två basfunktionerna i Arduino
- **setup()** – körs en gång när mikrokontrollern startar eller resetas.
- **loop()** – körs om och om igen i en evig loop så länge mikrokontrollern är på.

## Hämta blinkprogram
Blinkprogrammet finns i Arduino IDE under:  
`File` → `Examples` → `01.Basics` → `Blink`

## Setup och Loop (Strukturfunktioner)
- I **setup()** anger vi vilken port som ska användas.  
- I **loop()** bestämmer vi hur ofta lampan ska blinka.

```cpp
digitalWrite(ledPin, HIGH); // HIGH tänder LED lampan
digitalWrite(ledPin, LOW);  // LOW släcker LED lampan
delay(1000);                // Hur lång intervall mellan blinkningar (I detta fallet 1000ms)

```

## Resultat
När programmet körs blinkar LED‑lampan på NodeMCU‑kortet med en sekunds intervall.  
Det visar att koden är korrekt uppladdad och att mikrokontrollern fungerar som den ska.  
